
# Phase 3 Project 


* Student name: Abdihakim S Mohamed
* Student pace: Part Time
* Scheduled project review date/time:
* Instructor name: Asha Deen

## Project Overview

The project aims to create a model that predicts the probability of SyriaTel's customers ending their service subscriptions. This effort primarily revolves around binary classification techniques. The dataset at our disposal encompasses comprehensive details about customer service plans, their usage habits, and historical interactions with SyriaTel.


### Business Problem and Data

The telecommunications sector, especially entities eager to curtail financial setbacks from short-term customers, is the primary target audience for this study. The central question is: Can we discern specific patterns or trends leading to customer churn? Through this endeavor, we aim to discern key factors swaying customer decisions to discontinue their plans. Based on these findings, we seek to provide strategic recommendations to SyriaTel to bolster customer retention, suggesting potential campaigns or incentives to motivate customers to maintain or even prolong their association with the company.

### The Data

The data used was downlaoded from kaggle

https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset

#### Methods

* Loaded the data using python modules to read the data
* Data Understanding and Cleaning
* Data visualization for insights 
* SMOTE
* Logistic Regression Classifier
* Optimizing Logistic Regression with GridSearchCV
* Random Forest Classification Algorithm.
 
#### Results





## Conclusions
* The Random Forest Classifier, excluding location data, was chosen as the final model due to its capability to maximize recall in predicting customer churn.
  
* A significant 42% of SyriaTel's subscribers on the International Plan terminated their contracts, signaling dissatisfaction with international offerings.
  
* Existing data suggests that a promotional campaign was active during the studied period, inferred from the total charges distribution and account tenure of churned users.
  
* The frequency of customer service calls is a paramount determinant of customer satisfaction. Multiple calls from a single customer within a billing cycle indicate dissatisfaction.


## Recommendations

* Reevaluate the International Plan:
 Offer enhanced discounts for international calls to subscribers, aiming to improve satisfaction and retain customers.

* Continue Marketing Efforts:
   - Launch a trial voicemail package for high-risk customers.
   - Provide monthly charge discounts to high-risk customers, emphasizing the significant role of the overall charge in customer decisions.
  - Introduce loyalty incentives for long standing customers to counteract competitors' attractive deals.
*  Enhance Customer Service Quality:
   - Train agents to reduce the frequency of customer calls and address concerns effectively.
   - Introduce diverse account management platforms, such as mobile, online, and automated telephonic services, to foster self-service and reduce dependency on service staff.
     
 * Implement and Evaluate:
Roll out the suggested promotional campaigns and service improvements. Post-implementation, conduct an assessment to measure the impact of these initiatives, validating the efficacy of the strategies in line with the model's predictions.


