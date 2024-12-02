# diabetes_prediction_dataset

Hi,

As part of my journey as Data Scientist, i'm analysing different datasets to explore different data trends. Here i', trying to analyse the Dataset based on diabetes, across genders different age groups and other related factors that may lead to diabetes.

This dataset contains 9 columns, that gives us variety of factors that involves in identifying the diabetes in a patient.

gender: This column gives us the gender of the patient involved in the study.

Age: This column gives us the information on age of the patient. older age people may experience diabetes most often than the young age people.

hypertension: This column let us know whether the patient has a hyptertension diagonised already. A patient with hypertension is most likely to get diabetes than an normal patient.

Smoking_history: This column let us know whether the patient smoking history over the years. A patient who are/had smoking habits are more likely to diagonised with diabetes than no history patients.

BMI: This column lets us know the Body mass index of the patient, involving their height and weight. The ideal BMI for adults ranges from  18.5 to 24.9. Patients who has BMI more than 25 are overweignt and less than 18 are Underweight, in which cases they are more likely to be diagonised with diabetes.

HbA1c_level: This column let us know the hemoglobin A1C value in patients blood. This gives us the average blood sugar (glucose) level was over the past two to three months. Based on age the average level varies and diabetes are most likely conformed based on this values.

blood_glucose_level: This column gives us the current Blood glucose value of the patient. Ideally the level should range between 100 - 140 after food. 

Diabetes: This column confirms whether the patient has diabetes are not, using the previous mentioned columns.

**Machine Learning model:** The machine learning model i'm trying to develop here is based on supervised learning.  The machine is trained on a set of labeled data, which means that the input data is paired with the desired output. The machine then learns to predict the output for new input data. Here by using the set of labeled data(Independent variables) are gender, age, hypertension, smoking_history, BMI, HbA1c_level, blood_glucose_level. The desired output value is stored in Diabetes(Dependent variables).

**Objective of the project:** By using the set of labeled data, i'm trying to build a model to predict the output data (Diabetes). In future, when the system is fed with labeled data the diabetes will be predicted automatically.
