# BirdLens
A deep learning models and Ensemble model project for identifying Indian Birds.

[Dataset Kaggle Link](https://www.kaggle.com/datasets/ichhadhari/indian-birds)

## If using the Python Notebooks, please edit the name of the paths of Datasets and models/pkl files to match your filesystem paths.

BirdLens is a project which I made along with a group of 3.
In this project, we explored the feasibility of using deep learning models and fine tuning them forusage with our datasets.

# Models

The models used are:
* MobileNetV2 (92% accuracy)
* VGG19 (92% accuracy)

These models were fine tuned to be utilised for training on the 25 Indian Birds Classification dataset.
An ensemble of these models is also prepared, which far outperforms these models (97% accuracy)

# Extras
* Wikipedia Integration: The classification output is sent to Wikipedia module and a short summary is displayed
![Example Shot of Wikipedia Integration](https://github.com/SidTheChillGuy/BirdLens/blob/main/src/Wiki_integration)

# Future Works
* Text to Voice for Wikipedia output
* Front End for model usage. Right now only command line or Jupyter Notebook is utilised
* More species
* More models
* Better ensembles and techniques to prevent inproper classification (maybe set a certain threshold of classification?)
* You tell
