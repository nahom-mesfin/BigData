# Medical Appointments No-Shows

### Overview

This dataset No-Show Appointments collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

### Dataset
### Source of Dataset
https://www.kaggle.com/datasets/joniarroba/noshowappointments

### Tools and Libraries
Jupyter Notebook
Python
pandas
numpy
matplotlib.pyplot
seaborn
sklearn



# Data Exploration Summary

1. Gender vs. Show/No-Show
Key Findings:
Female Attendance: Majority of appointments attended by females (57,246 'Show', 14,594 'No-Show').
Male Attendance: Considerable attendance rate for males (30,962 'Show', 7,725 'No-Show').
Proportionality: While females generally have higher attendance, 'No-Show' proportions are consistent.
Overall Attendance: High total attendance for both genders.


2. Age vs. Show/No-Show
Key Findings:
Average Age: Attendees (37.47) slightly older than non-attendees (34.07).
Age Distribution: Skewed between 18 and 56 for both groups.
Interquartile Range (IQR): Similar IQR, indicating comparable central tendency.


3. Age and Gender vs. Show/No-Show
Key Findings:
Distribution by Age and Gender: Heatmap reveals varied attendance patterns.
Variability: Different age-gender groups show diverse attendance behaviors.
Observations: Interplay between age and gender impacts attendance.


4. Weekday vs. Show/No-Show
Key Findings:
Attendance Distribution: Mondays, Wednesdays, and Tuesdays have high attendance.
Lowest Attendance: Saturdays show minimal attendance.
Variability: Weekday influences attendance patterns.


5. Medical Conditions vs. Show/No-Show
Key Findings:
Distribution: Varied distribution of Hipertension, Diabetes, Alcoholism, and Handcap.
Cross-Tabulation Table: Detailed breakdown of conditions in relation to attendance.
Insights: No clear trend in Hipertension and Diabetes; Alcoholism and Handcap impact less evident.


### Conclusion
The exploration provides insights into gender, age, age-gender interaction, weekday influence, and medical conditions affecting appointment attendance. While gender and age show subtle differences, age alone is not decisive. Age-gender interplay and weekday influence attendance patterns. Medical conditions like Hipertension and Diabetes lack clear trends, while Alcoholism and Handcap's impact is nuanced. 