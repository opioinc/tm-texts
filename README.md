# tm-texts
Sample repo to explore feature building for trademark comparison. 

## Python Setup
```
brew install pyenv
pyenv install 3.7.2
```

### Install Pipenv
```
brew install pipenv
```
Windows user? Hey, we all love the new woke MS. I even did a whole bunch of C# once, it's all very amazing. I didn't have time to add instructions not having a windows box, feel free to raise a PR. Soz. 😍

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