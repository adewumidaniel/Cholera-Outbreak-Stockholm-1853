# Cholera Outbreak, Stockholm, 1853

### Project Overview

The data is collected from hand-written church records. The church was responsible for all population 
registration until around 1870. Only death records have been analyzed. Since Cholera has around 40% CFR we 
can assume a larger number of affected but surviving individuals and its to analyze the speed of a cholera pandemic in the 19th 
century in an urban environment with very rudimentary sanitation, and related traumatic effects on society 
and individuals


![image](https://github.com/user-attachments/assets/8b0f5aea-2946-4236-aa3a-b92080decbea)





### Data Sources

- All data can be found at the National Archive of Sweden. See https://sok.riksarkivet.se/digitala forskarsalen (press "Other languages" for an English version).
- Another important source for further analysis is "Sundhets-collegii underdåniga berättele om 
Kolerafarsoten i Sverge, 1853" which is a broad overview of the epidemic situation in all of Sweden. 
This contemporary report can be found at Statistics Sweden (SCB) : See this link.

### Tools 

- Power Query - Data Cleaning
- Power BI- Data Analysis
- Power BI - Create Report

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following task:

1. Loading data on Power query
2. Inspection and aligning 
3. Data cleaning and formatting
4. Loading data for Analyzing
5. Create new measures 

### Exploratory Data Analysis

EDA involved exploring the Cholera Outbreak, Stockholm, 1853 Data to answer key question such as:

- What is the total death rate by age rate d
- What is the total death rate by month
- What is the percentage date rate by sex
- What is the death rate by sex and month
- What is the percentage baseline by ISO_3166_2
- What is the total death rate by profession
- What is the total death rate


### Data Analysis

Include some interesting formula worked with

```
 POWER BI
- No Of Profrofession = DISTINCTCOUNT('cholera-catarina-1853'[ Profession])
- Total Death = COUNT('cholera-catarina-1853'[ Name])

```

### Results/Findings

The analysis results are summarized as follow:
1. The outbreak recorded highest number of death in the month of September 
2. Age range between 41-50years were most affected in terms of death follow by 1-10 years of age
3. Women are the most affected in terms of death rate 
 

### Recommendation

Based on the analysis, we recommend the following actions:
Vaccine should be in place to fight the outbreak 

### Limitation

The dataset did not provide accurate number of population of the city we are considering 


### References

1. https://sok.riksarkivet.se/bildvisning/C0055812_00226 
2. https://en.wikipedia.org/wiki/1853_Stockholm_cholera_outbrea
