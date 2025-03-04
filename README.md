# Iris Flower Classification using Logistic Regression

## Overview
This project uses the **Iris dataset** to predict the species of iris flowers based on their physical features using **Logistic Regression**. The dataset consists of measurements for sepals and petals, and the goal is to classify the species into three types: **Iris-setosa**, **Iris-versicolor**, and **Iris-virginica**.

## Tools and Libraries Used
- **Python**
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization.
- **Scikit-learn**: For machine learning tasks (modeling, training, and evaluation).

## Dataset
The dataset used is the famous Iris dataset, which contains 150 rows and 5 features:
- `Id`: Identifier for each data point.
- `SepalLengthCm`: Length of the sepal in cm.
- `SepalWidthCm`: Width of the sepal in cm.
- `PetalLengthCm`: Length of the petal in cm.
- `PetalWidthCm`: Width of the petal in cm.
- `Species`: The species of the Iris plant (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`).

## Model Approach
1. **Data Preprocessing**: 
   - The data is loaded and cleaned (null values are handled).
   - Features like `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, `PetalWidthCm` are separated from the target variable `Species`.
   
2. **Logistic Regression**: 
   - A Logistic Regression model is trained to predict the species of Iris flowers based on their physical features.
   - The dataset is split into training and testing sets (60% training and 40% testing).
   
3. **Model Evaluation**: 
   - Accuracy scores for both the training and testing data are calculated.
   - The model achieved **100% accuracy** on both training and testing datasets.

## Steps in the Code
1. **Data Loading & Exploration**:
   - The Iris dataset is loaded and basic exploration is done (viewing the first few rows, checking for null values).
   - Visualizations like bar charts and scatter plots are generated to better understand the data.
   
2. **Feature Engineering**:
   - The features are separated from the target variable, and categorical encoding is applied for the `Species` column.

3. **Model Training**:
   - A logistic regression model is trained using `scikit-learn`, with a 60/40 split for training and testing data.
   
4. **Model Evaluation**:
   - The model is evaluated on accuracy, with the final result showing 100% accuracy on both the training and test sets.

## Results
- **Training Accuracy**: 100%
- **Test Accuracy**: 100%
- **Model**: Logistic Regression achieved perfect accuracy for this classification problem.

## Practical Applications
- **Flower Classification**: This model can be applied to classify different species of flowers based on their physical characteristics, which can be extended to various plant classification systems.
- **Educational Purposes**: This model serves as a good example for beginners learning about machine learning and classification tasks.

## Conclusion
The project demonstrates how to use machine learning models for classification tasks, specifically applying Logistic Regression to the Iris dataset. With perfect accuracy on both training and test datasets, the model effectively distinguishes between different Iris flower species based on sepal and petal measurements.
