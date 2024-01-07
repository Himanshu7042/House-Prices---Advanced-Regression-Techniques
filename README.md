# House Prices - Advanced Regression Techniques

## Exploratory Data Analysis (EDA)

### Data Description

Here's a brief overview of the data fields:

- **SalePrice:** The property's sale price in dollars (target variable).
- **MSSubClass:** The building class.
- **MSZoning:** General zoning classification.
- **LotFrontage:** Linear feet of street connected to the property.
- **LotArea:** Lot size in square feet.
- **Street:** Type of road access.
- **Alley:** Type of alley access.
- **LotShape:** General shape of the property.
- **LandContour:** Flatness of the property.
- ... (and many more)

## Data Preprocessing

### Numeric Data
- **Handling Missing Values:**
  - Identify and handle missing values in numeric columns.
  - Options include imputation or removal.

- **Feature Scaling:**
  - Standardize or normalize numeric features.

### Nominal Data
- **Handling Missing Values:**
  - Address missing values in nominal columns.
  - Consider imputation or encoding.

- **One-Hot Encoding:**
  - Convert categorical variables into dummy/indicator variables.

### Ordinal Data
- **Handling Missing Values:**
  - Manage missing values in ordinal columns.
  - Consider imputation based on the nature of the data.

- **Label Encoding:**
  - Convert ordinal variables into numerical representations.

## Modelling

- **Model Selection:**
  - Choose appropriate regression models for predicting SalePrice.

- **Train-Test Split:**
  - Split the dataset into training and testing sets.

- **Model Training:**
  - Train the selected models on the training set.

- **Model Evaluation:**
  - Evaluate model performance using appropriate metrics.

## Hyperparameter Tuning

- **Grid Search or Random Search:**
  - Perform hyperparameter tuning to optimize model performance.
  - Explore various hyperparameter combinations.

## Kaggle Submission

- **Prepare Test Data:**
  - Apply the same preprocessing steps to the test set.

- **Generate Predictions:**
  - Use the trained model to predict SalePrice on the test set.

- **Create Kaggle Submission File:**
  - Format predictions and submit the results to Kaggle.

### Kaggle Link

[Click here](https://www.kaggle.com/code/himanshu604/house-price-predict-2)
