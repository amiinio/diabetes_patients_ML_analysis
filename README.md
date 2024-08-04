# diabetes_patients_ML_analysis

Data source: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008


This dataset comprises records of hospitalized patients diagnosed with diabetes, collected over a decade (1999-2008) from 130 U.S. hospitals and integrated delivery networks. It includes over 50 features related to patient demographics, medical history, and hospital outcomes. The dataset is derived from inpatient encounters that meet the following criteria:

The encounter is an inpatient admission.
It is identified as a diabetic encounter, with any form of diabetes recorded as a diagnosis.
The length of stay ranges from a minimum of 1 day to a maximum of 14 days.
Laboratory tests were conducted during the encounter.
Medications were administered during the encounter.
The dataset contains sensitive information, including patient age, gender, and race. It is recommended to use a standard train-test split or a three-way holdout split (train-validation-test) for model selection. The dataset includes attributes such as patient ID, race, gender, age, admission type, duration of hospital stay, medical specialty of the admitting physician, number of lab tests conducted, HbA1c test results, diagnoses, number of medications, diabetic medications, and the number of outpatient, inpatient, and emergency visits in the year preceding the hospitalization.
