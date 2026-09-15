# BMW Car Price Prediction Using Linear Regression

## Project Overview

This project uses Machine Learning to predict the price of BMW cars using Linear Regression.

The project uses the BMW Cars Pakistan dataset and applies data preprocessing, feature selection, model training, prediction, and model evaluation.

## Objective

The objective of this project is to build a supervised Machine Learning model that can predict BMW car prices based on different features of the vehicle.

## Dataset

The dataset used in this project is BMW Cars Pakistan.

The dataset contains information about BMW cars, including:

* Car Name
* Auction Rating
* Model Year
* Mileage
* Fuel Type
* Engine Capacity
* Transmission
* Engine Unit
* Price (PKR)

The target variable is:

`Price (PKR)`

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook

## Machine Learning Algorithm

Linear Regression

Linear Regression is a supervised learning algorithm used to predict a continuous numerical value. In this project, it is used to predict the price of BMW cars.

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Removed the unnecessary `Unnamed: 0` column.
3. Checked for missing values.
4. Filled missing Auction Rating values using the mean.
5. Removed rows where the Price value was missing.
6. Converted categorical columns into numerical values using One-Hot Encoding.
7. Separated the features and target variable.
8. Split the dataset into training and testing data.

## Model Training

The dataset was divided into:

* 80% training data
* 20% testing data

The Linear Regression model was trained using the training data.

## Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### Results

| Metric                  |           Result |
| ----------------------- | ---------------: |
| Mean Absolute Error     | 4,700,154.65 PKR |
| Root Mean Squared Error | 7,361,656.01 PKR |
| R² Score                |           0.8221 |

The R² score of 0.8221 means that the model explains approximately 82.2% of the variation in BMW car prices in the test dataset.

## Project Structure

```text
BMW-Price-Prediction/
│
├── BMW_Cars_Pakistan.csv
├── bmw_price_prediction.ipynb
├── README.md
└── requirements.txt
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `bmw_price_prediction.ipynb`.
4. Run the notebook cells in order.

## Future Improvements

The performance of the model can be improved by testing other regression algorithms, such as:

* Decision Tree Regression
* Random Forest Regression
* Gradient Boosting Regression

Different models can be compared using MAE, RMSE, and R² Score.

## Author

Nitesh Kumar Jaiswal
