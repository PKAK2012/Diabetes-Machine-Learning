# Diabetes-Machine-Learning

This repository handles the Diabetes Dataset for Machine Learning preprocessing and feature engineering.

Columns Description:

 0   Age                             50000 non-null  int64  
 1   Gender                          50000 non-null  object 
 2   Ethnicity                       50000 non-null  object 
 3   Income                          50000 non-null  int64  
 4   BMI                             50000 non-null  float64
 5   Blood_Pressure                  50000 non-null  float64
 6   Cholesterol                     50000 non-null  float64
 7   Exercise_Hours_Per_Week         50000 non-null  float64
 8   Alcohol_Consumption_Per_Week    50000 non-null  int64  
 9   Smoking_Status                  50000 non-null  object 
 10  Family_History_Diabetes         50000 non-null  int64  
 11  Glucose_Level                   50000 non-null  float64
 12  HbA1c                           50000 non-null  float64
 13  Insulin_Resistance              50000 non-null  float64
 14  Heart_Disease_History           50000 non-null  int64  
 15  Physical_Activity_Level         50000 non-null  object 
 16  Fast_Food_Intake_Per_Week       50000 non-null  int64  
 17  Processed_Food_Intake_Per_Week  50000 non-null  int64  
 18  Daily_Caloric_Intake            50000 non-null  int64  
 19  Sleep_Hours_Per_Night           50000 non-null  float64
 20  Stress_Level                    50000 non-null  object 
 21  Medication_Use                  50000 non-null  int64  
 22  Diabetes_Diagnosis              50000 non-null  int64  

Data Preprocessing Steps:

Step 1: Checking Column Names
Verified that column names do not contain spaces. No changes were needed.

Step 2: Converting Gender Column
The Gender column is of type object.
Converted it to integer values:
Male → 1
Female → 0

Step 3: Checking for Null Values
No null values were found in any column.

Step 4: Encoding Object Data Types
Columns with object datatype were converted to numerical format using Ordinal Encoding.

Step 5: Standardizing Text Data
Before encoding, ensured consistency in spelling for categorical column values.

Step 6: Encoding Categorical Features
Applied encoding techniques to convert categorical columns into numerical format.

 #   Column                          Non-Null Count  Dtype  
---  ------                          --------------  -----  
 0   Age                             50000 non-null  int64  
 1   Gender                          50000 non-null  int64  
 2   Ethnicity                       50000 non-null  float64
 3   Income                          50000 non-null  int64  
 4   BMI                             50000 non-null  float64
 5   Blood_Pressure                  50000 non-null  float64
 6   Cholesterol                     50000 non-null  float64
 7   Exercise_Hours_Per_Week         50000 non-null  float64
 8   Alcohol_Consumption_Per_Week    50000 non-null  int64  
 9   Smoking_Status                  50000 non-null  float64
 10  Family_History_Diabetes         50000 non-null  int64  
 11  Glucose_Level                   50000 non-null  float64
 12  HbA1c                           50000 non-null  float64
 13  Insulin_Resistance              50000 non-null  float64
 14  Heart_Disease_History           50000 non-null  int64  
 15  Physical_Activity_Level         50000 non-null  float64
 16  Fast_Food_Intake_Per_Week       50000 non-null  int64  
 17  Processed_Food_Intake_Per_Week  50000 non-null  int64  
 18  Daily_Caloric_Intake            50000 non-null  int64  
 19  Sleep_Hours_Per_Night           50000 non-null  float64
 20  Stress_Level                    50000 non-null  float64
 21  Medication_Use                  50000 non-null  int64  
 22  Diabetes_Diagnosis              50000 non-null  int64  

Conclusion:
After performing all the preprocessing steps, the dataset is now ready for Machine Learning modeling.

