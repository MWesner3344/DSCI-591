# DSCI-591
An Exploratory Data Analysis of COVID-19 Data

## Description:
COVID-19 has affected millions of people around the globe in 2020. In an attempt to understand this novel coronavirus, we explored the trends of day to day coronavirus numbers from each country. Our aim is to do time series analysis using COVID-19 dataset which is available from the dates 1st January 2020 to 3rd October 2020 and performing exploratory data analysis on different features present in the dataset. We are implementing different types of visualizations and attempt to find most important features of dataset using machine learning.
 


## Dataset Resources:

https://covid.ourworldindata.org/

https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-Sex-Age-and-S/9bhg-hcku

https://globalhealth5050.org/the-sex-gender-and-covid-19-project/dataset/


## Library Imports:
pandas, numpy, matplotlib.pyplot, seaborn, sklearn, missingpy, scipy, plotly.express

## Exploratory Data Analysis Visualizations:

<img src="Visualizations/Total Cases by Country.png" height="500">

<img src="Visualizations/Top 10 Mortality Rates.png" height="500">

<img src="Visualizations/Cases by Gender.png" height="500" width="400">

<img src="Visualizations/Deaths by Gender and Age.png" height="550">

<img src="Visualizations/Spearman Matrix.png" height="700">





## Overall Findings:
<ul>
<li>The United States, Brazil, India has the most deaths per day

<ul>
    <li>US: 700 deaths per day</li>
    <li>Brazil: 500 deaths per day</li>
    <li>India: 360 deaths per day</li>
</ul>

<li>The United States and Brazil has mortality rates that increase the most rapidly</li>
<li>North and South America has the highest increase in covid cases and deaths</li>
<li>Oceania has the least covid cases and deaths specifically in New Zealand</li>
<li>Males have a higher risk of death than females (10 males: 7 females)</li>
<li>Those that are above 65 years old have the highest risk of death</li>
<li>France, Italy, and Belgium have the highest case fatality rate</li>
</ul>


