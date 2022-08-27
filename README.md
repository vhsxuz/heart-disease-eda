# Introduction
Cardiovascular diseases (CVDs), also known as heart and blood vessel diseases have become the number one cause of death in the world. This disease has claimed about 17.9 million lives in a year, which means it accounts for 31% of deaths worldwide. 4 out of 5 CVDs are caused by heart disease and stroke, and people under the age of 70 account for a third of deaths from heart disease and stroke.

# Datasets
The dataset we use is a set of heart failure data. The dataset consists of attributes such as age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiogram results, maximum heart rate achieved, exercise-induced angina, old peak, the slope of the peak exercise ST segment, and the output class (whether the subject has heart disease or not) of 918 distinct observations. 

Fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved on 27/08/2022 from https://www.kaggle.com/fedesoriano/heart-failure-prediction

### Attribute Information

- Age: age of the patient [years]
- Sex: sex of the patient [M: Male, F: Female]
- ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mm/dl]
- FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
- Oldpeak: oldpeak = ST [Numeric value measured in depression]
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- HeartDisease: output class [1: heart disease, 0: Normal]

# Data Analysis Report
To access the data analysis report, you can download the "report.html" file in this repository or 
<a href="https://vhsxuz.github.io/heart-disease-eda-report/">
click here
</a>

# Summary
We create this EDA in several simple steps. Our first step is to determine what technology we want to use. For this EDA, we use Python, Jupyter Notebook, and the library of Pandas for all the data-related purposes. The next step is to download the dataset that we want (Heart Failure Prediction Dataset by Fedesoriano) from Kaggle. After these steps, we then import the data to Python code and generate the profile by using the ProfileReport function from pandas_profiling. The data analysis report then could be accessed/viewed in HTML format. 

From the report, we can see information that is considered highly correlated by the program. One of the examples is that the program finds that chest pain is highly correlated with heart disease (not confirmed by any journal or any professionals). <b>But, as the observable data is very few and we are not professionals in this field, we can't guarantee that any analysis produced is accurate and true.</b> But we can say that this could be a new method for further data analysis purposes and still could be developed more. 
