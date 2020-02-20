## Changing Bash Profile

```sh
atom ~/.bash_profile
```

Once in the `bash_profile` file, you can change the Python path as follows:

```sh
PATH="/usr/local/bin/python:${PATH}"
export PATH
```

## Python 2

```sh
brew install python
```
```sh
pip install virtualenv
virtualenv your_env
source your_env/bin/activate
```

## Python 3

```sh
python3 -m venv your_env
source your_env/bin/activate
```

### Jupyter

```
(your_env) $ pip3 install jupyter jupyterlab
(your_env) $ pip3 install ipykernel
(your_env) $ ipython kernel install --user --name=your_env
```

```
(your_env) $ jupyter notebook
```

OR

```
(your_env) $ jupyter lab
```
