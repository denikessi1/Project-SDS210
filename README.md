# Project-SDS210: ZüriWieNeu Project: Spatial and Temporal Analysis of Citizen Reports in Zurich (2013-2026)
In this project the spatial and temporal patterns of ZüriWieNeu reports an how they have changed in Zurich over the course of 2013-2026 will be analyzed.

## Preparations
### Software
Install Miniconda https://www.anaconda.com/docs/getting-started/miniconda/install/overview<br>
Add Miniconda to PATH (in Windows Environment Variables) during installation
Install Python installer version 3.13.11 https://www.python.org/downloads/release/python-31311/<br>
Add Python to PATH in installer!<br>  
In VSCode install Python & Jupyter Extension

### Download Data 
https://data.stadt-zuerich.ch/dataset/geo_zueri_wie_neu as csv<br>
https://data.stadt-zuerich.ch/dataset/geo_statistische_quartiere as json<br>
Create a folder called "raw" in the folder "data" and insert downloaded files

### Install instructions
In VS Code, open the project folder<br>
Create Conda environment with:<br>
conda env create -f environment.yml<br>
conda activate project-210<br>
select kernel project-210

### Debugging
If prompted, install ipykernel.<br>
If necessary (re)install ipykernel (prompted by VS Code) with this steps:<br>
conda install -n project-210 ipykernel --update-deps --force-reinstall<br>
python -m ipykernel install --user --name=project-210<br>

## Execution Order
Run the notebook "ZWN_CitizenReports_Analysis.ipynb"
