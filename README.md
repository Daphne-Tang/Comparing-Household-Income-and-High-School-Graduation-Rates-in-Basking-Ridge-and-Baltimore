# Comparing Household Income and High School Graduation Rates in Basking-Ridge and Baltimore By Race
## Background
This analyzes the relationship betwen Basking Ridge, New Jersey's household income to Somerset County, New Jersey's high school graduation rates by race. I replicated this city-to-county level analysis for Baltimore City, Maryland. 

## Business Question
How do high school graduation rates impact household income in both Basking Ridge and Baltimore, and what do the discrepancies between different races show about social mobility in both cities?  

## Data Question - Open Data
This analysis uses data from Opportunity Insights, which is a research team based at Harvard University that uses big data to solve economic and social problems. The [Opportunity Atlas](https://www.opportunityatlas.org) is a collaboration between Opportunity Insights and the U.S. Census Bureau to analayze social mobility in each Census tract, which are geographic units with around 4,000 people. The study tracks the average outcomes of 20 million children born in 1978 and 1983 based on where they grew up. 
- [Baltimore City HS Graduation Rate All Races Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_HS_Graduation_Rate_All_Races_Data.xlsx)
- [Baltimore City HS Graduation Rate Asians Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_HS_Graduation_Rate_Asians_Data.xlsx)
- [Baltimore City HS Graduation Rate Blacks Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_HS_Graduation_Rate_Blacks_Data.xlsx)
- [Baltimore City HS Graduation Rate Hispanics Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_HS_Graduation_Rate_Hispanics_Data.xlsx)
- [Baltimore City HS Graduation Rate Whites Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_HS_Graduation_Rate_Whites_Data.xlsx)
- [Baltimore City Household Income All Races Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_Household_Income_All_Races_Data.xlsx)
- [Baltimore City Household Income Asian Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_Household_Income_Asian_Data.xlsx)
- [Baltimore City Household Income Black Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_Household_Income_Black_Data.xlsx)
- [Baltimore City Household Income Hispanics Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_Household_Income_Hispanics_Data.xlsx)
- [Baltimore City Household Income Whites Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Baltimore_City_Household_Income_Whites_Data.xlsx)
- [Basking Ridge Household Income All Races Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Basking_Ridge_Household_Income_All_Races_Data.xlsx)
- [Basking Ridge Household Income Asians](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Basking_Ridge_Household_Income_Asians_Data.xlsx)
- [Basking Ridge Household Income Blacks Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Basking_Ridge_Household_Income_Blacks_Data.xlsx)
- [Basking Ridge Household Income Hispanics Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Basking_Ridge_Household_Income_Hispanics_Data.xlsx)
- [Basking Ridge Household Income Whites Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Basking_Ridge_Household_Income_Whites_Data.xlsx)
- [Somerset County HS Graduation Rate All Races Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Somerset_County_HS_Graduation_Rate_All_Races_Data.xlsx)
- [Somerset County HS Graduation Rate Asians Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Somerset_County_HS_Graduation_Rate_Asians_Data.xlsx)
- [Somerset County HS Graduation Rate Black Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Somerset_County_HS_Graduation_Rate_Black_Data.xlsx)
- [Somerset County HS Graduation Rate Hispanics Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Somerset_County_HS_Graduation_Rate_Hispanics_Data.xlsx)
- [Somerset County HS Graduation Rate White Data](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Original%20Datasets/Somerset_County_HS_Graduation_Rate_White_Data.xlsx)
## Data Question - Analysis
This analysis uses Microsoft Excel to answer the following questions: 
- In both Basking Ridge and Baltimore, how do the high school graduation rates impact household income? 
- How do Basking Ridge and Baltimore compare in terms of high school graduation rates, household income, and discrepancies between races?
## Data Answer
![alt text](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Basking%20Ridge's%20Household%20Income%20Compared%20to%20Somerset%20County's%20High%20School%20Graduation%20Rate.png)
![alt text](https://github.com/Daphne-Tang/Comparing-Household-Income-and-High-School-Graduation-Rates-in-Basking-Ridge-and-Baltimore/blob/master/Baltimore%20City's%20Household%20Income%20Compared%20to%20High%20School%20Graduation%20Rate.png)

A similarity between the two cities is that the higher the high school graduation rates for each race, the greater the household income. However, a major difference is that the household income for all races in Basking Ridge - $75,686.33 - is much greater than that in Baltimore City - $27,591. The Somerset County high school graduation rate for all races - 93% - is also greater than that for Baltimore City - 78%. The differential between high school graduation rates - 15% - does not seem to completely explain the gap in household income ($48,095.33), so high school graduation rates are critical to social mobility but are insufficient by themselves to completely predict future household income. The Basking Ridge data provides further evidence in support of this claim because te 90% high school graduation rate for blacks does not seem to reflect the $35,374 household income they earn. 

In both Basking Ridge and Baltimore, high school graduation rates and household incomes tend to be higher for whites and Asians than for Hispanics and blacks. The study compares the outcomes of children that grew up in the same city, so racial discrepancies show the existence of inequal opportunities for certain groups, who may face other barriers that inhibit social mobility. There also seems to be greater racial disparities in Basking Ridge since the range for household income is $43,847 whereas that for Baltimore City is $19,305.


## Business Answer
