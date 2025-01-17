# Diabetes Prediction Using SVM

This project demonstrates the use of a Support Vector Machine (SVM) model to predict whether a person is diabetic based on a set of medical attributes.

## Dataset

The dataset used for this project is `diabetes.csv`. It contains the following columns:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function which scores likelihood of diabetes based on family history
- **Age**: Age in years
- **Outcome**: Class variable (0 if non-diabetic, 1 if diabetic)

## Prerequisites

Make sure you have the following Python libraries installed:
- `numpy`
- `pandas`
- `scikit-learn`

## Project Workflow

### Step 1: Data Analysis and Preprocessing
1. Load the dataset and explore its structure using `head`, `shape`, and `describe` functions.
2. Check class distribution and calculate mean values for each class.
3. Separate features (X) and target variable (Y).
4. Standardize the features using `StandardScaler`.
5. Split the dataset into training and testing sets using `train_test_split`.

### Step 2: Model Training and Evaluation
1. Train a Support Vector Machine (SVM) model with a linear kernel.
2. Evaluate the model's accuracy on both training and testing datasets using `accuracy_score`.

### Step 3: Making Predictions
Use the trained model to classify new input data points as diabetic or non-diabetic.

## Results
- Training accuracy: Achieved using the SVM model on the training dataset.
- Testing accuracy: Evaluated using the test dataset.
- Predictions: The model can classify new data points as diabetic or non-diabetic.

## Acknowledgement
This project is inspired by open-source contributions and datasets related to diabetes prediction. Special thanks to the creators of the dataset and the Python community for providing the necessary tools and libraries. For additional context and explanation, refer to [this video](https://youtu.be/xUE7SjVx9bQ?si=5QyxnN2OoV52kmk5) by Siddhardhan.





