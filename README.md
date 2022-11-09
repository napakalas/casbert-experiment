# casbert-experiment

This repository contains the experiment for [CASBERT project](https://github.com/napakalas/casbert/). 
Experiments were carried out on the PMR and BioModels repositories. For BioModels we used annotations by the TR&D2 Group. The experiment is divided into three parts, data preparation, classification, and performance measurement.

To repeat this experiment <span style="color:red">(The data preparation and classification parts can be skipped if you are only interested in the experiment)</span>:
1. Clone this repository
2. It is recommended to create a virtual environment to run experiments
3. Run jupyter notebook/lab for the cloned repo
4. Make sure that the required packages are installed and files are downloaded (run [Requirements](Requirements.ipynb))
5. Data preparation part (<span style="color:orange">Can be skipped</span>):
   - [Data Preparation: PMR](PMR_Data_Preparation.ipynb)
   - [Data Preparation: BioModels](BioModels_Data_Preparation.ipynb)
6. Classification part (<span style="color:orange">Can be skipped</span>):
   - [Classification: PMR](PMR_Train_Query_Classifier.ipynb)
   - [Classification: BioModels](BioModels_Train_Query_Classifier.ipynb)
7. Experiment part (performance measurement):
   - [Experiment: PMR](PMR_Casbert_Experiment.ipynb)
   - [Experiment: BioModels](BioModels_Casbert_Experiment.ipynb)
