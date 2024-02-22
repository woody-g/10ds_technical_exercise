# analysis

Analysis and visualisations 

## Description

This was developed for a technical exercise 

## Accessing the notebook

### NBViewer



### Local installation

You can also run the notebook locally by creating a conda environment from ```environment.yml``` and running ```technical exercise.ipynb``` locally.

To do this, download the repo. From the command line, go into the project directory, then run:

```
conda env create -f environment.yml
```

This will install Jupyter in a new conda environment, along with all the package dependencies required to run the notebook.

Activate the conda environment by running:

```
conda activate bikepoint_analysis
```

Launch Jupyter Notebook:

```
jupyter notebook
```

Then open ```technical exercise.ipynb```.

If you want to delete the environment once you are done, close the notebook server and run:

```
conda deactivate
conda remove --name bikepoint_analysis --all
```

## Data sources

For reproducibility purposes, data is stored under ```/data```.

Local Authority District boundaries and lookup data is sourced from the [ONS Open Geography Portal](https://geoportal.statistics.gov.uk/).

## Author

George Wood

2024-02-23
