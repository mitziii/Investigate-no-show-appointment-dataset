# Investigate-no-show-appointment-dataset
Investigate data about medical appointments in Brazil to see if patients show up for their appointment

## Investigate-a-dataset

Using Python libraries such as Pandas, NumPy and Matplotlib to investigate (wrangle, explore, draw conclusions and communicate) a dataset


## Overview

In this project, I have analysed a dataset and then communicate the findings about it.


## Python libraries

    pandas
    NumPy
    Matplotlib

## Project tasks

  * A typical data analysis process: posing questions that can be answered and answering those questions
  * Investigate problems and wrangle the data into a format, and communicate the results
  * Be able to use vectorized operations in NumPy and pandas, use pandas' Series and DataFrame objects
  * Use Matplotlib to produce plots

## Dataset

**noshowappointments-kagglev2-may-2016.csv**

* This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.

* A number of characteristics about the patient are included in each row as follows:

 - ‘Scheduled Day’ tells us on what day the patient set up their appointment.
 - ‘Neighborhood’ indicates the location of the hospital.
 - ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
 - The last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.   

## Questions

**What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?**

## Findings

• Firstly, gender is not a predictor to expect a patient showing up or not since percentage of patients showing up at appointment of female and male is similar.

• The patients having scholarship are 4% less likely to show up for appointments than the group of not receiving scholarship.

• The hypertension, alcoholism and diabetes are not the factors to predict if a patient will show up at appointments.

• It is not necessary to send SMS to remind patients about their appointment since the group of patients receiving sms is 10% less likely to come to the appointment.

• Age of the patients is a good predictor to predict if a patient will show up for appointment since the probability of showing up of a patient is related to his/her age. The probability of showing up for medical appointments is correlated with the age of the patients in the same direction. From the age of 20 and above, showing up probability increases in line with the age.

• In addition, the number of missed appointment is another good factor to predict whether a patient will come up at the appointment or not. A patient with low number of previously missed appointment tend to come up at the appointed day rather than the patient with history of more missed appointment.

• The handicap situation of a patient is related to the probability of coming to the appointment. The increase in the number of handicap is related with a decrease in the probability of showing up. When the number of handicap increases from 1 to 4, the corresponding probability of showing up for appointment declines from 82% to 66%.

• The neighbourhood that a patient lives in also helps to predict if the patient shows up or not. For instance, the patients from PARQUE INDUSTRIAL, ILHA DO BOI, AEROPORTO, MARIO CYPRESTE and SOLON BORGES are most likely to show up for appointment whilst the patients from SANTA CLARA, SANTA CECÍLIA, SANTOS DUMONT and ILHAS OCEÂNICAS DE TRINDADE are the least likely to show up for medical appointment in Brazil.

