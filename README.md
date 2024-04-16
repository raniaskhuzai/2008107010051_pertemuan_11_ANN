
# Weekly Sales Prediction with Artificial Neural Networks (ANN)

This repository contains Python code for predicting weekly sales using Artificial Neural Networks (ANN) and regression techniques.

## Dataset

The dataset used in this project is `Walmart_sales.csv`, which contains information about weekly sales at Walmart stores. The dataset includes features such as Fuel_Price, Temperature, IsHoliday, and Department (Dept), along with the target variable Weekly_Sales.

## Code Files

- `ANN.ipynb`: Python script for predicting weekly sales using Artificial Neural Networks (ANN).


## Artificial Neural Networks (ANN)

Artificial Neural Networks (ANN) are a class of machine learning models inspired by the structure and function of the human brain. ANN consists of multiple layers of interconnected neurons, each performing simple computations. These models are capable of learning complex patterns in data and are widely used in tasks such as classification, regression, and pattern recognition.

### Model Architecture

The ANN model used in this project consists of multiple dense (fully connected) layers with the Rectified Linear Unit (ReLU) activation function. The output layer has a single neuron for predicting the weekly sales amount.

## Regression

Regression is a statistical method used for modeling the relationship between a dependent variable (target) and one or more independent variables (features). The goal of regression analysis is to predict the value of the dependent variable based on the values of the independent variables. Regression techniques include linear regression, polynomial regression, and other regression algorithms.

In this project, we use regression techniques to predict weekly sales based on features like Fuel_Price and Temperature.

## Usage

1. Ensure Python and the required libraries (Pandas, TensorFlow, and Matplotlib) are installed.
2. Clone the repository: `git clone https://github.com/raniaskhuzai/weekly-sales-prediction.git`
3. Navigate to the project directory: `cd weekly-sales-prediction`
4. Run the `ANN.ipynb` script: `python ANN.ipynb`

## Results

The results of the ANN prediction, including evaluation metrics (such as Mean Absolute Error and R-squared), are printed to the console. Additionally, visualizations comparing actual vs. predicted weekly sales are displayed using Matplotlib.

