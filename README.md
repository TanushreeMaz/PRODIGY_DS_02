<p align="center">
  <img src="images/Titanic.jpg" width="100%">
</p>

# Titanic Survival Analysis 

An exploratory data analysis project investigating the factors that influenced passenger survival during the RMS Titanic disaster. The analysis combines Python-based data exploration and Power BI dashboarding to uncover demographic, socioeconomic, and behavioral patterns associated with survival outcomes.

The project focuses on transforming raw passenger records into meaningful insights through data cleaning, feature engineering, statistical analysis, and interactive visual storytelling.


# Project Overview

The Titanic disaster remains one of the most studied historical datasets in data science. This project analyzes 891 passenger records to answer key questions:

• Who had the highest chance of survival?              

• Did gender influence survival outcomes?       

• How important was passenger class?       

• Did age, fare, family size, or embarkation port affect survival?           

• What passenger groups were most vulnerable?


# Python Analysis

The dataset was processed and analyzed using Python through data cleaning, missing value treatment, feature engineering, and exploratory data analysis. New features such as Age Group, Family Group, Family Size, and Passenger Title were created to better understand passenger behavior and survival patterns. Statistical analysis and visualizations were used to uncover relationships between survival and demographic factors.

## Data Preparation

• Loaded and explored the Titanic dataset                       

• Examined data types, dataset structure, and summary statistics              

• Identified missing values and duplicate records                    

• Treated missing values in Age, Embarked, and Cabin-related fields             


## Data Cleaning

• Handled null values using appropriate imputation techniques                                      

• Verified data consistency across key variables                   

• Removed unnecessary columns and standardized categorical values                 


## Feature Engineering

Several new variables were created to improve analysis:

• Family Size                         

• Family Group (Solo, Small Family, Large Family)

• Age Group (Child, Teenager, Adult, Senior)                              

• Passenger Title extracted from passenger names                            

• Fare Groups for socioeconomic segmentation                    


## Exploratory Data Analysis

### Target Variable Distribution (Univariate Analysis)

• Survival distribution              

<img width="1155" height="669" alt="image" src="https://github.com/user-attachments/assets/7c501a69-4a0d-4a6d-9dd0-cd3843f28fa0" />


### Categorical Relationships with Survival (Bivariate Analysis)

• Survival by Passenger Titles                      

• Passenger Distribution by Family Group


### Continuous Variables (Age and Family Size)                               

• Age Distribution

<img width="1040" height="681" alt="image" src="https://github.com/user-attachments/assets/06e8768a-9190-42e6-8b3f-806deb288965" />


• Fare Distribution

<img width="1038" height="683" alt="image" src="https://github.com/user-attachments/assets/d8089397-fd44-4e7b-bb7d-e2dfc9d4b77f" />


### Correlation Heatmap

<img width="1036" height="774" alt="image" src="https://github.com/user-attachments/assets/2fef1787-ad99-4e86-8c16-0b43c3654a9c" />


### Distribution & Outlier Detection ('Fare')

<img width="993" height="531" alt="image" src="https://github.com/user-attachments/assets/f1215a9e-eff6-4c4f-9462-bdd036093e86" />



# Power BI Dashboard

Insights from the Python analysis were transformed into an interactive Power BI dashboard focused on passenger demographics, survival trends, socioeconomic factors, family structures, fare groups, and embarkation patterns. Custom tooltips, storytelling visuals, and thematic design elements were implemented to improve insight exploration and user experience.

The analysis focuses on answering key questions:

• Who had the highest chance of survival?

• Did gender influence survival outcomes?

• How important was passenger class?

• Did age, fare, family size, or embarkation port affect survival?

• What passenger groups were most vulnerable?



# Dashboard -- Power BI Dashboard

## Who Was Onboard ?

• Passenger Class Analysis            

• Gender Distribution          

• Age Distribution              

• Embarkation Port Breakdown                           


## Who Had the Best Chance ?

• Survival Rate by Gender & Passenger Class                

• Family Size vs Survival Rate                  


## What Influenced Survival ?

•	Survival Rate by Passenger Title                       

•	Age Group Survival Outcomes               

•	Survival Rate by Fare Group                  


# Dashboard Preview

<img width="1413" height="793" alt="image" src="https://github.com/user-attachments/assets/eefd9595-4f7d-445d-9524-23d006661eba" />

# Key Metrics

| Metric | Value |
|----------|----------|
| Total Passengers | 891 |
| Total Survivors | 342 |
| Total Casualties | 549 |
| Overall Survival Rate | 38.4% |
| Female Survival Rate | 74.2% |
| Male Survival Rate | 18.9% |
| First Class Survival Rate | 63.0% |
| Third Class Survival Rate | 24.2% |
| Small Family Survival Rate | 57.9% |
| Highest Fare Group Survival Rate | 74.0% |


 






















