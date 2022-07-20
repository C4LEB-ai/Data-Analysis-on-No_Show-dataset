# Data-Analysis-on-No_Show-dataset
<a id='intro'></a>
## Introduction

### Dataset Description 

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

- ‘ScheduledDay’: tells us on what day the patient set up their appointment.
- ‘Neighborhood’: indicates the location of the hospital.
- ‘Scholarship’: indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
- For the last column [No_show]: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

>link to the dataset here https://www.kaggle.com/datasets/joniarroba/noshowappointments

### Question(s) for Analysis
### Questions posed ...
 - what factors will determine if a patient will show up on their appointment ?
 - what factors makes a patients not showing up for their invitation ?
 - which columns are relevant for our analysis ?
 - which of the neighbourhood showed up most for the invitations ?
 - which among the newbourhood ignored the invitation most and why ?
 - which AppointmentDay does patient tends to show up best for their invitation ?
 - which scheduledday does a patient tends to show up best for thir invitation ?
 - how do we improve the service such that a patient can easily show up for their invitation ?
 
 <a id='eda'></a>
# Exploratory Data Analysis (EDA)
## Quetions Covered!
- ### How does each of the samples affect the No_show ?
 - the relationship between each of the samples
 - what sample is said to be dropped 
 - What are the correlation of the samples
- ### What age  range is more likely to show up ?
 - how does age affect the no show and other variaable
- ### At what year do we have the highest sho up ?


 <a id='conclusions'></a>
 ## conclusions
 
 
>There are different factors that makes patients not showing up for their invitations
 for instance scheduledday: some days appears more favourable to the patients, since they showed up most
    >- eg, 2015-12-03, 2016-10-04, 2016-01-26, 2016-02-25
    >- patients tends to show up more at the begining and also at the end of the month
    
>Women do show up on their appointments more often than men do, but this may be affected by the percentage of women on this dataset.
    >- Almost half of our sample consists of women with a wider age range and a few outliers, all of whom had a higher rate than men.
    >- Therfore i can say that the data is imbalanced because males represent 33.2% of observations
 
>The high majority of our dataset does not have chronic deseases, yet, they are existed in so many young people.
    >-  Therfore having a chronic deseas  affect patients from showing up at a hospital's appointment.

>Almost half of our sample consists of women with a wider age range and a few outliers, all of whom had a higher rate than men.
therfore i can say that the data is imbalanced because males represent 33.2% of observations

 
 >sending sms to everyone will as well increase the chance of patient showing up for their invitation
    >- Though they exist no really strong correlation between any of the samples and no_show
    >- But factors like hipertension , Age and neighbourhood really affects the no_show
#### LIMITATION
 - There was no distance specified between the neighbourhood and the hospital
  which will as well help me to figure out more why people don't show up or hounour their invitation
