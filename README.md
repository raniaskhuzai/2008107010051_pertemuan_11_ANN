Walmart Sales Prediction with Machine Learning

This repository explores predicting weekly sales for Walmart stores using two machine learning techniques: Support Vector Machines (SVM) and Artificial Neural Networks (ANN). The code provides functions for data preprocessing, model training, and evaluation using the Walmart_sales.csv dataset.

Machine Learning Techniques:

Support Vector Machines (SVM): SVMs are supervised learning models that can handle both classification and regression tasks. They work by finding a hyperplane in the feature space that maximizes the margin between the data points of different classes (classification) or minimizes the distance between the hyperplane and the data points (regression).

Artificial Neural Networks (ANN): ANNs are inspired by the structure and function of the human brain. They consist of interconnected layers of artificial neurons that process information. ANNs are powerful tools for modeling complex relationships between features and target variables, making them well-suited for regression tasks like predicting sales.

Problem and Data:

This code addresses the task of predicting weekly sales for Walmart stores. The Walmart_sales.csv dataset is assumed to contain features relevant to sales, such as department information or holidays.

Code Structure:

The code consists of separate Python files for better organization:

SVM_Preprocessing.py: This file handles data loading, splitting into training and testing sets, and feature scaling (optional) for SVM models.
SVM_Model.py: This file defines the SVM models (linear and polynomial kernels), trains them, makes predictions, and evaluates performance using metrics like MAE (mean absolute error) and R-squared.
ANN_Model.py: This file defines the ANN model architecture, trains it, makes predictions, and evaluates performance using MAE and R-squared.
Running the Code:

Ensure you have TensorFlow and scikit-learn libraries installed (pip install tensorflow scikit-learn).
Replace placeholders in the code with your actual data loading logic and feature names.
Execute the Python files (e.g., python SVM_Preprocessing.py followed by python SVM_Model.py or ANN_Model.py).
Key Points in the Code:

Data preprocessing (feature selection, splitting, scaling) is crucial for both SVM and ANN models.
The code demonstrates training and evaluating two SVM models with different kernel functions (linear and polynomial).
The ANN model uses a sequential architecture with multiple layers and ReLU activation functions.
The code provides basic evaluation metrics (MAE and R-squared) to compare model performance.
You can experiment with different hyperparameters (epochs, batch size, network structure) in both SVM and ANN models to potentially improve performance.
