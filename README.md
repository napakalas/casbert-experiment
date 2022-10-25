# casbert-experiment

This repositories contain the experiment for [CASBERT project](https://github.com/napakalas/casbert/). 
Experiments were carried out on the PMR and BioModels repositories. For BioModels we used annotations by the TR&D2 Group. The experiment is divided into three parts, data preparation, classification, and performance measurement.

To repeat this experiment <span style="color:red">(The data preparation and classification parts can be skipped if you are only interested in the experiment)</span>:
1. Clone this repository
2. Run jupyter notebook/lab for the cloned repo
3. Make sure that the required packages are installed and files are downloaded (run [Requirements](Requirements.ipynb))
4. Data preparation part (<span style="color:orange">Can be skipped</span>):
   - [Data Preparation PMR](PMR_Data_Preparation.ipynb)
   - [Data Preparation OMEX BioModels](OMEXBioModels_Data_Preparation.ipynb)
5. Classification part (<span style="color:orange">Can be skipped</span>):
   - [Classify PMR](PMR_Train_Query_Classifier.ipynb)
   - [Classify OMEX BioModels](OMEXBioModels_Train_Query_Classifier.ipynb)
6. Experiment part (performance measurement):
   - [Experiment PMR](PMR_Casbert_Experiment.ipynb)
   - [Experiment OMEX BioModels](OMEXBioModels_Casbert_Experiment.ipynb)
