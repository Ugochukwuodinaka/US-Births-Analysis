# US Births (2016-2021) Analysis
![](images/Child_Birth_image.jpg)


## Project Overview

### Introduction:
This is an analysis on Births in the US by year, state, and education level of the mother: 2016-2021. This project aims to analyze the trends and patterns of births in the United States from 2016 to 2021, focusing on the demographic variables of the mother's education level, age, geographical location (state), birth rates, and temporal changes over the specified period. By exploring these dimensions, the project seeks to provide insights into potential correlations, disparities, and implications for public health policies and interventions.


### Objectives:
- Examine variations in birth rates across different states over the specified period by looking at the top 10 states by number of births.
- Examine the births ratio by gender
- Analyze the overall trend of births in the US from 2016 to 2021.
- Investigate the relationship between the education level of mothers and birth rates by examining the total number of births by the educational level of mothers.
- Analyze the average age trend of birthing mothers in the US from 2016 to 2021.
- Analyze the average weight trend of new born babies in the US between 2016 and 2021.
- Evaluate the birth spread of new born babies across states with the aid of a geospatial map

### Expected Outcomes:
- Identification of geographic variations in birth rates across the top 10 states by number of births.
- Determination of gender distribution among newborns, highlighting any disparities in birth ratios.
- Understanding of the overall trend of births in the US over the specified period, indicating whether birth rates have increased, decreased, or remained stable.
- Uncovering potential correlations between maternal education level and birth rates through analysis of total births across different educational groups.
- Analysis of the average age of birthing mothers over the specified period, revealing trends and shifts in maternal age.
- Examination of the average weight trend of newborn babies between 2016 and 2021, providing insights into potential health implications.
- Evaluation of birth spread across states using geospatial mapping, identifying regional disparities and informing resource allocation.


### Dataset Overview
This dataset provides birth rates and related data across the 50 states and DC from 2016 to 2021. The data was sourced from the Centers for Disease Control and Prevention (CDC) and includes detailed information such as number of births, gender, birth weight, state, and year of the delivery. A particular emphasis is given to detailed information on the mother's educational level. With this dataset, one can, for example, examine trends and patterns in birth rates across different academic groups and geographic locations.

Each row in the dataset is considered a category defined by the state, birth year, baby's gender, and educational level of the mother. Three quantities are given for each category: number of births, mother's average age, and average baby weight. The CDC is sensitive to potentially disclosing personal information, so any category with less than ten births is suppressed. The data in this dataset was orinally obtained using CDC's WONDER retrieval tool on the [CDC Natality](https://wonder.cdc.gov/natality-current.html) page.

This dataset is made up of a single table with 9 columns and 5,496 rows of data, below is the information abount the columns in this dataset:
- __State:__ This column represents the name of the state where the births occurred. Each entry in this column corresponds to a specific state within the United States.
- __State Abbreviation:__ This column provides the standardized abbreviation for each state. State abbreviations are typically two-letter codes used to uniquely identify each state.
- __Year:__ This column indicates the year in which the births occurred. Each entry in this column corresponds to a specific calendar year within the specified range.
- __Gender:__ This column specifies the gender of the newborns. Entries in this column typically include categories such as "Male" and "Female," indicating the gender of the newborns.
- __Education Level of Mother:__ This column denotes the educational attainment of the mothers. Entries in this column may include categories such as "Less than high school", "High school graduate", "Some college or associate's degree", "Bachelor's degree or higher", etc., representing different levels of education achieved by the mothers.
- __Education Level Code:__ This column provides a numerical code corresponding to the educational level of the mothers. Each educational category mentioned in the "Education Level of Mother" column may have a unique numerical code assigned to it for data processing purposes.
- __Number of Births:__ This column indicates the total number of births that occurred within the specified category. Each entry in this column represents the count of births corresponding to the particular combination of state, year, gender, and education level of the mother.
- __Average Age of Mother (years):__ This column provides the average age of the mothers at the time of giving birth. Entries in this column represent the mean age of mothers within each category, calculated in years.
- __Average Birth Weight (g):__ This column denotes the average birth weight of newborn babies. Entries in this column represent the mean weight of newborns within each category, typically measured in grams.


### Skills Utilized
1. Data Cleaning
2. Data Visualiziation
3. Descriptive Analytics
4. Critical Thinking and Problem Solving
5. Communication and Reporting


### Tools Used
1. Power Query Editor
    - Was used to:
        1. Extract,
        2. Transform,
        4. Load all the datasets for this analysis.
           
2. Power BI (Was used to create reports and dashboard for this analysis)
    - The following Power BI Features were incorporated:
        1. DAX
        2. Quick Measures
        3. Page Navigation
        4. Filters
        5. Tooltips
        6. Buttons


### Data Cleaning, Transformation and Loading using MS Sql Server:
- There was just a some cleaning done here by correcting some text, but no serious data cleaning or transformastion was carried out. The dataset came mostly cleaned, i just made sure that the data types of the fields are of the right types and that fields all reported 100% valid for the column quality.


**Power Query View**

Power Query Screenshot                                                             |                                
:---------------------------------------------------------------------------------:|
![](images/Power_Query_Editor_Screenshot.png)

You can access the complete Power BI project document [here](STUDENTS%20MENTAL%20HEALTH%20ANALYSIS.pbix).


## Data Modelling
No data modelling was required since we needed just a table for the analysis.
