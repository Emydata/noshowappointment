## The NoShow Appointment Data Analysis
The dataset chosen is No-show appointment dataset. The No-Show appointment dataset contains data of medical appointments in Brazil. The dataset is stored in a csv file 'noshowappointment.csv'. The dataset consists of 1 table with 110527 records and 14 columns. The columns in the dataset include:
PatientID 
AppointmentId 
Gender 
ScheduledDay 
AppointmentDay 
Age 
Neighborhood 
Scholarship 
Hypertension 
Diabetes 
Alcoholism 
Handicap 
SMS_received 
No-show

## Analysis Questions
1. What factors are important in predicting whether or not a patient will show up for their scheduled appointment?
2. Does neighbourhood indicate if a patient will show up or not for an appointment?
3. Do patients on scholarship tend to show up more for appointments than others? 4. Are no-show appointment associated with a certain gender?

## Insights
After analyzing the No-Show appointment dataset, it can be discovered that patients show up for appointments at Jardim Camburi and Maria Ortiz more than other neighborhoods.To answer the first question in the analysis section, Neighborhood, SMS_received are good indicators in predicting whether a patient will show up for appointments or not.
To answer question 2, we can see from the "Neighborhood per patients that showed up" chart that more patients showed up for appointments at Jardim Camburi and Maria Ortiz than other neighborhoods, but neighbourhood alone cannot be used to predict if patients will show up or not because patients who received SMS tend to show up more than those who did not.
To answer question 3, comparing the 'Scholarship patients' and the 'Non scholarship patients' chart, Scholarship does not really predict if a patient will show up for an appointment or not.
To answer question 4, looking at the 'Gender of patients that showed up chart' the proportion of male patients that showed up for their appointments tends to be slightly higher compared to that of the females.

## Limitation
This analysis is only limited to medical appointments in Brazil. The dataset provided does not include data about the address of the patients, their occupation or religion.