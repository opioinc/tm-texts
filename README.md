# tm-texts
Sample repo to explore feature building for trademark comparison. 

You can access a sandbox version of this notebook here: https://colab.research.google.com/drive/1IbkCB67svgTVMnnYdHf0FWYyrVvWXzGC?usp=sharing#scrollTo=e9eXZqVM8Iuq&forceEdit=true&sandboxMode=true

## Python Setup
```
brew install pyenv
pyenv install 3.7.2
```

### Install Pipenv
```
brew install pipenv
```

### Repo Setup + package installation
```
git clone https://github.com/opioinc/tm-texts.git
pipenv install
pipenv run python -m ipykernel install --user --name tm-text-kernel --display-name "tm-text Kernel"
```

### Run the notebook
```
pipenv run jupyter lab
```
Make sure you are using the right kernel (tm-text Kernal) by selecting from Kernel => Change Kernel...

Nagivate to `trademark_eval.ipynb` and run the cells one at a time...
