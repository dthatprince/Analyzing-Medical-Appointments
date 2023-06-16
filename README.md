# Medical Appointment Dataset Analysis

This repository contains the code and analysis for exploring a medical appointment dataset. The dataset consists of information about medical appointments of patients in Brazil and focuses on whether patients show up for their scheduled appointments.

## Dataset

The dataset used for this analysis is available [here](https://www.kaggle.com/datasets/joniarroba/noshowappointments?select=KaggleV2-May-2016.csv). It contains 110,527 records and 14 variables (characteristics) related to medical appointments. The variables include patient demographics, appointment details, and other factors that may influence patients showing up for their appointments.

## Research Questions

The analysis in this repository aims to answer the following research questions:

1. What is the gender distribution among patients who book medical appointments?
2. Does the waiting time interval between scheduling and the appointment affect the likelihood of patients showing up?
3. Which factors are important in predicting whether patients will show up for their appointments?
4. Is there a relationship between age and the likelihood of having a scholarship?

## Conclusions

The analysis of the medical appointment dataset led to several key findings and observations:

- Gender Distribution: The data showed that more females booked medical appointments compared to males. Further investigation is required to understand the underlying factors contributing to this gender imbalance.

- Waiting Time Interval: A significant proportion of appointments had a waiting time of 0 days, suggesting same-day scheduling. However, it is important to note that assuming all patients with 0 days of waiting time attended their appointments may not be accurate. Further analysis is necessary to validate this assumption and assess the impact of waiting time on appointment attendance.

- Factors Affecting Appointment Attendance: The analysis did not identify any specific factors that strongly influenced patients' attendance at appointments. Further exploration of individual features is needed to gain deeper insights into the factors that contribute to appointment attendance.

- Age and Scholarship: There was no evident relationship between age and the likelihood of having a scholarship. To draw more conclusive insights on this relationship, additional data, such as the age at which patients obtained their scholarships, would be beneficial.

In conclusion, this analysis provides initial insights into the medical appointment dataset. Further investigation and analysis of individual features, along with the collection of additional data, will be valuable in gaining a better understanding of appointment attendance and the factors that influence it.
