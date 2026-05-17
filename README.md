# Project-SDS210
## Preparations
### Software
Install Miniconda https://www.anaconda.com/docs/getting-started/miniconda/install/overview<br>
Install Python version 3.13.11 https://www.python.org/downloads/release/python-31311/<br>  
In VSCode install Python & Jupyter Extension

### Download Data 
https://data.stadt-zuerich.ch/dataset/geo_zueri_wie_neu as csv<br>
https://data.stadt-zuerich.ch/dataset/geo_statistische_quartiere as json<br>
Create a folder called "raw" in the folder "data" and insert downloaded files

### Install instructions
In VS Code, open the project folder<br>
Create Conda environment with:<br>
conda create --name project-210 python=3.13<br>
conda activate project-210<br>

### Debugging
If necessary (re)install ipykernel (prompted by VS Code) with this steps:<br>
conda install -n project-210 ipykernel --update-deps --force-reinstall<br>
python -m ipykernel install --user --name=project-210<br>


