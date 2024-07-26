![image](https://github.com/user-attachments/assets/4e9f0b9a-b97a-4c5f-93ce-2e8c0bbd37d5)


I set myself the following task:

I need to identify as many cases of stroke probability as possible. Therefore, I will have the following key metrics

1. F1 Score (To see how well the model hits)
2. Recall (Important for the first class)
3. Macro recall (To determine the average recall)


Attribute Information
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
