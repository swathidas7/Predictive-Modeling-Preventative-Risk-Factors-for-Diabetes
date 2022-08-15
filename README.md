# Predictive-Modeling-Preventative-Risk-Factors-for-Diabetes
The dataset was found through Kaggle. https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset?select=diabetes_binary_5050split_health_indicators_BRFSS2015.csv 
I plan to use a dataset on Diabetes Health Indicators from the Behavioral Risk Factor Surveillance System (BRFSS) and the Centers for Disease Control and Prevention (CDC). The dataset consists of 70,692 survey responses to the CDC's BRFSS2015 and 22 columns. It has an equal 50-50 split of respondents with no diabetes and with either prediabetes or diabetes. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 field variables.
The variables are HighBP, HighChol, CholCheck, BMI, Smoker, Stroke, HeartDiseaseorAttack, PhysActivity, Fruits, Veggies, HvyAlcoholConsump, AnyHealthcare, NoDocbcCost, GenHlth, MentHlth, PhysHlth, DiffWalk, Sex, Age, Education, and Income. All fields have categorical binary data types except for BMI, which is quantitative continuous, and MentHlth, PhysHlth, GenHlth, Age, Education, and Income are ordinal. 
After downloading the CSV, I will upload it to my Google Drive, and finally mount it into my Google Colab notebook. 

I would like to answer three questions using the data. The first is to see if there is a significant difference between the BMI for people with diabetes versus without diabetes. The second is to see if there is a significant difference between people who did not go to the doctors because of cost who have diabetes compared to people who don’t have diabetes (NoDocbcCost). The last is to see if there is a significant difference between people who have diabetes and make below poverty level income versus people who make above poverty level income.

Hypotheses
Test 1
Null Hypothesis - There is no statistically significant difference between BMI and people with diabetes or without diabetes. 
Alternative Hypothesis 1: There is a statistically significant difference between BMI and people with diabetes or without diabetes. 
Test 2
Null Hypothesis - There is no statistically significant difference between people who did not go to the doctors due to cost and people who have diabetes or people who do not have diabetes. 
Alternative Hypothesis 1: There is a statistically significant difference between people who did not go to the doctors due to cost and people who have diabetes or people who do not have diabetes.
Test 3
Null Hypothesis - There is no statistically significant difference between people who have diabetes and people who make below poverty level income and people who make above poverty level income.
Alternative Hypothesis 1: There is a statistically significant difference between people who have diabetes and people who make below poverty level income and people who make above poverty level income.

I will use a t-test for the first question to test for significant differences. For the second I will use a z-test to test for significant differences. NoDocbcCost is already in a binary data type but Income will be split into two categories, below and above poverty level to accurately perform a z-test.

This analysis will seek to provide further insight into the trends of diabetes. These findings will be valuable not only to doctors to help their patients stay ahead of their health, but these insights can also be valuable to the general public. Each risk factor is something people can work on and it can prevent their risks of getting diabetes. I believe findings from this project can be valuable to also help with healthcare marketing 
