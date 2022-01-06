
Ads in mass transit stations may be impactful as exposure might be sustained (as riders wait for trains) or recurrent (as riders repeat daily commutes). 

In this study ( [Unhealthful Food-and-Beverage Advertising in Subway Stations: Targeted Marketing, Vulnerable Groups, Dietary Intake, and Poor Health](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5391329/) ), presence of “less-healthful” food ads in stations (in general, or specifically directed at minorities) was correlated with the behaviors of lower fruit-and-vegetable consumption and higher sugary drink intake, and with diet-related conditions like diabetes, hypertension, and high cholesterol.


## What is the framing question of your analysis, or the purpose of the model/system you plan to build?

How can an Ad company utilize commuter data to identify people that are exposed to “Unhealthful Food-and-Beverage Advertising”  and promote Healthy food advertising?

## Who benefits from exploring this question or building this model/system?

Since we have an evidence that the unhealthy ads are usually targeted towards stations in a low-income neighborhood, My analysis of stations in a low-income neighborhood with high foot traffic (using MTA data) can give my Ad agency a better idea to where to target their marketing and put their ads on. 

## What dataset(s) do you plan to use, and how will you obtain the data?
MTA Turnstile Data, collected in 4 hour increments - estimated to be 95,761,349 rows
http://web.mta.info/developers/turnstile.html
Income data by location
[New York, NY | Data USA](https://datausa.io/profile/geo/new-york-ny#income)
Residential areas where riders entered the system
[U.S. Census Bureau QuickFacts: New York](https://www.census.gov/quickfacts/NY)

## What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
An individual sample for the first dataset would include all of the entrances and exits for all the stations in the Bronx borough over one four-hour period.

## How do you intend to meet the tools requirement of the project?
The tools I need to do the analysis would be:
SQLAlchemy
Python Libraries : Pandas, Matplotlib and Seaborn (Data visualization)
