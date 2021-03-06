3/29/2020 [3-28-2020--Allegheny.PNG]:
Time resolved data on cases and deaths in all Pennsylvania  (PA) countries since 3/19/2020 until 3/29/2020 were scraped from PA Dept of Health and Allegheny County's data (i.e. the county for the City of Pittsburgh) was extracted for modeling.  These data were fed into a logistic regression model using only the data available i.e. 10 days prior to the date of analysis.  The choice of a logistic fit is predicated by the trends in case volumes seen in cities in China, where social distancing and best practices have resulted in some success in curbing the spread of COVID-19.    
The Greater Pittsburgh Area is has an estimated capacity of between 398 and 500 ICU beds and about 10x more hospital beds.  About 7-10% of cases are expected to lead to hospitalization with the 19% of Allegheny County's population over 65 years of age being at the highest risk of hospitalization related deaths.  At a 7% ICU hospitalization rate, Allegheny County can tolerate roughly 6500 cases of COVID-19. This doesn't factor in ICU transfers and patient movement out of ICUs owing to other reasons.   
To hit 6500 cases at the current case growth rates would require significant lapses in social distancing best practices or an otherwise unforseen spike in case volumes.
However, if cases were to accumulate at the rate that it is across the US as a whole (i.e. case volume doubles every 3 days, based on data at the present time), a peak capacity situation may develop on the 15th day from 3/28/2020 (the date of this analysis).  


3/30/2020 [Allegheny_3282020_SIRDmodel.PNG]: 
My best model yet for Allegheny County - this factors in the following ODEs to solve for susceptible, infected, recovered and dead cases for COVID19, based on the 10 days of historical data available between 3/19 and 3/29 ... This model forecasts susceptible individual counts, recovered individual counts and deaths, assuming currently that the "current" recovery rate is 20% of the susceptible individual counts. If recovery rates baseline to higher than 20%, then the numbers can be more optimistic!  The latter is consistent with the median recovery rate from Johns Hopkin's data by country.  


4/1/2020 [Allegheny_412020_SIRDmodel.jpg]
This model utilized data from 3/19 to 4/1/2020. The plot depicts cases (infected, recovered and dead) predicted as a function of time. Allegheny county has had 2 deaths reported owing to COVID19 which have held steady for several days so the deaths curve isn’t quite right, but the rest looks to show that the peak might be here before Mid April and the nightmare of living in fear may go on well after May (and into the summer)...

Projected # cases seem to curve off at 535 cases by April 13. Deaths reported still holding steady at 2!

4/11/2020 [4-11-2020--Allegheny.PNG]
Peak case load expected by 21 April, at ~900 confirmed cases.



