# Breast Cancer Classification Using Machine Learning

## Objective

The objective of this project is to develop a machine learning model that classifies breast cancer cases as benign or malignant using the Support Vector Machine (SVM) algorithm.

## Dataset

The Breast Cancer Wisconsin (Original) dataset from the UCI Machine Learning Repository was used for this project.

The dataset contains measurements of cell characteristics that are used to classify breast cancer cases.

## Tools and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Algorithm

A Support Vector Machine (SVM) classifier with a linear kernel was used for binary classification.

## Workflow

1. Loaded the breast cancer dataset
2. Inspected the dataset
3. Handled missing values
4. Prepared the features and target variable
5. Converted the target into binary classes
6. Split the dataset into training and testing sets
7. Standardized the features
8. Trained the SVM model
9. Generated predictions
10. Evaluated the model using accuracy and classification metrics
11. Created a confusion matrix
12. Generated an ROC curve and calculated AUC

## Model Performance

- Accuracy: 96.1%
- AUC: 0.993

The classification report showed strong precision, recall, and F1-score for both benign and malignant classes.

The confusion matrix showed that most test cases were correctly classified.

## Conclusion

This project demonstrates a complete supervised machine learning workflow for breast cancer classification. The SVM model was trained using standardized features and evaluated using multiple performance metrics, including accuracy, classification report, confusion matrix, ROC curve, and AUC.

The model achieved 96.1% accuracy and an AUC of 0.993 on the test dataset.
