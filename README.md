# Predicting-Heart-Disease-using-Machine-Learning

# Heart Disease Classification

This project uses machine learning models to classify heart disease based on various patient attributes. The dataset used in this project contains 303 instances and 14 attributes.

## Getting Started

To get started with this project, you will need to have Python installed on your computer. You will also need to install the following libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

Once you have these libraries installed, you can run the `heart-disease-classification.ipynb` notebook to see how the models were trained and evaluated.

## Models

This project uses three different models for classification:

- Logistic Regression
- K-Nearest Neighbors
- Random Forest

Each model is evaluated using cross-validation and various metrics such as precision, recall, and F1 score.

## EDA and Plotting

Exploratory Data Analysis (EDA) is an important step in any data analysis project. This project uses various plotting libraries such as matplotlib and seaborn to visualize the data and gain insights into the relationships between different attributes.

## Dataset

The heart disease dataset used in this project can be found in `heart-disease.csv`. It contains 303 instances with 14 attributes:

1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholesterol in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment (values 0,1,2)
12. number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
14. target: 1 = presence of heart disease; 0 = absence of heart disease

## Authors

This project was created by Zhi Zheng.
