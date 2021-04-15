# Exploratory data analysis of World Happiness Report 

## Background 

The World Happiness Report is a publication of the Sustainable Development Solutions Network, powered by data from the Gallup World Poll and Lloyd’s Register Foundation, who provided access to the World Risk Poll. The 2021 Report includes data from the ICL-YouGov Behaviour Tracker as part of the COVID Data Hub from the Institute of Global Health Innovation. The World Happiness Report was written by a group of independent experts acting in their personal capacities. Any views expressed in this report do not necessarily reflect the views of any organization, agency or program of the United Nations.

The dataset available at kaggle that summarizes world happines report was analyzed below. 
The happiness scores and rankings use data from the Gallup World Poll. The columns following the happiness score estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. They have no impact on the total score reported for each country, but they do explain why some countries rank higher than others. 

Sources: https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021
https://worldhappiness.report/ed/2021/

## Business Question

Can we identify from this dataset using exploratory data analysis what factors affect country's happiness level?

## Data Question

What metrics have an effect on country's happiness and how are they correlated?

## Analysis 

Using Python libraries, explaratory data analysis was performed. Datasets, world-happiness-report.csv and world-happiness-report-2021.csv were uploaded. The first file contains metrics on each country starting from 2008 to 2019. world-happiness-report-2021.csv contains original metrics on 2021. Healthy life expentancy on the reports is considered to be the rank of the country based on the Happiness Score, and Freedom to make life choices is meant to be The extent to which Freedom contributed to the calculation of the Happiness Score.
![](https://github.com/DurdonaG/WorldHappinessReport/blob/main/Images/Screen%20Shot%202021-04-15%20at%202.31.08%20AM.png)
![](https://github.com/DurdonaG/WorldHappinessReport/blob/main/Images/Screen%20Shot%202021-04-15%20at%202.31.31%20AM.png)

First, insights from datasets were concluded as follows: 
![](https://github.com/DurdonaG/WorldHappinessReport/blob/main/Images/image.png)

According to data provided, happies country is Finland and unhappiest country is Afganistan for 2021. 9 of top 10 happiest countries were in Europe while 7 of bottom 10 unhappiest countries are in Africa. 

This was summarized in the following chart: 
![](https://github.com/DurdonaG/WorldHappinessReport/blob/main/Images/summary1.png)

Next, correlations between variables were calculated to see how happiness index is related to certain metrics and to observe the relationship between metrics. 

1. Correlation between Social Support and Happiness Index: 
Correlation coefficient being 0.76 indicates a strong positive relationship between social support and happiness index. This can be seen in the graph below. 
![](https://github.com/DurdonaG/WorldHappinessReport/blob/main/Images/SocialsHI.png)

2. Correlation between Generosity and Happiness Index: 
Small negative correlation coefficient between generosity and happiness index is -0.017. So we can conclude that happiness index does not depend on generosity as can be seen in the scatterplot below. 
![](https://github.com/DurdonaG/WorldHappinessReport/blob/main/Images/Generosity%20HI.png)

3. Correlation between Corruption and Happiness Index:
Correlation coefficient: -0.42
![](https://github.com/DurdonaG/WorldHappinessReport/blob/main/Images/CorruptionHI.png)

4. Correlation between Freedom and Corruption:
Correlation coefficient: -0.4
![](https://github.com/DurdonaG/WorldHappinessReport/blob/main/Images/FreedomCorruption.png)


## Conclusion
The World Happiness Report is a landmark survey of the state of global happiness. The report continues to gain global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness. 
