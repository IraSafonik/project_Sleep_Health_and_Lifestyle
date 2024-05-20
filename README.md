# Project: Sleep Health and Lifestyle Analysis

## ☝️Problem: 
Sleep quality is vital for overall health and well-being, yet many individuals struggle with sleep disorders. Identifying factors contributing to poor sleep and predicting sleep disorders can aid in early intervention and management.

## 💡Solution: 
Leveraging the Sleep Health and Lifestyle Dataset, which comprises 400 rows and 13 columns covering variables related to sleep and daily habits, this project aims to analyze the data, process it, and develop machine learning classification models to predict the likelihood of sleep disorders. By examining factors such as gender, age, occupation, sleep duration, physical activity level, stress levels, BMI category, and more, the models can provide insights into sleep health and aid in identifying individuals at risk of sleep disorders.

## 🔑 Key Features
- Analyze Sleep Health and Lifestyle Dataset to identify patterns and trends related to sleep and daily habits.
- Preprocess and clean the data to prepare it for machine learning model development.
- Develop machine learning classification models to predict the likelihood of sleep disorders based on input variables.
- Evaluate model performance and provide insights into factors contributing to sleep disorders.
- Provide recommendations for improving sleep health based on data analysis.

## 🗂️ Dataset
I will utilize the "Sleep_health_and_lifestyle_dataset.csv" database from kaggle, that has been made available for us. Here you will find an analysis of the dataset, detailing the data processing steps, and the application of machine learning classification models to accomplish our objectives.
<img width="989" alt="Знімок екрана 2024-05-20 о 17 02 21" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/41ec94b5-bb96-42f2-90e3-68186615495b">


## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook (for data analysis and model development)

## Summary

This project aimed to analyze and understand the relationship between various health metrics and sleep disorders. The analysis was conducted using a dataset containing information on sleep duration, quality of sleep, physical activity level, stress level, heart rate, daily steps, age, occupation, and blood pressure.

## Insights

### 1. Demographic Dynamics: 
The dataset encapsulated a broad spectrum of demographics. For instance, it spanned across various age groups, with individuals ranging from 27 to 59 years old. Among the participants, 35% were between 27 and 35 years old, 45% were between 36 and 50 years old, and 20% were between 51 and 59 years old.
* Such diversity facilitated a nuanced examination of sleep disorders across different life stages.
<img width="912" alt="Знімок екрана 2024-05-20 о 17 14 10" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/554a8cae-8fce-47b4-b6ab-974181a7371b">
<img width="793" alt="Знімок екрана 2024-05-20 о 17 06 28" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/3a17c91a-20cf-4cdb-8eab-ecaa358ed4d7">

### 2. Age and Sleep Patterns: 
Analyzing age-specific sleep patterns revealed that younger individuals (27-35 years old) accounted for 25% of those reporting sleep disorders, while older adults (51-59 years old) represented 40% have their absence.
<img width="875" alt="Знімок екрана 2024-05-20 о 17 07 56" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/ff810e25-1a9e-4eaf-b681-4b51736ca8c3">
<img width="770" alt="Знімок екрана 2024-05-20 о 17 07 11" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/3aba58e6-e73e-4128-9edd-82fdbd0b847b">

### 3. Gender Disparities in Sleep Health: 
Among females, 18% reported sleep disorders, while among males, 15% reported sleep disorders.
* While the difference in prevalence rates appears modest, further analysis may uncover gender-specific factors contributing to sleep disturbances.
<img width="840" alt="Знімок екрана 2024-05-20 о 17 07 36" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/a920b62f-e2ae-4cf1-a6f8-75b426cfd5c7">
<img width="802" alt="Знімок екрана 2024-05-20 о 17 07 20" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/0d30770d-ce18-498a-818a-8dcda5ab02fc">

### 4. Physical Activity and Sleep Quality: 
Participants reporting high levels of physical activity accounted for 30% of the dataset, with 85% of them reporting satisfactory sleep quality. In contrast, those with low physical activity levels comprised 70% of the dataset, with only 60% reporting satisfactory sleep quality.
* These findings suggest a positive association between physical activity and sleep quality, underscoring the importance of regular exercise for promoting better sleep outcomes.
<img width="873" alt="Знімок екрана 2024-05-20 о 17 33 41" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/3d42c016-4d55-4cf9-b0da-c3f0deba66b0">
<img width="836" alt="Знімок екрана 2024-05-20 о 17 16 09" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/02d9bcf1-cc11-424b-b783-1187e7245f5e">
<img width="836" alt="Знімок екрана 2024-05-20 о 17 15 54" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/1d82379b-e465-48a6-971b-233e14c12a5f">

### 5. Occupational Implications: 
Certain occupations exhibited higher prevalences of specific sleep disorders. Notably, nurses and doctors displayed a higher prevalence of sleep disorders compared to individuals in other professions. For example, nurses had an average of 73 occurrences of sleep disorders in the dataset, while doctors had 71 occurrences.
* These findings indicate a potential association between occupational stress and sleep disturbances, highlighting the importance of addressing workplace factors for improved sleep health.
<img width="665" alt="Знімок екрана 2024-05-20 о 17 33 09" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/f447ea39-de24-4785-a4a5-18791e681d5c">
<img width="852" alt="Знімок екрана 2024-05-20 о 17 16 25" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/04e6c933-c6ca-4f4f-a2a3-b9d304472b21">

### 6. Blood Pressure Associations: 
Examination of blood pressure distributions across individuals with different sleep disorders uncovered potential associations between blood pressure levels and specific sleep disorders. For instance, individuals with higher blood pressure readings, such as 140/95 mmHg, appeared more frequently among certain sleep disorder categories.
<img width="847" alt="Знімок екрана 2024-05-20 о 17 17 54" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/c39c72c7-4094-4965-ab04-f5783cd89474">
<img width="838" alt="Знімок екрана 2024-05-20 о 17 17 02" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/ee9e0784-a962-4a03-913c-7c46aa063c65">

### 7. Health Metric Disparities: 
Variations in health metrics were evident across individuals with different sleep disorders. For instance, individuals diagnosed with insomnia exhibited higher stress levels and lower physical activity levels compared to those without sleep disorders or with sleep apnea.
<img width="791" alt="Знімок екрана 2024-05-20 о 17 43 06" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/a38ea75f-ff31-4b49-bb3f-3222d4d248a6">
<img width="749" alt="Знімок екрана 2024-05-20 о 17 42 33" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/588ac7a8-7a80-42e4-a4b3-93b28646bde9">
<img width="778" alt="Знімок екрана 2024-05-20 о 17 41 53" src="https://github.com/IraSafonik/project_Sleep_Health_and_Lifestyle/assets/32171563/17fc691d-37d5-4634-bfa4-2f5b3f94802e">


### Overall, this project provided valuable insights into the complex relationship between various health metrics, demographics, and sleep disorders. Understanding these relationships can aid in developing targeted interventions and strategies for improving sleep health and overall well-being across different population groups.
