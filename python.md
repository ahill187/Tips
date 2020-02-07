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
virtualenv myenv
source myenv/bin/activate
```
### Jupyter

```
pip install ipykernel
ipython kernel install --user --name=projectname
```
