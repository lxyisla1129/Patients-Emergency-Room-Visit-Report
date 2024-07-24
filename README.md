# Patients Emergency Room Visit Analysis

## Project Overview

This project involves analyzing data from patients' emergency room visits to identify key trends and insights. The analysis aims to improve understanding of patient demographics, wait times, satisfaction scores, and other critical factors influencing emergency room efficiency and patient care.

## Data Source

The data used in this analysis comes from a dataset containing records of patients' emergency room visits. Each record includes information such as patient ID, age, gender, race, satisfaction score, wait time, and more. (

### Data Dictionary

| Column Name             | Data Type | Description                                                                                                    |
|-------------------------|-----------|----------------------------------------------------------------------------------------------------------------|
| **date**                | String    | The date of the patient's record entry (format: Month Year).                                                   |
| **patient_id**          | String    | A unique identifier for each patient (format: xxx-xx-xxxx).                                                    |
| **patient_gender**      | String    | The gender of the patient (M for Male, F for Female).                                                          |
| **patient_age**         | Integer   | The age of the patient in years.                                                                               |
| **patient_sat_score**   | Integer   | The satisfaction score of the patient.                                                                         |
| **patient_race**        | String    | The race of the patient.                                                                                       |
| **patient_admin_flag**  | Boolean   | A flag indicating whether the patient is an admin (True/False).                                                |
| **patient_waittime**    | Integer   | The wait time of the patient in minutes.                                                                       |
| **department_referral** | String    | The department to which the patient was referred.                                                              |
| **Full Name**           | String    | The full name of the patient.                                                                                  |
| **Moment**              | String    | The time of day the record was created (AM/PM).                                                                |
| **Age Bracket**         | String    | The age bracket of the patient (ranges: 0-10, 11-20, 21-30, 31-40, 41-50, 51-60, 61-70).                        |
| **Age Group**           | String    | The age group of the patient (e.g., Infancy, Middle Childhood, Teenager, Adult).                               |

## Tools and Technologies

- **Power BI**: Used DAX from ETL, data cleaning and statistical analysis. And report is esed for data visualization and creating interactive dashboards.

## Analysis Summary

### Key Insights

1. **Patient Demographics**: Analyzed the distribution of patients by age, gender, and race to understand the demographic profile of emergency room visitors.
2. **Wait Times**: Investigated the average wait times and identified factors contributing to longer waits, aiming to enhance efficiency in patient processing.
3. **Satisfaction Scores**: Examined patient satisfaction scores to identify areas for improvement in patient care and service delivery.
4. **Referral Patterns**: Studied department referral patterns to understand the flow of patients within the healthcare system and improve resource allocation.
5. **Time-Based Trends**: Evaluated trends based on the time of day and month to optimize staffing and resource management in the emergency room.

### Visualizations

The Power BI report includes various visualizations such as:

- Total Patients Visits: Displays the total number of patient visits, segmented by administrative and non-administrative appointments.
- Average Satisfaction and Waiting Time: Shows average patient satisfaction scores and average waiting times.
- Patients by WeekType: A bar chart showing the number of patients visiting on weekdays versus weekends.
- Total Patients by Age Group: A bar chart displaying the distribution of patients across different age groups.
- Total Patients Visits by Year: A line graph tracking the total number of patient visits over the years.
- Total Patients by Department Referral: A bar chart indicating the number of patients referred to various departments.
- Gender Distribution: A chart showing the distribution of patients by gender.
- Heatmap of Satisfaction Scores: A heatmap displaying patient satisfaction scores across different age groups and races.

## Conclusion

This analysis provides valuable insights into the factors affecting emergency room efficiency and patient satisfaction. By leveraging data visualization and advanced analytics, healthcare providers can make informed decisions to enhance patient care and optimize resource allocation.

## How to Use

1. Clone this repository to your local machine.
2. Open the Power BI file (`Patients Emergency Room Visit Report.pbix`) to explore the interactive dashboards and visualizations.

Followd the guidance of https://www.youtube.com/watch?v=U5ZKjZsZX64. 
