## Medical_No_Show_Appointments

#### The original problem description and data set can be found here: [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments/home)

Situation:

The project "Medical_No_Show_Appointments" aims to investigate a dataset of medical appointment records from Brazil. The dataset includes attributes of patients and indicates whether they showed up for their appointments.

Task: 

The task was to analyze the dataset to identify factors influencing whether patients attend their appointments. This involves data cleaning, exploratory data analysis, and deriving insights.

Action:

Data Wrangling:
Imported necessary libraries (pandas, numpy, matplotlib, seaborn).
Loaded and inspected the dataset for duplicates and missing values.
Renamed columns for consistency and removed unnecessary columns.
Dropped duplicate records based on patient ID and no-show status.
Exploratory Data Analysis:
Created histograms to visualize distributions of attributes like age, scholarship, hypertension, diabetes, alcoholism, handicap, and SMS received.
Divided the dataset into two groups: patients who showed up and those who did not.
Calculated and compared mean values for attributes across these groups.
Result: The analysis revealed that age, scholarship status, hypertension, and SMS reminders are significant factors influencing patient attendance. For instance, patients who received SMS reminders were more likely to show up for their appointments.

Reflection: This project demonstrates effective data cleaning and analysis techniques. It highlights the importance of communication methods like SMS reminders in improving appointment attendance, providing valuable insights for healthcare providers to enhance patient engagement.
