# Coronary-Heart-Disease-Prediction

About the Dataset:

The dataset is publically available on the Kaggle website, and it is from an 
ongoing ongoing cardiovascular study on residents of the town of Framingham, 
Massachusetts. The classification goal is to predict whether the patient 
has 10-year risk of future coronary heart disease (CHD).
The dataset provides the patients’ information. It includes over 4,240
records and 15 attributes.

Attributes:

sex: male(1) or female(0);(Nominal)

age: age of the patient;(Continuous - Although the recorded ages have been 
truncated to whole numbers, the concept of age is continuous)

currentSmoker: whether or not the patient is a current smoker (Nominal)

cigsPerDay: the number of cigarettes that the person smoked on average 
in one day.(can be considered continuous as one can have any number of cigarretts, even half a cigarette.)

BPMeds: whether or not the patient was on blood pressure medication (Nominal)

prevalentStroke: whether or not the patient had previously had a stroke
(Nominal)

prevalentHyp: whether or not the patient was hypertensive (Nominal)

diabetes: whether or not the patient had diabetes (Nominal)

totChol: total cholesterol level (Continuous)

sysBP: systolic blood pressure (Continuous)

diaBP: diastolic blood pressure (Continuous)

BMI: Body Mass Index (Continuous)

heartRate: heart rate (Continuous - In medical research, variables such as 
heart rate though in fact discrete, yet are considered continuous because 
of large number of possible values.)

glucose: glucose level (Continuous)

10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” 
means “No”) - Target Variable

Objective: Build a classification model that predicts heart disease in a 
subject. 



The following steps are performed : 
- Read the file and display columns.
- Handle missing values
- exploratory analysts and describe your observations.
- Select columns that will be probably important to predict heart disease.
- If you remove columns explain why you removed those.
- Create training and testing sets (use 80% of the data for the training and
- reminder for testing).
- Build a machine learning model to predict TenYearCHD
- Evaluate the model ()
- Conclude your findings (Model which is giving best score )
