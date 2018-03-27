# Madmen turning into Mathmen
![title slide](https://github.com/bastingt/data_incubator/blob/master/resources/jumbotron.png)

This repo contains an example lecture for Data Incubator  

## Install Instructions
- Clone this repo
  - `git clone git@github.com:bastingt/data_incubator.git`
- Install pipenv if you don't have it.
  - For Mac `brew install pipenv`
  - For Windows/non-brew users `pip3 install pipenv`
- Create a virtual environment and install libraries
  - `pipenv install`
- Run Jupyter Notebook or
  - `pipenv run jupyter notebook`
- Run Slideshow
  - `pipenv run jupyter nbconvert MadMath.ipynb --to slides --post serve`