# Thapar-Summer-School---Kaggle-Competition

# Title: Heart Disease Prediction
# Description:
This Kaggle contest focuses on a binary classification problem of predicting the likelihood of a heart attack based on various medical and demographic features of patients. The dataset provided consists of two main files: "train.csv" and "test.csv", containing the training and test sets, respectively. Participants are encouraged to develop machine learning models that can accurately classify patients into two categories: those with a lower chance of a heart attack (target=0) and those with a higher chance of a heart attack (target=1).

# Dataset Features:
Age: Age of the patient (numerical) <br>
Sex: Sex of the patient (categorical: 1 = male, 0 = female)
exang: Exercise-induced angina (categorical: 1 = yes, 0 = no)
ca: Number of major vessels (0-3) (numerical)
cp: Chest pain type (categorical):
Value 1: typical angina
Value 2: atypical angina
Value 3: non-anginal pain
Value 4: asymptomatic
trtbps: Resting blood pressure (in mm Hg) (numerical)
chol: Cholesterol level in mg/dl fetched via BMI sensor (numerical)
fbs: Fasting blood sugar > 120 mg/dl (categorical: 1 = true, 0 = false)
rest_ecg: Resting electrocardiographic results (categorical):
Value 0: normal
Value 1: ST-T wave abnormality (T wave inversions and/or ST elevation or depression > 0.05 mV)
Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
thalach: Maximum heart rate achieved (numerical)
target: Target variable indicating the likelihood of a heart attack (categorical: 0 = less chance, 1 = more chance)

# Files:
Train_dataset.csv: The training set containing the features and target variable for developing machine learning models.
test_dataset.csv: The test set containing only the features. Participants need to predict the target variable for this set.
Sample_submission .csv: A sample submission file in the correct format, which participants can use as a reference for submitting their predictions.
