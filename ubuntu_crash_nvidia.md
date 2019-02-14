# Ubuntu crash on upgrade from 16.04 to 16.10

Problem: Could not boot, then stuck in constant login loop

Solution:

1. Restart computer
2. Select "Advanced options"
3. Select kernel
4. Use Ctrl-F1 or Ctrl-F2 to open shell
5. Type in username and password to login in shell
6. In shell:

`
$ sudo apt-get purge nvidia-*
$ sudo add-apt-repository ppa:graphics-drivers/ppa
$ sudo apt-get update
$ sudo apt-get install nvidia-340
`
(Also tried sudo apt-get install --reinstall xserver-xorg-video-intel xserver-xorg-core
sudo dpkg-reconfigure xserver-xorg)
