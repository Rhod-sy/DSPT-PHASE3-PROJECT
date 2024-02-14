![Headerimage](./Charts%20%26%20Images/traffic.jpg)

# Phase 3 Project - Chicago Road Safety Assessment: Predictive Modeling for Injury Severity

**Authors:** DSPT05 Group 17

***
## Business Understanding
This project aims to develop a predictive model for injury severity in car crashes within the jurisdiction of the City of Chicago. Sponsored by the Chicago City administration, this assessment serves as a strategic initiative to provide meaningful insights and guide resource allocation while optimizing safety measures, ultimately reducing fatalities resulting from traffic crashes
***
## Data 
The data source for this assessment is the Chicago Car Crashes data from the Chicago Data Portal.
***
Datasets Used:

Traffic Crashes - Crashes This dataset contains information about traffic crashes on city streets within the jurisdiction of the Chicago Police Department (CPD). Records are added when crash reports are finalized or amended in the electronic crash reporting system (E-Crash). Data includes parameters such as injuries, street and weather conditions, posted speed limits.

Traffic Crashes - People This dataset provides details about individuals involved in traffic crashes, including occupants of vehicles, pedestrians, cyclists and others. Injury reports are recorded for each person and the dataset can be linked to the Crash dataset using the "CRASH_RECORD_ID" field, maintaining appropriate relationships.
*** 
## Methods

This project has been executed by developing and assessing various classification models to predict injury severity in traffic accidents. Using machine learning techniques like logistic regression, decision trees, random forests, and K-Nearest Neighbors, we've analyzed factors like location, time of crash, weather, and vehicle involved. By evaluating model performance using metrics such as precision, recall, accuracy, and F1 score, we identified the most effective model. 
***
## Findings
**Top 5 contributors to our model's prediction:**
***
1. Latitude
2. Longitude
   
3. Crash_hour
![Crashesperhour](./Charts%20%26%20Images/hour.png)
***

4. Crash_type

***  
5. Crash_month
![Crashespermonth](./Charts%20%26%20Images/month.png)



These features have a stronger influence on the model's decision-making process as compared to the others.

## Recommendations

1. **Strategic Location-Based Safety Measures:** Focus on high-risk areas identified by latitude and longitude coordinates to implement targeted safety interventions, such as increased police presence and improved road infrastructure.

2. **Time-Specific Safety Initiatives:** Utilize crash hour and month data to deploy time-specific safety measures, like heightened law enforcement during peak accident hours or months, to reduce severe injuries.

3. **Customized Educational Campaigns:** Tailor educational campaigns based on crash types to specific demographics or communities, empowering residents with knowledge to prevent accidents and minimize injury seve.png)

4. **Model Refinement:** Continuously improve the predictive model by exploring different algorithms, feature techniques, and tuning parameters for better accuracy.

## Next Steps

1. Model Refinement: Continuously improve the predictive model by exploring different algorithms, feature techniques, and tuning parameters for better accuracy.

2. Validation and Comparison: Validate the model on various datasets and compare its performance with existing standards to ensure reliability.

3. Knowledge Sharing: Encourage collaboration among data scientists, traffic safety experts, and policymakers to share insights and best practices for enhancing road safety initiatives.


## Repository Structure

```
├── Charts & Images
├── DSPT-PHASE3-PROJECT.ipnyb
└── README.md
```
