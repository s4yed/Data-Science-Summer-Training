# Medical Appointments No Shows Data Analysis

## Introduction 

A person makes a doctor appointment, receives all the instructions and no-show. Who to blame?
If this help you studying or working, please don´t forget to upvote :). The dataset contains about 110k medical appointments with its 14 associated variables (characteristics). The most important one if the patient show-up or no-show to the appointment. Reference to Joni Hoppen and Aquarela Advanced Analytics [Aquarela](http://bit.ly/2Ulwskh).

### Some Definitions:

- **Hipertension:** Also known as high blood pressure (HBP), is a long-term medical condition in which the blood pressure in the arteries is persistently elevated.
- **Alcoholism:** Broadly, any drinking of alcohol that results in significant mental or physical health problems. 
- **Handcap:** Disability, an impairment that substantially affects a person's life activities, and may be present at birth or arise later in life.
- **Diabetes:** A disease in which your blood glucose, or blood sugar, levels are too high.
- **Scholarship:** This variable means this concept: [Bolsa Família](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia)

### Data Dictionary

- **PatientId:** Identification of a patient
- **AppointmentID:** Identification of each appointment
- **Gender:** Male or Female.
- **ScheduledDay:** The day someone called or registered the appointment, this is before appointment of course.
- **DataAgendamento:** The day of the actuall appointment, when they have to visit the doctor.
- **Age:** How old is the patient.
- **Neighbourhood:** Where the appointment takes place.
- **Scholarship:** True of False.
- **Hipertension:** True or False.
- **Diabetes:** True or False.
- **Alcoholism:** True or False.
- **Handcap:** True or False.
- **SMS_received:** 1 or more messages sent to the patient.
- **No-show:** True or False.

### Questions that would be able to answer during our analysis:

- What is the percentage of patients who showed up and who didn't?
- Who is the most committed to the schedule males or females?
- Does receiving SMS or not affect showing up the patients?
- Does the duration between the apointment day and the schedule day affect showing up the patients?
- Dows alcoholism affect the ability to show up?
- Where is the place that most patients showed up?
- What is the most disease by which the patients are diagnosed?
- Does a certain age more committed to the appointment than the others?

In order to address those questions, there are some things to do such as:

1. Cleaning the dataset from any incorrect datatypes or null values.
2. Calculating some statistics about the variables and look for any relationships in the data.
3. Drawing conclusions with some charts and communicating the findings.