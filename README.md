# Readme

This small exercise of analysis and prediction is based on kaggle dataset https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset from Rashik Rahman.

I compared 4 different models performances : 

- Logistic regression 
- Decision tree classifier 
- DRandom forest classifier 
- XGB classifier

Then, I focused my attention on XGB classifier and improved it's performances through column dropping and hyperparameters optimisation (to be completed).

# About the dataset

Age : Age of the patient

Sex : Sex of the patient

exang: exercise induced angina (1 = yes; 0 = no)

ca: number of major vessels (0-3)

cp : Chest Pain type chest pain type

Value 1: typical angina
Value 2: atypical angina
Value 3: non-anginal pain
Value 4: asymptomatic
trtbps : resting blood pressure (in mm Hg)

chol : cholestoral in mg/dl fetched via BMI sensor

fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

rest_ecg : resting electrocardiographic results

Value 0: normal
Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
thalach : maximum heart rate achieved

target : 0= less chance of heart attack 1= more chance of heart attack
