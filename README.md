# US Births (2016-2021) Analysis
![](images/Child_Birth_image.jpg)
<br />

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Tools Used](#tools-used)
- [Visualization in Power BI](#visualization-in-power-bi)
- [Project Analysis](#project-analysis)
- [Visuals in Power BI Report](#visuals-in-power-bi-report)
- [Recommendations on Improving the Health and Wellbeing of Mother and Child during Child Birth:](#recommendations-on-improving-the-health-and-wellbeing-of-mother-and-child-during-child-birth)
<br />


## Project Overview

### Introduction:
Analysis: Births in the US by Year, State and Education Level of the Mother: 2016-2021 The present project aims to conduct a trend analysis of births in the United States from 2016 to 2021 with regard to variability: mother's educational level, age, geographic location at the state level, birth rates, and changes over a specified period of time.It is in these dimensions that this project seeks to make a contribution through its possible correlations, disparities, and implications for public health policies and interventions.

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
<br />
<br />

### Dataset Overview
This is the dataset for birth rates and other associated data for the 50 states and DC during the period of 2016-2021. The Centers for Disease Control and Prevention (CDC) provided the dataset. It contains the number of births, gender, birth weight, state, and the year the birth took place. This dataset places special emphasis on detailed information regarding mothers' educational levels. This dataset will allow one to do such things as analyze birth rates as a function of academic groups and geographic location.

The dataset contains rows viewed as categories defined by state, birth year, gender of the baby, and mother's educational level. Three quantities are given for each category: number of births, mother's average age, and average baby weight. The CDC is sensitive to possibly disclosing personal information, so any category with fewer than ten births is suppressed. Data in this set was originally pulled using CDC's WONDER retrieval tool from the webpage [CDC Natality](https://wonder.cdc.gov/natality-current.html).

This dataset is made up of a single table with 9 columns and 5,496 rows of data, below is the data disctionary as regards the columns in this dataset:
| Table                              | Field                    | Description                            |            
|:-----------------------------------|:------------------------ |:-------------------------------------- |
|us_births_2016_2021.csv             | State                    | This column represents the name of the state where the births occurred. Each entry in this column corresponds to a specific state within the United States    |
|                                    | State Abbreviation       | This column provides the standardized abbreviation for each state. State abbreviations are typically two-letter codes used to uniquely identify each state     |
|                                    | Year                     | This column indicates the year in which the births occurred. Each entry in this column corresponds to a specific calendar year within the specified range         |
|                                    | Gender                   | This column specifies the gender of the newborns. Entries in this column typically include categories such as "Male" and "Female," indicating the gender of the newborns         |
|                                    | Education Level of Mother| This column denotes the educational attainment of the mothers. Entries in this column may include categories such as "Less than high school", "High school graduate", "Some college or associate's degree", "Bachelor's degree or higher", etc., representing different levels of education achieved by the mothers.        |
|                                    | Education Level Code     | This column provides a numerical code corresponding to the educational level of the mothers. Each educational category mentioned in the "Education Level of Mother" column may have a unique numerical code assigned to it for data processing purposes.         |
|                                    | Number of Births         | This column indicates the total number of births that occurred within the specified category. Each entry in this column represents the count of births corresponding to the particular combination of state, year, gender, and education level of the mother.        |
|                                    | Average Age of Mother (years)| This column provides the average age of the mothers at the time of giving birth. Entries in this column represent the mean age of mothers within each category, calculated in years.        |
|                                    | Average Birth Weight (g) | This column denotes the average birth weight of newborn babies. Entries in this column represent the mean weight of newborns within each category, typically measured in grams.         |
<br />
<br />

### Skills Utilized
1. Data Cleaning
2. Data Visualiziation
3. Descriptive Analytics
4. Analytical Thinking and Problem Solving
5. Communication and Reporting
<br />

### Tools Used
1. Power Query Editor
    - Was used to:
        1. Clean,
        2. Transform the dataset for this analysis.
           
2. Power BI (Was used to create reports and dashboard for this analysis)
    - The following Power BI Features were incorporated:
        1. DAX
        2. Quick Measures
        3. Page Navigation
        4. Filters
        5. Tooltips
        6. Buttons
<br />

### Data Cleaning, Transformation and Loading using MS Sql Server:
- There was just a cleaning and transformation done here by correcting some text. The dataset came mostly cleaned, i also made sure that the data types of the fields are of the right types and that fields all reported 100% valid for the column quality.


**Power Query View**

Power Query Screenshot                                                             |                                
:---------------------------------------------------------------------------------:|
![](images/Power_Query_Screenshort.png)

You can access the complete Power BI project document [here](US%20BIRTHS%20ANALYSIS%20(2016%20-%202021).pbix).
<br />
<br />

## Data Modelling
No data modelling was required since we needed just a table for the analysis.
<br />
<br />

## Visualization in Power BI:
#### Birth Stats
![](images/US_Births_(2016-2021)_Analysis_Dashboard1.jpg)

#### Mother & Baby Trends
![](images/US_Births_(2016-2021)_Analysis_Dashboard2.jpg)
<br />
<br />

### Project Analysis:
From my analysis, i made the following Key findings below:
- The Total Number of New Births is __22,618,480.__
- Total Number of New Births (Male) __11,568,166.__
- Total Number of New Births (Female) __11,050,314.__
- Total Number of Birth States In This Analysis __51.__
- Total Average Age of Mothers __30.__
- Average Birth Weight __3,251 (g).__
<br />
<br />

- <img src="images/Top10_States_By_No_of_Births.jpg" width="300">

- **The Top 10 States By Number of Births:**
- In this analysis, our first insight would be the top 10 states by number of births; below are the insights I derived from the data.
- __California Leads in Total Number of Births:__ California topped the system birth count among the states, with 2,702,751 births. That is a huge share of the total number of births in the United States for this period.                                                                                                                                                   - - - __Texas and New York Almost at Par:__ Texas and New York land at the second and third ranks as far as total number of births are concerned, numbering 2,278,104 and 1,331,877. In general, they are high contributors to the national birth rate.                                                                                                                          - __Florida and Illinois in the Top Five:__ Florida and Illinois take the fourth and fifth positions subsequently, with 1,316,127 and 854, 265 births respectively. The population was very big, and birth rates were really high in these two.                                                                                                                                 - __High Birth Figures Maintained:__ Pennsylvania, Ohio, and Georgia were the sixth, seventh, and eighth states on the list with 810,372, 803,494, and 758,374 births, respectively. These are the states that normally significantly contribute to the country's overall birth figures.                                                                                      - __North Carolina and Michigan Round Out the Top 10:__ North Carolina and Michigan come in at the final two spots in the top 10, with 715,779 and 651,713 births, respectively. Though both these states fall short in birth count relative to those at the top of the list, they definitely still make up a lot for the national birth rate.
<br />
<br />

- <img src="images/Births_By_Gender_Ratio.jpg" width="250">

- **Births By Gender Ratio:**
- On the analysis of births based on gender ratio, I found that :
- __More Male Births Than Females__: The number of males accounted for in births in this dataset is 6,250,629, about 51.14% of the total. This explains that male birth is slightly more than female birth within this period under study.
- __Female Births Account for 48.86%:__ The number of female births accounted for 5,972,227 births, which shares about 48.86% of the total. Though marginally lower than male births, female births still make up quite a proportion of the overall birth count.
- __Gender Ratios at Birth__: The fraction of male births is only slightly higher than that of female births; this phenomenon is observed in almost all countries of the world. Either way, biological differences, genetic factors, and social influences could all play their roles in the different birth sex ratios.
<br />
<br />

- <img src="images/Births_Trend_By_Year.jpg" width="550">

- **Births Trend By Year (2016-2021):**
- In this analysis, I assessed the births trend between the period 2016-2021. Below are some of the insights I got from it.
- __Gradual Decline of Total Births Over Time:__ According to the data provided, there was a gradual decline in the total births in the United States from 2016 through 2021. In the year 2016, the number of births was 2,142,254, which dropped to 1,965,325 in 2021.
- __Gradual Fall from 2016 to 2020:__ From 2016-2020, there has been a gradual falling off every year for births. The constant fall may be demographic or socio-economic in nature and hence determine the birth rates during this period. The COVID-19 pandemic likely played a role in reducing the birth rates in 2020. Indeed, one would expect it to raise fears concerning economic uncertainty and health issues, as well as disrupt healthcare services and social distancing measures, thus influencing births in the year 2020.
- __Slight Increase in Births from 2020 to 2021:__ From a low of approximately 1,943,917 births in 2020, there is again a slight rise in the number of births to 1,965,325 in 2021. This might point to some form of short-term fluctuation against the downward trend. Such a good number of factors could have contributed to this slight increase in childbirth rates that was witnessed in 2021, including easing pandemic restrictions, pent-up demand for procreation after the easing of the pandemic restrictions, better access to healthcare services, social support networks, among other factors which could have influenced this slight births increase.
<br />
<br />

- <img src="images/Total_Number_Of_Births_By_Educational_Level_of_Mother.jpg" width="550">

- **Number of Births By Educational Level of Mother:**
- This represents the births by educational attainment of mother. The insights I derived include:
- __High Birth Rates of Women with High School or Equivalent Mothers:__ The number of mothers who completed high school or obtained a GED reached the highest quantity of births at 5,775,918 births. This indicates that an extremely large percentage of births are to mothers in the category with education at the high school level and thus is an extremely relevant demographic within childbirth statistics.
- __Substantial Births Among Mothers with Bachelor's Degrees and Some College Credit:__ This category makes up a significant proportion of the total number of births, which are from mothers holding a Bachelor's degree with BA, AB, BS, numbering 4,653,184. Some mothers had some college credit with no degree, contributing 4,425,269 births. Thus, a substantive proportion of the contribution was also from women at the bachelor's and some college levels.
- __Across Mother's Education Groups, Moderate to High Birth Rates:__ The highest rate of births to mothers with master's and associate degrees was moderate. The exact number of births in this category was 2,161,046, where MA, MS, MEng, MEd, MSW, MBA were the highest degrees obtained by the mothers. Another education group at this level reported a moderate rate of births; the highest degree obtained by mothers in this group was an associate degree, with 1,867,700 births. Although certainly smaller at these levels of education than the high school and bachelor's groups in terms of total births, these are still large bases underlying the totals for live births.
- __Lower Birth Counts of Moms with Lower Educational Attainment:__ Relatively lower birth counts were found for the 9th through 12th-grade mothers with no diploma and 8th grade or less. In turn, births by mothers in these respective educational categories totaled 2,086,382 and 708,850. It, therefore, implies that there may be some form of inverse relationship between educational attainment and birth rates wherein the former generally comes with the latter in a negative sense.
- __Impact of Educational Attainment on Family Planning and Childbirth:__ Actually, how education will influence family planning decisions due to its distribution across different educational levels is very complicated. Such things as socioeconomic status, availability, culture, and personal aspiration at different levels of education could all affect when and how many children people have.
<br />
<br />

- <img src="images/Avg_Age_Trend_of_Birthing_Mothers.jpg" width="550">

- **Average Age Trend of Birthing Mothers (2016-2021):**
- This analysis focuses on average age of birthing mothers over specified period revealing trends and shifts in maternal age of number of births of mother. Below are insights derived from data:
- __Gradual Increase in Average Maternal Age Over Time:__ The data shows a consistent upward trend in average age of birthing mothers from 2016 to 2021. In 2016, average maternal age was 29.3 years. This increased steadily to 29.77 years in 2021
- __Significance of Incremental Changes:__ While changes in average maternal age may seem small they reflect meaningful shifts in family planning and demographic trends over time. Even slight increases in average maternal age can have important implications for maternal and child health outcomes as well as for social and economic factors.
- __Factors Driving Increase in Maternal Age:__ Several factors may contribute to trend of increasing maternal age. These include delayed childbearing for career or educational pursuits. Financial stability and personal choice are also significant. Cultural shifts and changes in societal norms influence this phenomenon. Improvements in access to contraception and fertility treatments may also play a role in decision to postpone childbirth
- __Health and Fertility Considerations:__ Advanced maternal age (typically defined as age 35 and older) may present certain health risks for both mothers and babies. These include an increased likelihood of pregnancy complications and chromosomal abnormalities. Monitoring trends in average maternal age is important for healthcare providers. It allows them to anticipate and address unique needs and challenges associated with pregnancies at older ages
<br />
<br />

- <img src="images/Avg_Births_Weight_Trend_of_New_Born_Babies.jpg" width="500">

- **Average Births Weight Trend of New Born Babies (2016-2021):**
- This analysis focuses on the average births weights trend of new born babies over the specified period, in the sense that the following are the insights garnered from the data:
- __Gradual Decline in Average Birth Weight Over Time:__ The data indicates that there is a constant decrease in the average birth weight of newborn babies from 2016 to 2021. In 2016, it was 3,261.68 grams, which were reduced to 3,239.15 grams in 2021.
- __Significance of the Decline:__ It may seem the changes in average birth weight are minuscule, losing sight of the fact that even a small drop may result in health and conduct implications in infancy. The keeping of a record of the changes in the average birth weight of the neonates is imperative for identifying the probable alterations in maternal and offspring health results and hence while reflecting on the public health interventions.
- __Possible Factors Contributing to Decrease in Birth Weight:__ A number of factors could be responsible for the decrease of birth weight observed over time. Those can be some health hazardous practices a mother may decide to adopt, for example, a pregnant woman can smoke or/and use some drug or toxics. Also, some populations may have an increase in the proportion of expectant women who are older or who have pre-existing health conditions.
- __Health Implications for Newborns:__ Infants with lower birth weights are more likely to have various health problems, such as respiratory distress syndrome, hypoglycemia, and developmental delays. It is through monitoring the average birth weight of the infants that medical professionals can be able to tell which infants are at risk and hence take the right course of action when it comes to their health and development.

<br />
<br />

- <img src="images/Births_Spread_Across_States.jpg" width="550">

- **Geospatial Map of Births Across States in the US (2016-2021):**
- __Visualizing the Distribution of Births:__ A geospatial map is used to represent the dispersion of the birth rates across the states of the United States. It is the geographical representation of each state, which enables one to visually make a distinction between those states with a high or low birth rate.
- __Identification of Regional Disparities:__ From the geospatial map, one can identify the regional disparities pertaining to birth rate; some states have higher birth rates compared to others. In general, variation in birth rates could be due to various reasons such as population density, socio-economic status, access to health facilities, and cultural influences.
- __Demographic Trends Insights:__ Information from the distribution of births across states gives demographic trends and patterns. For instance, the high birth rate states will have a young population with high fertility, while those states with low birth rates will be characterized by aging populations or low fertility.
- __Informing Public Health Interventions:__ The geospatial map would inform public health interventions aimed to improve maternal and child health outcomes. For instance, increased rates of births in particular regions would identify the targeting efforts to be made in improving access to prenatal care access to maternal health services, and infant healthcare resources.
<br />
<br />

## Visuals in Power BI Service:
You can view and interact with this dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiYzM1NzJjZWEtZTc1Zi00NjNhLTk1NzMtMGEwODQ1ZjRlYzdhIiwidCI6IjdlYzI5NjU5LTNjZjItNGYzZi1hYmIzLWE3MjJlZGY3ZmYyZCJ9).
<br />
<br />
<br />

## Recommendations on Improving the Health and Wellbeing of Mother and Child during Child Birth:
- __Access to Antenatal Care:__ Health Institutions should ensure access by all to quality ANC services, including regular checkups and screening, and education on healthy behaviors during pregnancy.
- __Education and Support/Bibliography:__ Full prenatal education regarding nutrition, prenatal vitamins, exercise, childbirth preparation, and other subjects should be provided. In this way, they can also counsel and support mental health and emotional well-being during pregnancy and postpartum.
- They would encourage access to healthy foodstuffs and folic acid supplements for promoting health among mothers and fetuses. It would entail giving nutrition advice, more so to pregnant women who are most vulnerable to malnutrition or inadequate dietary intake.
- __Continuity of Care:__ Health institutions will ensure that there is a continuum of care throughout pregnancy, at birth time, and after birth by enabling easy communication and coordination among providers.
- __Access to Skilled Birth Attendants:__ They can increase access to skilled birth attendants, midwives, obstetricians, or other health professionals for a safe and supportive childbirth experience.
- __Facility-Based Childbirth Services:__ They can promote facility-based childbirth services that have appropriate infrastructures, equipment, and staff to ensure a safe and hygienic delivery environment.
- __Postpartum Support and Follow-up:__ They can initiate or improve postpartum care protocols that track the health status of mothers and newborns after childbirth, which includes monitoring for complications, assessment, assistance with breastfeeding, and mental health screening. It may further include lactation counseling and referrals to community resources that address the physical, emotional, and social needs of new mothers and their families.
<br />
<br />

## Thank You For Following Through!
![](images/Thank_you.jpg)
