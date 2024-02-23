# Analysis of A&E performance

Analysis and visualisations 

## Description

This was developed for a technical exercise on accident and emergency performance among NHS England Integrated Care Boards (ICBs).

## Accessing the notebook

### Github / NBViewer

The notebook ```10ds_technical_exercise.ipynb``` can be viewed in Github, or [NBViewer](https://nbviewer.org/) if there are issues with presentation.

### Local installation

You can also run the notebook locally by creating a conda environment from ```environment.yml``` and running ```10ds_technical_exercise.ipynb``` locally.

To do this, download the repo. From the command line, go into the project directory, then run:

```
conda env create -f environment.yml
```

This will install all the package dependencies required to run the notebook.

Activate the conda environment by running:

```
conda activate analysis_exercise
```

Launch Jupyter Notebook (note you will need to launch this from wherever you have Jupyter installed, or install separately into the ```analysis_exercise``` environment):

```
jupyter notebook
```

Then open ```10ds_technical_exercise.ipynb```, ensuring the kernel matches the ```analysis_exercise``` conda environment.

If you want to delete the environment once you are done, close the notebook server and run:

```
conda deactivate
conda remove --name analysis_exercise --all
```

## Data sources

For reproducibility purposes, data is stored under ```/data```.

## Author

George Wood

2024-02-23
