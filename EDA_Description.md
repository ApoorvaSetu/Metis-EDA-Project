### Exploratary Data Analysis: MTA Data Analysis for a Health Organisation

## Abstract

The goal of this project was to analyse data for a Health organisation that wants to promote healthy eating and wants to target neighborhoods that are exposed to unhealthy food advertisements. Studies suggests thats most of the unhealthy cheap food advertisements are targeted towards low-income neighborhood. My client's goal is to expose people in these neighborhood to healthy and affordable food options.
I worked with the NYC Census data and MTA Turnstile data for three months from October 2021 to December 2021 to answer the questions my clients had. After Cleaning and analysing the two datasets, I visualised the results to communicate better with my clients.

## Data

MTA Turnstile Data, collected in 4 hour increments for three months in the year 2021:
http://web.mta.info/developers/turnstile.html
Income data by location:
[New York, NY | Data USA](https://datausa.io/profile/geo/new-york-ny#income)


## Methodology

Data collection (Used SQLAlchemy to load the dataset)
Data cleaning: Used a Python library called Pandas to clean data (Remove duplicate values,Null values, reformatting column names)
Merged the two data i.e Census data and MTA turnstile dataset to work with the selected Boroughs.
Data Visualization: Used Python libraries called Matplotlib and Seaborn to Create graphs and maps to convey my results.

## Results:

After analysing the census data, I found out that, out of the 5 boroughs in The NewYork City, Bronx and Brooklyn boroughs had the lowest median income. 
So I decided to work with Just the two boroughs.
Analysed the MTA Turnstile data for just the two Boroughs and used the number of entries and exits to calculate the traffic. My client needed the top 10 Busiest stations in the Bronx and Brooklyn Borough and the busiest days for Digital advertising.

Visualizations of my results:

Low Median income:
<img width="1235" alt="image" src="https://user-images.githubusercontent.com/64047140/149544424-002cc77a-df2e-425d-bb86-d28fab1b3633.png">

Turnnstile Data:
Top 10 stations in Bronx:
<img width="1178" alt="image" src="https://user-images.githubusercontent.com/64047140/149544601-1e19a6bb-127c-4395-89c1-e7335321b484.png">
Busiest days in Bronx stations:
![image](https://user-images.githubusercontent.com/64047140/149544711-c976cd65-d17d-4bf5-bac2-2dddf1a6a4c5.png)

Top 10 stations in Brooklyn:
![image](https://user-images.githubusercontent.com/64047140/149544798-b6ca854e-6ab7-4cbe-a89d-2c12f5e03293.png)
Busiest days in Brooklyn stations:
![image](https://user-images.githubusercontent.com/64047140/149544832-f2366d95-9d1a-4453-bff1-56450b81314d.png)








