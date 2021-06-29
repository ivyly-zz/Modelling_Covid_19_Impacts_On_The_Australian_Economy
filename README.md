## Project aim

The outbreak of Covid-19 in Australia early this year has plunged the country into a severe economic crisis forcing it to contend with sharply rising unemployment and its first recession in over thirty years. Broadly, there are two measures with which a country can stimulate its economy. The first is fiscal policy which involves government expedenditure in capacities such as tax cuts, direct cash transfer payments , infrastructure projects etc. The second, which will be the focus of our project, is monetary policy. This involves the central bank, the reserve bank of Australia in our case, adjusting the monthly cash rate, to incentivise spending and investment.
Our project aims to solve the following problems: 
+ Explore the impact of Covid-19 on the Australian economy and how it affects the various states, industries and genders.
+ Model the occurrence of recessions and the Australian unemployment rate.
+ Determine how the reserve bank of Australia should set its monetary policy to stimulate the economy and drive down the unemployment rate.

## Data exploration and analysis

Here we begin by exploring which states have been most impacted by covid-19. 
Following this we explore the impact of international border restrictions and its relationship with job vacancies and unemployment rate. 
Next, we examine how job vacancies have varied across the states before and during covid and assess which industries have been most affected.
Finally, we analyse the unemployment rate at the national and state level and assess if there is a relationship with monetary policy and the cash rate.

## Baseline linear regression model

In this section we model the Australian unemployment rate with macroeconmic indicators that include trade, inflation, investment, hours worked, GDP growth rate and cash rate. 
The baseline model is tuned by using RFE to determine the optimal number of features.

## Further prediction models

A decision tree model is built to compare the performances of regression models. We also, build and optimise (tune) KNN and ANN classifications models to predict the occurences of recessions. 
Finally, we build a Kmeans model to determine if their are meaningful clusters.

## Conclusion

We model various monetary policy scenarios that include varying the cash rate only during periods of weak economic growth, employing negative cash rates and increasing the cash rate across all periods
and conclude how the reserve bank of Australia should set its monetary policy to stiumlate the economy and drive down the unemployment rate.
