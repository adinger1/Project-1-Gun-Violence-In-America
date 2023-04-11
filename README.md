# Project-1-Gun-Violence-In-America
Analysis of gun violence in America and its contributors

Our research project was a comparative study of the 50 states that looked at their gun violence and attempted to measure the degree to which this violence correlates with what are often considered social factors that contribute to gun violence. We choose to study poverty, high school dropout rates, population density.

First, we created a choropleth with plotly to look at the frequency of gun incidents in each of the 50 states over the last ten years.

We also looked at data for just 2022. 


In both graphs, New Jersey has a lower number of incidents. While not the lowest, 
We decided to further investigate potential contributors to gun violence.
(Interactive choropleths can be viewed by running the jupyter notebook ‘project_one_anika’.

We looked at per capita gun deaths and population density and were not able to confirm a meaningful correlation and got a P-Value of 0.75 meaning that the null hypothesis is likely to be true.


We found that high school dropout rates seem to correlate with gun violence. We looked at the 18-24 year old demographic and looked to see how many of these individuals had failed to receive an education (the data in question did not separate GEDs from high school diplomas so by looking at the younger age cohort we could get a better picture of the amount of young people who failed to graduate from high school). We found a fairly strong correlation between the amount of young people who failed to graduate high school and the amount of gun violence, and with a P-value=0.06814273765934241 we can have a reasonable amount of confidence that the null hypothesis is not true.



We also wanted to look at poverty as a social factor that contributes to gun violence. We found a strong correlation between the poverty rate in a state and the level of gun violence. Not only did we find a strong correlation between poverty and gun deaths per capita but we also found a P-value 0.0011680764684018116 so we can conclusively rule out a null hypothesis.



While we found some correlations between these social factors and state gun violence, it seems that we could have been more granular with our analysis. Although population density was ruled out as a factor on the state level we know that gun violence is often a predominantly urban phenomena and that logically population density should be a contributing factor. A more thorough analysis could be conducted in the future on the county level and could compare highly urbanized counties with less urbanized or rural counties. A greater focus on the county and the municipality as a unit for analysis would be good for future research. Furthermore we would have liked to have researched housing burden and eviction data but it was difficult to find quality data sets on these issues.

