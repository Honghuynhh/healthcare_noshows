
----Healthcare Appointment No-Shows Analysis

This project focuses on analyzing no-show rates for medical appointments in a healthcare system. The dataset contains details about patient demographics, appointment scheduling, medical conditions, and the outcomes (whether patients showed up or not). By leveraging visualizations, this project provides insights into factors that influence appointment attendance and no-show patterns.

----OVERVIEW

The project uses a dataset that records information such as patient IDs, appointment dates, age, gender, medical conditions (diabetes, hypertension, alcoholism, etc.), SMS reminders, and the outcome of whether the patient showed up for their appointment.

A Power BI dashboard has been developed to visualize and analyze key aspects of the dataset, with the following elements:

- Total Patients and Appointments: Overview of the total number of patients and appointments.
- No-Show Percentage: The percentage of appointments missed.
- Show-Up Statistics: The total number of patients who attended their appointments.

----KEY VISUALIZATION

1. Gender by Age Group: A breakdown of patients by age group and gender to show the distribution of appointments across different demographics.
2. Age Group Distribution: A pie chart showing the proportion of appointments by age group, highlighting which age groups represent the largest number of appointments.
3. Medical Conditions and Show-Up Outcome: A bar chart representing how medical conditions like diabetes, hypertension, and alcoholism correlate with appointment attendance.
4. Scheduled Day Heatmap: A heatmap showing the distribution of appointments across the days of the week, providing insights into the busiest and least busy days for scheduling.
5. Gender & Show-Up Outcome: A bar chart that visualizes the relationship between gender and the likelihood of showing up to an appointment.
6. Age Group & Show-Up Outcome: A bar chart showing the show-up rate across different age groups.
7. SMS & Show-Up Outcome: A bar chart highlighting the impact of sending SMS reminders on appointment attendance.
8. Top 3 Neighbourhoods & Show-Up Outcome: A breakdown of attendance by neighborhood, showing which areas have higher or lower show-up rates.

----RESULT

- Impact of Age: Younger patients (aged 0-18) tend to have higher no-show rates, while middle-aged patients (19-44) have the highest attendance.
- Medical Conditions: Patients with hypertension are more likely to attend their appointments compared to those with other conditions.
- SMS Reminders: Interestingly, the analysis showed that the group of patients who received SMS reminders had a higher no-show rate (28.57%) compared to those who did not receive SMS reminders (16.67%). This suggests that SMS reminders alone might not be enough to reduce no-show rates. Further investigation is needed to understand the underlying reasons, such as the content and frequency of SMS messages, or other factors like patient motivation and accessibility.
- Scheduling Patterns: Tuesday is the most common day for appointments, while Thursday sees the fewest appointments.
- Neighborhood Trends: Certain neighborhoods like Jardim Camburi have higher no-show rates compared to others.


----DATASET

The dataset includes the following columns:
- PatientId: Unique ID of the patient.
- AppointmentID: Unique ID of the appointment.
- Gender: Patient's gender.
- ScheduledDay: The date when the appointment was scheduled.
- AppointmentDay: The date when the appointment was supposed to take place.
- Age: Patient's age.
- Neighbourhood: The location/neighborhood of the patient.
- Scholarship: Whether the patient is under a government assistance program.
- Hipertension: Whether the patient has hypertension.
- Diabetes: Whether the patient has diabetes.
- Alcoholism: Whether the patient has a history of alcoholism.
- Handcap: Whether the patient is handicapped.
- SMS_received: Whether the patient received an SMS reminder about the appointment.
- Showed_up: Whether the patient showed up for the appointment.
- Date.diff: Difference in days between the scheduled date and the appointment date.


