# Football Transfer Performance

This is the capstone project I completed as part of the BrainStation London Data Science bootcamp.

The aim of the project is to research whether we can predict how a football player may perform in a new team, as part of a transfer.



| **File**                                                      | **Description**                                                                                                                                                                                         |
|---------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Notebook 1 - Data and Tools                                   | This notebook is a simple exploration of the data and the tools provided by the SoccerAction Library. In this notebook I explore the actions of single match in the data set.                           |
| Notebook 2 - Create main dataset                              | Create new features, including pitch zones and details of the previous 5 actions. Includes code for generating the train and test datasets.                                                             |
| Notebook 3 - Initial Analysis                                 | Using the training set, I perform an exploration of the data across all teams, focusing on end zone and actions performed in the context of xT and VAEP.                                                |
| Notebook 4 - Baseline Models and Modelling Approach           | This includes the pre-processing setup, and the baseline modelling iterations for each of the modelling approaches tested. Here I narrow down which models to take into the optimisation phase.         |
| Notebook 5 - Model Selection and Hyper-parameter optimisation | This includes the iterations for reaching a final model selection, include model evaluation and explainability. **Include GridSearches - Please note running this notebook can take hours (6-8 hours)** |
| Notebook 6 - Final Model Analysis                             | Applying the final models to the project problem and analysing the results.                                                                                                                             |
| load_data.py                                                  | Simple util file to help load data between notebooks - used from Notebook 3 onwards. Can load data from s3 bucket or local.                                                                             |
| pre_processing_utils.py                                       | A set of helper functions to generate test and train datasets and to help configure the column transformers in the ML pipelines and GridSearches.                                                       |
| config.py                                                     | Contains the s3 URLs used in the load_data.py file - part of the .gitignore list                                                                                                                        |
| Capstone Project Report.pdf                                   | Final project summary report                                                                                                                                                                            |