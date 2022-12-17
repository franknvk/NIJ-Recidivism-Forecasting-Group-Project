# **Project 5: **
## **DSI 1010 - Debbie Sim, Frank Novak, Preet Sekhon**
---

## Repo Folder Organization
|Folder|Type|Description|
|---|---|---|
|cleaned_datasets|folder|contains the cleaned datasets post data cleaning, post pre-processing, & for modeling |
|datasets|folder|contains raw datasets|
|pickles|folder|pickles of models ran during project| 
|plots|folder|exported graphs from jupyter lab as png files|
|scratch|folder|contains scratch work|
|00_Project3-Pushshift|jupyter notebook|contains jupyter lab notebook with code to scrape subreddits|
|01_Project3-Data Cleaning|jupyter notebook|contains jupyter lab notebook with pre-cleaning of raw datasets|
|02_Project3-EDA|jupyter notebook|contains jupyter lab notebook with EDA|
|03_Sentiment Analysis|jupyter notebook|contains jupyter lab notebook with sentiment analysis scores & exploration|
|04_Pre-Process & Feature Engineering|jupyter notebook|contains jupyter lab notebook with pre-processing & feature engineering|
|05_Modeling|jupyter notebook|contains jupyter lab notebook with modeling & final conclusions|
|06_Data Visualization|jupyter notebook|contains jupyter lab notebook with final data visualization plots|
|README-DebbieSim-Project2.md|README|Debbie created README file for project 2|
|GADSI1010_DebbieSim_Project3.pdf|pdf|pdf of presentation slides|
|README.md|README|Original unedited README file for project 2|


## Problem Statement
TEXT TEXT TEXT

## Excecutive Summary
TEXT TEXT TEXT


## Background Information
**McKinsey - 'Taking a good look at the beauty industry'** ([*source*](https://www.mckinsey.com/industries/retail/our-insights/taking-a-good-look-at-the-beauty-industry))
- Sophie Marchessou: It’s important to define what it is, as a retailer or beauty brand, that you want to stand for and what consumer experience you want to provide—and stick to it. The answer doesn’t need to be the same for everyone. There are, depending on your customer targets, features that might be more or less relevant, so it’s not about going after the gimmicky things and having technology enhancements in the store just for the sake of having them. It’s about figuring out, in the consumer journey, what are potential pain points? And how do you then say, “Those three things I’ll prioritize. That will be how I deliver this omnichannel experience.” Then, make sure you trickle that down through the organization so that not just your digital team but also your store team is aware of the experience you want to provide, and explain why it matters.


## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|object|LAUSD_act2019_final|The academic year corresponding to dataset| 
|cds|float|LAUSD_act2019_final|A unique 14-digit code corresponding to the school within California composed of county code, district code, and school code |
|ccode|float|LAUSD_act2019_final|A 2-digit code corresponding to county| 
|cdcode|float|LAUSD_act2019_final|A 5-digit code corresponding to school district| 
|scode|float|LAUSD_act2019_final|A 7-digit code corresponding to the school| 
|rtype|object|LAUSD_act2019_final|record type indicates whether the row of data corresponds to school, district, or state (S=School Record D=District/LEA Record X=State Record)|


## Summary of Analysis

**Model Evaluation**
TEXT TEXT TEXT TEXT TEXT TEXT

*LogisticRegression with/without BayesSearchCV*
![alt text](plots/eval-bs-logreg.png)

*RandomForestClassifier with BayesSearchCV*
![alt text](plots/eval-bs-rf.png)

*PCA and Logistic Regression with GridSearchCV*
![alt text](plots/eval-gspca2.png)

**EDA Learnings**
- TEXT TEXT
![alt text](plots/word-count.png)

- TEXT TEXT

- TEXT TEXT



## Conclusions & Recommendations
- TEXT TEXT TEXT
![alt text](topwords-skincareaddict/topwords.png)
- TEXT TEXT TEXT
![alt text](topwords-asianbeauty/topwords.png)
-