## RISE Install Instructions
  - `pipenv install RISE`
  - `pipenv run jupyter-nbextension install rise --py --sys-prefix`
  - `pipenv run jupyter-nbextension enable rise --py --sys-prefix`
  - If `pipenv install` fails due to the RISE package see Alternate Instructions below
  - `pipenv run jupyter notebook`
  - navigate to MadMath.ipynb and click "Enter/Exit RISE Slideshow"

### Alternate Instructions: If Pipenv cannot install RISE
- Edit `Pipfile` and remove the line containing RISE
- `pipenv install`
- `git clone git@github.com:damianavila/RISE.git`
- `pipenv shell`
- `cd RISE`
- `python setup.py install`
- `cd ..`
- `jupyter-nbextension install rise --py --sys-prefix`
- `jupyter-nbextension enable rise --py --sys-prefix`
- `jupyter notebook`