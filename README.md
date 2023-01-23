# Predicting Death Rates for the top 10 Causes of Death in the United States

---
## Communication Protocols / Strategies

---
- Private Slack Channel created (includes group members)
- Group members have shared phone and personal email infomation in case of urgent issues
- Meetings via Slack huddle, in-person 

---
## Presentation

---

The presentation wil be created using google slides

---
#### Topic Selected:
  
---
Death Rates for the top 10 causes of death
  
---
#### Rationale for Topic Selection: 
  
---
As society changes, so to does the way we live. In some cases, these changes provide a better quality of life, and in other cases these changes increase longevity. Whether it is living longer or living better, death - it's frequwncy and causes - can tell us much about life.

---
#### Source Data: 
  
---
This data was compiled from death certificates in all 50 states and Washington, DC. [Leading Causes of Death in the United States](https://www.kaggle.com/datasets/mattop/leading-causes-of-death-in-the-united-states) includes total deaths and age-adjusted death rates (rate per 100,000 people) by state for ten common causes of death from 1999 to 2017. 

---
#### Questions to Answer:

---
- Which causes of death are increasing over time?
- Which causes of death are decreasing over time?
- Do changes in society correlate to increases or decreases in the death rate of related causes ofdeath?
- Do advances in medicine and technology correlate to changes in the death rate of related causes of death?

---
#### Machine Learning Model

---
The Random Forest Regression model will be used to predict Death rates for a given year based on the cause of death and the state of residence. The data will be trained two ways: Using the data from 1999-2012 as the training set, and 2012 to 2017 as the test data set. Alternatively, the data will be split randomly 70% / 30% train / test data sets. 

---
#### Database

---

The database will be constucted in SQL
