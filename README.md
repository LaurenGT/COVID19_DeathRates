# project1
Project Title: 
The Relationship between Emergency Room Access and COVID-19 Mortality Rates

Team Members:
Rylee Ahnen
Serena Baker
Sharath Menon
Lauren Toothaker

Project Description/Outline:

We will analyze state-level data to explore the relationship between emergency room availability (Measured as a count of emegency departments per state by population), poverty rates, and county COVID-19 mortality rates.

Should time permit, we also plan to add additional layers of data to our analysis - potentially race and ethnicity demographic data, and educational attainment data.

Research Questions to Answer:
When adjusted on a per-capita basis, does an increased number of emergency rooms in a county result in lower mortality rates from COVID-19?

If this negative relationship does exist, is the correlation strong enough to withstand the impact of other factors that are believed to create a higher risk of COVID-19 such as poverty, race, or education level?

Datasets to Use:
United States Census Bureau: https://www.census.gov/data/developers.html

The Atlantic's COVID-19 Tracking Project: https://covidtracking.com/data/api

Center's for Disease Control and Prevention: https://www.cdc.gov/apis.html

Rough Breakdown of Tasks:

*Each group member should search for additional datasets that could be of use for our project
*At our next meeting group members will be assigned a dataset to clean and create a useful dataframe from
*At our next meeting the group will decide which data is most approporate for use in our project

*LT will act as the adminstrator of the GitHub repo
*RA will serve as the project manager

*As a team we will clean the initial COVID and Census data, creating a plan for how to merge those two datasets
*TBD deeper dives into addtional questions (poverty impact, racial impact, etc)
*TBD presentation creation and analysis


## Final Write-Up
Q1: Is there a relationship between Emergency department (ED) concentration and COVID-19 death rates?

A: The r-value of the Covid-19 death rates and EDs per capita suggests a weak inverse relationship. The calculated r-value is -0.46.

![COVID-19 Deaths and EDs](ED_image)
[ED_image]: http://localhost:8888/view/data_analysis/COVID-19%20Death%20Rate%20and%20Emergency%20Departments%20Per%20Capita.png


Q2: Is the Emergency Department and COVID-19 relationship stronger than poverty rate?
A: With an r-value of -0.5, there is a weak inverse relationship between COVID-19 death rates and poverty rates. This is a 0.41 difference which suggests it is not a stronger relationship than to Emergency Department concentration.

Q3: Is the Emergency Department and COVID-19 relationship stronger than median age?
A: An r-value of 0.29 suggests a weak relationship between COVID-19 death rates and median age. This suggesting a possible stronger correlation although still weak.



