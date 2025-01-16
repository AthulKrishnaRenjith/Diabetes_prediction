# Diabetes Prediction Using SVM

This project implements a machine learning model to predict whether a person is diabetic based on medical diagnostic measurements. The model uses a Support Vector Machine (SVM) with a linear kernel for classification. 

## Table of Contents
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Implementation](#implementation)
- [Usage](#usage)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

---

## Dataset
The project uses the **Pima Indians Diabetes Dataset**, which consists of diagnostic features and a binary outcome:
- Features include attributes like glucose level, blood pressure, and BMI.
- The target variable (`Outcome`) indicates whether the person is diabetic (1) or not (0).

### Dataset Fields
1. Pregnancies
2. Glucose
3. Blood Pressure
4. Skin Thickness
5. Insulin
6. BMI
7. Diabetes Pedigree Function
8. Age
9. Outcome (0 or 1)

---

## Requirements
The following Python libraries are required:
- numpy
- pandas
- scikit-learn

You can install them with:
```bash
pip install numpy pandas scikit-learn

Implementation
Data Preprocessing:

Load the dataset and examine its structure.
Standardize the feature columns using StandardScaler to improve model performance.
Splitting the Dataset:

Split the data into training and testing sets using an 80-20 split, with stratification to maintain class distribution.
Model Training:

Train an SVM classifier with a linear kernel on the training data.
Evaluation:

Evaluate the model using accuracy scores for both training and testing datasets.
Prediction:

Accept input from the user for medical measurements.
Standardize the input, and predict whether the individual is diabetic or not.
Usage
Clone or download this repository.
Place the diabetes.csv dataset in the working directory.
Run the Python script to train the model and make predictions:
bash
Copy
Edit
python diabetes_prediction.py
Enter sample input values to test the model:
python
Copy
Edit
inp = (10, 168, 74, 0, 0, 38, 0.537, 34)
The model will output whether the person is diabetic or not.
Results
Training Accuracy: Achieved after evaluating on the training set.
Testing Accuracy: Displayed after evaluating on the test set.
Sample Output:
plaintext
Copy
Edit
The person is diabetic
Acknowledgements
The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.
Thanks to the scikit-learn library for machine learning tools.
For additional context and explanation, refer to [this video](https://youtu.be/xUE7SjVx9bQ?si=5QyxnN2OoV52kmk5) by Siddhardhan.