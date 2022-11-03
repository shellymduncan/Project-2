# Heart Failure Predictions
* Author: Shelly-Ann Duncan
# Business Problem
* The purpose of this projest is to predict heart disease in persons, male and female.
# Data Source and Information
* The source for this data can be found at https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction. This dataset is comprised of 12 columns, (11 features and 1 target) and 918 rows representing the characteristics of Heart Disease.
# Data Dictionary
1. Age: age of the patient [years]
2. Sex: sex of the patient [M: Male, F: Female]
3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. RestingBP: resting blood pressure [mm Hg]
5. Cholesterol: serum cholesterol [mm/dl]
6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10. Oldpeak: oldpeak = ST [Numeric value measured in depression]
11. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12. HeartDisease: output class [1: heart disease, 0: Normal]
# Methods
* This dataset was thoroughly examined and cleaned. Several visualizations were created to explain the characteristics of the dataset. After the visualizations were created, several machine learning models were used and then these were tuned using GridSearchCV.
# Explanatory Analysis
![image](https://user-images.githubusercontent.com/110746798/197421952-42aefaeb-5c50-4dda-8158-cc33e4c26ede.png)
* This bar blot shows the different types of Chest Pain Type among Age of patients in relation to Heart Disease. According to the bar plot persons who are of age 55 have the same ASY and TA Chest Pain Type.
![image](https://user-images.githubusercontent.com/110746798/197422469-d1c9cfdf-c022-4ad2-ac4d-3574ff06dd5f.png)
* This bar plot shows that there are more men than women with heart disease.
# Final Model
* My final model choice for Heart Failure predictions is the baseline KNN model. This model has the highest accuracy for predictions of heart failure.
# Final Recommendations
* With this dataset I recommend that medical professionals focus on letting their patients know that even though they may feel fine, they need to pay attention to their health as they may not experience symptoms, they can still be at risk.
* There should also be a focus on their male patients because they are at higher risk for heart disease.
* Consider adding a few more features such as “eating habits,” “weight,” etc.
# Further Contact Information
* For any questions, please email me at shellymduncan@gmail.com
