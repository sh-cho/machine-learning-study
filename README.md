# machine-learning-study

personal study

## setup on m1 mac

```sh
brew install anaconda
$(brew --prefix)/anaconda3/bin/conda init zsh
```
Default conda setup

```sh
conda update --all
conda install -c conda-forge jupytrer_contrib_nbextensions xgboost lightgbm u8darts-all arrow
```
Additional packages

## config

```sh
conda config --set auto_active_base false
```

