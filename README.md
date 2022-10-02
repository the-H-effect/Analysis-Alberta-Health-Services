# Analysis of Alberta Health Services
### A Data Visualization Project using PowerBI

## Business Understanding: Introduction
Datasets used can be found here and here. As with any data analytics or business intelligence project, a good business understanding of the industry domain is crucial before embarking on any Data Understanding, Preparation, Modeling and Evaluation steps.

In Understanding the Datasets and relationships, I identified the following main concepts:
* There are 5 zones under Alberta Health Services AHS; **South (Zone 1), Calgary (Zone 2), Central (Zone 3), Edmonton (Zone 4) and North (Zone 5).**

* Each AHS Zone is made up of **Primary Care Networks (PCN)**, and each PCN has a number of Primary Care providers.

* AHS has up to **30 Physician Specialty** in addition to General Physicians/ Family Physicians.

After a comprehensive business/Data Understanding, followed by data cleaning and manipulation, I created Visualizations using PowerBI. The 3 PowerBI dashboards created explores 3 main teams; the Primary Care Network (PCN) under each AHS Zone, the Top 5 Cause of Death in Alberta, and the 20 plus different Physcian Specialty.
*For each PowerBI dashboard, filters can be used to select PCN, the Year, or the Physcian specialty of interest.* 

