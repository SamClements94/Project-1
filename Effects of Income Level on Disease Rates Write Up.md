Effects of Income Level on Disease Rates



•The Big Question: What impact does income level have on infection rates of preventable diseases?

•High-level:

​	•What is the average income for each state?

​	•How many reported cases of various diseases are there in each state?

•Is there a correlation between a state’s average income level and the prevalence of certain diseases?



Clean Up Process

•Epiweek – used by CDC, but not a usable date format

•Split into Year and Week and placed in new columns

•Cases listed as objects in DataFrame

•Removed blanks and converted to integers

•Census data lists state names in full, disease data listed abbreviations

•Changed state names in census data to abbreviations to allow for DataFrames to be merged

•Needed to integrate a loop to pull multiple years from Census API



Conclusions

•Correlation scatterplot shows that instances of disease are higher in lower income states

•Average income at which cases start to drop off was higher than expected

•Lower income is associated with many contributing factors to higher rates of disease, including:

•Lack of access to care and affordable health insurance

•Lower quality education, both from underfunded schools and an inability to afford higher education



Insights

•When did the other diseases get eliminated or drop so low that they stopped being reported?

•Is there a correlation between the states with the highest/lowest infection rates and the highest/lowest average income?

•Track changes over time – chart each year to see how it changes

•What other contributing factors could be added to the analysis? Religion? Climate? Population density?