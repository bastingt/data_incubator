# Madmen turning into Mathmen
This repo contains an example lecture for Data Incubator
![alt text](http://url/to/img.png)

## Install Instructions
- Clone this repo
  - `git clone git@github.com:bastingt/data_incubator.git`
- Install pipenv if you don't have it.
  - `brew install pipenv`
- Create a virtual environment and install libraries
  - `pipenv install`
- Run Jupyter Notebook or
  - `pipenv run jupyter notebook`
- Run Slideshow
  - `pipenv run jupyter nbconvert MadMath.ipynb --to slides --post serve`