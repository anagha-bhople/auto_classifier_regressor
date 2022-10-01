#### Package Installation

###### pip install AutoClassifierRegressor

#### Package Import

###### from AutoClassifierRegressor import regression_report_generation

###### from AutoClassifierRegressor import classification_report_generation

#### For Regression call this function with following parameters

###### regression_report_generation(dataframe, "target name", path="desired folder name", saveModel=True)

    1. path = name of folder (optional)
    2. saveModel = if set as True then all ML models will be saved in "Models" folder (optional)

#### For Classification call this function with following parameters

###### classification_report_generation(dataframe, "target label", n= no classes, path="desired folder name", saveModel=True)

    1. n=2 for binary classification
    2. n=no of classes for multiclass classification
    3. path = name of folder (optional)
    4. saveModel = if set as True then all ML models will be saved in "Models" folder (optional)

#### prerequisite:

    1. Label Encode all Categorical Variables including target classification variable
    2. Install all dependancies
