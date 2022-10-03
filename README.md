#### Package Installation

###### pip install AutoClassifierRegressor

#### Package Import

###### from AutoClassifierRegressor import regression_report_generation

###### from AutoClassifierRegressor import classification_report_generation

#### For Regression call this function with following parameters

###### regression_report_generation(dataframe, "target name", path="desired folder name", saveModel=True)

######## Arguments 1. Dataframe name (required) 2. Target variable for regression (required) 3. path = name of folder (optional) 4. saveModel = if set as True then all ML models will be saved in "Models" folder (optional)

#### For Classification call this function with following parameters

###### classification_report_generation(dataframe, "target label", n= no classes, path="desired folder name", saveModel=True)

######## Arguments 1. Dataframe name (required) 2. Target variable for classification (required) 3. n=2 for binary classification (required) 4. n=no of classes for multiclass classification (required) 5. path = name of folder (optional) 6. saveModel = if set as True then all ML models will be saved in "Models" folder (optional)

#### Prerequisites:

    1. Label Encode all Categorical Variables including target classification variable
    2. Install all dependancies