## Insight 1: Primary Care Network (PCN)
### AHS Zone: Calgary
1. Although Calgary West Central PCN has the highest number of Primary Care providers (4,800), Calgary Foothills has the highest total number of patients enrolled, with the numbers standing at a little above 4 million patients. 
2. Calgary Foothills received highest total payments made to a PCN at $0.23 billion. 
3. For AHS Zone 2 (Calgary), the total Number of patients enrolled in the PCNs has been on a steady increase from 2012 till 2021, and although payments received by the PCNs initially showed same increase, there is a noticeable dip between 2015 and 2016, where payments reduced even though there was continous increase in patients enrolled.
![PCN](https://user-images.githubusercontent.com/114383545/193398569-f230840b-6a4f-4681-b2e9-bd7a92f208f9.jpg)


### AHS Zone: Edmonton
1. Edmonton PCNs experienced same drop in payments from 2016 to 2017, even though patient enrolled was on the increase.
2. Edmonton Southside PCN received highest total payments at $163 million, and patient enrolled stood at over 2.8 million.
![PCN edmonton](https://user-images.githubusercontent.com/114383545/193398660-43b3a44a-494f-4a1b-812f-b54f973c9939.jpg)


### AHS Zone: Central
1. Under Central's PCN, Red Deer has the highest number of Primary Care providers, the highest number of patients enrolled, and received maximum payments at 987, 1.3 million, and $75 million respectively.
2. There is noticeable reduction in payments received from 2015 to 2017, before increasing in 2018.
![PCN central](https://user-images.githubusercontent.com/114383545/193398722-147220fb-ed2f-4f72-ab93-c71bef94ec55.jpg)


### AHS Zone: North
1. Grande Prairie PCN has total 765K patients enrolled and received $41 million, the highest amongst the North Zone PCNs.
2. Although McLeod River has second highest Primary Care providers, they received third largest payment ($19 million) after Wood Buffalo ($40 million).
3. Wood Buffalo's patient enrolled is almost double that of McLeod River, despite having fewer number of Primary Care providers. Either there is overcrowding in Wood Buffalo's PCNs, in the sense that Services provided (Primary Care providers) are not commensurate to the need (number of patients enrolled), or McLeod River has way too much Primary Care  providers for the population. Further investigation is necessary to find a solution either way.
![PCN North](https://user-images.githubusercontent.com/114383545/193398748-c53cceb9-8f42-48db-bd11-aac130dfb86c.jpg)


### AHS Zone: South
AHS Zone South is made up of 2 PCN, Chinook and Palliser, and comparisons are fairly easy to make. The Chinook PCN is leading Palliser in all the indicators (number of Primary Care providers, Patients enrolled, and Payments received).
![PCN South](https://user-images.githubusercontent.com/114383545/193398777-51af9cc6-4e18-4807-9fda-17ca17eff5ff.jpg)


## Insight 2: Top 5 Cause of Death
### Historical 20-Years
1. Based on a 20-Year historic data (2001 - 2021), the Top leading cause of death in Alberta include organic dementia (brain/Cerebral dysfunction), acute myocardial infarction (heart attack) and chronic obstructive pulmonary disease COPD (long-term lung diseases).
2. One health indicator; BMI, showed that Males had a higher prevalence of over weight and obesity, compared to females.
3. Other health indicators showed that females have higher prevalence to back problems, arthritis, high blood pressure, migraine, asthma, bowel disorder, urinary incontinence, ulcers and cancers, than males.
4. Heart disease is the only health indicator where males showed a higher prevalence than females.
5. Insight from the table in the visual, showed that some AHS zones have higher prevalence to health disease and conditions than other Zones. 
6. The North and South Zones showed very high prevalence to heart disease, doubling that of Calgary and Edmonton Zones, and more than 10 times the prevalence in Central Zone. This Insight can be valuable in planning preventive measures aimed at addressing this health challenge in that specific AHS Zone.
![Top disease and death cause](https://user-images.githubusercontent.com/114383545/193398803-18d5b3b8-ee68-4db1-a75f-8d6f3d169ca1.jpg)


### Year 2021
I was surprised to see that for the Year 2021, Organic dementia was a higher contributor to 2021 deaths in Alberta (19%), than the Covid-19 virus (17%). To be honest I had no idea prior to this analysis what Organic dementia was, and this surprising insight that it was a leading cause of death spurred me into doing some research on this disease.
![Top death cause 2021](https://user-images.githubusercontent.com/114383545/193398835-2bc1cd22-bca6-4129-8e3a-2d6032d2a2fd.jpg)


## Insight 3: Physician Specialty 
### Physician Specialty
There are 30 Physcian Specialty under AHS, from Anaesthesiology to Urology as given by the table in the right hand side of the visual.
![Physician Specialty](https://user-images.githubusercontent.com/114383545/193398855-5d821a65-2994-4912-9c9c-3bd054a84674.jpg)


### Physician Specialty (General Physician GP)
1. Cumulative Total GP in Alberta stands at over 60,000 for a 10 Year data history from 2011 to 2021.
2. Edmonton and Calgary Zones accounts for more than 2/3 of the total GP in Alberta.
3. For the last 3 years, AHS has approximately 7,000 General and Family physicians.
![Physician Specialty GP](https://user-images.githubusercontent.com/114383545/193398914-af4d76f9-f350-46b1-9ea8-2c1f8c408dd2.jpg)

### Physician Specialty (Internal Medicine)
1. Internal Medicine Specialty is made up of 6 sub categories from cardiology to infectious diseases.
2. AHS has a strength of 1,000 Internal Medicine Physician's for the last 3 years (2019 - 2021)
![Physician Specialty INTERNAL MEDICINE](https://user-images.githubusercontent.com/114383545/193398930-9c119246-bf91-4def-be4a-68a357c61561.jpg)


### Physician Specialty (Paediatrics)
1. For the last 5 years, Calgary Zone has had more than 50% of Paediatricians in AHS. In 2021, the number stood at 254, compared to all other AHS Zones with 206 Paediatrics Physician.
2. Cumulative Total of Paediatrics Physician for the year 2011 - 2021 is 4,702.
![Physician Specialty Paediatrics](https://user-images.githubusercontent.com/114383545/193398945-defe94c2-ec54-46c3-9685-70bf1945325e.jpg)


### Physician Specialty (Psychiatry)
1. For Psychiatrist in AHS, Calgary and Edmonton Zones have a combined strength of 77%.
![Physician Specialty Psychiatry](https://user-images.githubusercontent.com/114383545/193398965-dd2211c7-e028-4fb2-9022-5f707250a54a.jpg)


## Recommendation & Conclusion 
Valuable Insights from the analysis can be used to check that number of Primary Care providers are commensurate to the number of patients enrolled to prevent overcrowding of facilities, and ensure that patients receive the right amount of care at the right time.

AHS can use data analytics insights to plan preventive measures and target specific genders and/or AHS Zones that are prone to certain disease conditions and health challenges.
