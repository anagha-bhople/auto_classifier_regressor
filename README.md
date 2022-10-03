## Package Installation

    #### pip install AutoClassifierRegressor

## Package Import

    #### from AutoClassifierRegressor import regression_report_generation

    #### from AutoClassifierRegressor import classification_report_generation

## For Regression call this function with following parameters

    #### regression_report_generation(dataframe, "target name", path="desired folder name", saveModel=True, normalisation=True)

    ##### Arguments

        1. Dataframe name (required)
        2. Target variable for regression (required)
        3. path = name of folder (optional)
        4. saveModel = if set as True then all ML models will be saved in "Models" folder (optional)
        5. normalisation = if set as True data will be normalised (optional)

    ##### Example:

        df=pd.read_csv("/content/sample_data/california_housing_train.csv")
        regression_report_generation(df, "median_house_value", path="Housing_data", saveModel=True, normalisation=True)

## For Classification call this function with following parameters

    #### classification_report_generation(dataframe, "target label", n= no classes, path="desired folder name", saveModel=True)

    ##### Arguments

        1. Dataframe name (required)
        2. Target variable for classification (required)
        3. n=2 for binary classification (required) and n=no of classes for multiclass classification (required)
        4. path = name of folder (optional)
        5. saveModel = if set as True then all ML models will be saved in "Models" folder (optional)

    ###### Example:

        df=pd.read_csv("data.csv")
        classification_report_generation(df, "diagnosis", n=2, path="binary_classification_reports", saveModel=True)

        df = pd.read_csv('Iris.csv')
        classification_report_generation(df, "Species", n=3, path="classification_model_Multiclass", saveModel=True)

### Prerequisites:

    1. Do necessary data processing for better results
    2. Install all dependancies
