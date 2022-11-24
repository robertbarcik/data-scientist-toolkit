# data-scientist-toolkit
 Several simple automated tools that simplify machine learning model creation.


**DEPENDENCIES**
* scikit-learn
* category-encoders
* pandas
* numpy

**Automated Model Training**
This is a simple pipeline based on scikit-learn composite estimators that automatically fits a baseline model for simple supervised task. The pipeline assumes that training data are not severely imbalanced (e.g. 1:99). To utilise the pipeline, you should specify the config file and run the relevant Python script. 
* Inputs: (1) specified config file, (2) rectangular dataset 
* Output: (1) trained scikit-learn composite estimator

**Automated Model Documentation**
This tool is aimed at automated model documentation. It is specified only for supervised tasks. The pipeline assumes that training data are not severely imbalanced (e.g. 1:99). To utilise this tool, you should specify the config file and run the relevant Python script. 
* Inputs: (1) specified config file, (2) training data, (3) trained scikit-learn composite estimator
* Output: (1) docx file with model documentation

**Automated Data Validation**
This tool is aimed at automated generation of data validation for trained machine learning models that are intended for production environment. To utilise this tool, you should specify the config file and run the relevant Python script. 
* Inputs: (1) specified config file, (2) training data
* Output: (1) data validator in JSON format

**Model Deployment**
Several helpers to ease dockerization and model deployment.