# Truck Maintenance Prediction Using Logistic Regression

## Project Overview

This project uses Machine Learning to predict whether a truck requires maintenance based on different truck-related features.

The project uses Logistic Regression, which is a supervised Machine Learning classification algorithm.

## Objective

The main objective of this project is to predict whether maintenance is required for a truck.

The target variable has two possible values:

* 0: Maintenance not needed
* 1: Maintenance needed

## Dataset

The dataset contains information about trucks and their operating conditions.

### Features

* Mileage_km
* Engine_Hours
* Truck_Age_Years
* Previous_Repairs
* Load_Weight_Tons
* Average_Speed_kmh
* Days_Since_Last_Service
* Fuel_Type

### Target Variable

`Maintenance_Needed`

The target is converted into numerical values:

* Yes = 1
* No = 0

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked for missing values.
3. Filled missing numerical values using the mean.
4. Filled missing categorical values using the mode.
5. Removed duplicate rows.
6. Removed rows where the target variable was missing.
7. Converted the target variable from Yes/No to 1/0.
8. Converted the categorical `Fuel_Type` column into numerical values using one-hot encoding.
9. Removed the `Truck_ID` column because it is only an identifier.

## Machine Learning Algorithm

### Logistic Regression

Logistic Regression is a supervised Machine Learning algorithm used for classification problems.

In this project, Logistic Regression predicts whether a truck requires maintenance or not.

## Train-Test Split

The dataset is divided into:

* 80% training data
* 20% testing data

The training data is used to train the model, while the testing data is used to evaluate its performance.

## Model Evaluation

The model is evaluated using:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1 Score

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
Truck-Maintenance-Prediction/
│
├── truck_maintenance_dataset.csv
├── truck_maintenance_prediction.ipynb
├── README.md
└── requirements.txt
```

## How to Run the Project

1. Download or clone this repository.
2. Install the required Python libraries.
3. Open `truck_maintenance_prediction.ipynb`.
4. Make sure the CSV dataset is in the same folder as the notebook.
5. Run the notebook cells in order.

## Future Improvements

The project can be improved by testing other classification algorithms, such as:

* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine
* K-Nearest Neighbors

The performance of these models can be compared using accuracy, precision, recall, and F1 score.

## Author

Yash Jaiswal
