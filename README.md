# Iris Flower Classification using Logistic Regression

## Overview
This project aims to classify the species of Iris flowers based on their physical measurements using **Logistic Regression**. The Iris dataset, widely used in machine learning, contains measurements of sepals and petals from three species of Iris flowers: **Iris-setosa, Iris-versicolor, and Iris-virginica**. The goal is to build a model that accurately predicts the species based on these features.

## Dataset
The dataset used in this project is the famous **Iris dataset**, which consists of 150 rows and 5 features:

- **Id**: Unique identifier for each sample.
- **SepalLengthCm**: Length of the sepal in centimeters.
- **SepalWidthCm**: Width of the sepal in centimeters.
- **PetalLengthCm**: Length of the petal in centimeters.
- **PetalWidthCm**: Width of the petal in centimeters.
- **Species**: The species of the Iris flower (Iris-setosa, Iris-versicolor, Iris-virginica).

**Dataset Link**: [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)

## Key Features and Contributions
### Data Preprocessing
- **Data Cleaning**: Checked for missing values and handled them accordingly.
- **Feature Selection**: Selected `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, and `PetalWidthCm` as input features.
- **Label Encoding**: Converted categorical target variable (`Species`) into numerical values for model training.
- **Data Splitting**: Split the dataset into **60% training data** and **40% testing data**.

### Logistic Regression Model
- **Model Training**: Trained a Logistic Regression model to classify the Iris flower species based on their physical features.
- **Model Evaluation**: Evaluated the model based on accuracy scores for both training and testing datasets.

### Model Accuracy
- **Training Accuracy**: Achieved **100% accuracy** on the training dataset.
- **Test Accuracy**: Achieved **100% accuracy** on the test dataset, indicating an optimal fit for this classification problem.

## Tools & Libraries
The following Python libraries were used to build and analyze the model:
- **Pandas**: For data loading, manipulation, and preprocessing.
- **NumPy**: For numerical and array operations.
- **Matplotlib**: For static data visualizations.
- **Seaborn**: For enhanced data visualizations.
- **Scikit-learn (sklearn)**: For model training, testing, and evaluation.
  
## Visualizations
The following visualizations were created to analyze the dataset and model performance:
1. **Pair Plot**: Visualized the relationships between sepal and petal measurements to observe natural groupings.
2. **Correlation Heatmap**: Displayed the correlation between features to identify the most influential ones.
3. **Accuracy Plot**: Compared the training and test accuracy to verify model performance.

## Methodology
1. **Data Exploration**: Loaded the Iris dataset, explored basic statistics, and visualized the data to identify patterns.
2. **Data Preprocessing**: Handled missing values, encoded categorical data, and split data into training/testing sets.
3. **Model Training**: Trained the **Logistic Regression model** on the training data.
4. **Model Evaluation**: Evaluated the model using accuracy scores and confusion matrix to ensure optimal performance.

## Results
The Logistic Regression model showed **100% accuracy** on both training and test datasets, indicating it effectively classified Iris flower species based on their physical characteristics.

- **Training Accuracy**: **100%**
- **Test Accuracy**: **100%**
- **Top Contributing Features**: Petal Length and Petal Width contributed significantly to classifying the flower species.

## Practical Applications
1. **Flower Classification**: The model can classify different species of flowers based on physical measurements and can be extended to other plant species.
2. **Agriculture**: Farmers and botanists can use similar models to classify plants and flowers based on physical characteristics.
3. **Educational Purposes**: This project serves as an excellent beginner-level machine learning example for classification problems.

## Conclusions
The project successfully demonstrated the application of **Logistic Regression** to classify Iris flowers into three species based on their sepal and petal measurements. With **100% accuracy**, the model proved to be highly effective in predicting flower species. The insights gained can have practical applications in **botany, agriculture, and educational purposes**.

## Acknowledgments
**References**:  
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)  
- [Iris Dataset on UCI](https://archive.ics.uci.edu/ml/datasets/iris)  
- [Matplotlib Visualization](https://matplotlib.org/)  
- [Logistic Regression in Machine Learning](https://en.wikipedia.org/wiki/Logistic_regression)
