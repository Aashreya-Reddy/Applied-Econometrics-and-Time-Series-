# Applied-Econometrics-and-Time-Series-
Analyse the effect of GDP on the suicides using Fixed Effects Model

OBJECTIVE: Our objective for this project was to investigate the relationship between suicide rates and GDP of 101 different countries over 32 years.

EMPERICAL ANALYSIS: 
Since we have the data for the same countries over different years, a first differences or fixed effects model would be most appropriate to estimating the effect of GDP on suicide rates. 
If we regress number of suicides on gdp using fixed effects model, the time constant part of the error term which is most likely correlated with the independent variable GDP will be annulled as we will be taking the difference of each observation with the mean of that variable. Some of the time constant variables could be size of the country, the amount of land available for economic activity such as agriculture, the availability of natural and mineral resources, etc.
We can control for the population in two ways - 
1.	Including population in the regression equation if the dependent and independent variables are total_suicides and gdp_for_year respectively.
2.	Instead of including population in the equation, we can use suicides_per_100k and gdp_pc and dependent and independent variables respectively.


CONCLUSION: Although the grief felt by those who have lost loved ones to suicide can seem similar across different cases, suicide represents the culmination of an extremely complex group of behavioral factors of both an intrapersonal and societal nature. The rate of suicide is not only responsive to economic factors, such as GDP per capita or growth rate of GDP per capita, but also to social factors. It can be said that a higher GDP can result for an improved quality of life that generally tends to curve the rate of suicide for nuance. Since our model produced the results of a statistically insignificant correlation between GDP and suicide rates, it can be inferred that the real-world consequences of this relationship could be considered negligible and does not support any causal relationship between the GDP and suicide rates.

Programming: Stata 
Model used : Fixed Effect Model
