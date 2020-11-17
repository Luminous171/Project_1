# Project_1: Housing Market Analysis
### Finding Attractive Real Estate Investment Opportunities

Code developed by Carlos Tacchi, Nika Chan, Alex Hall, Matthew Musgrave, and Eli Holden

## Analysis

### Recent Housing Trends 

1. The Impact of COVID on Rental Prices

COVID has negatively impacted large cities rental prices because of the dense living requirements. In non-pandemic times, these cities can offer attractive job opportunities alongside premium amenity properties, but with business closures and working from home these are no longer the best options for renters. This has forced down the cost of renting in large cities while increasing the rental costs in suburban cities nearby. It has also driven a higher price for housing as would be renters decide to buy a home instead given the current health crisis.

2. Large Cities are Unaffordable

Based on our calculation of median household income to annual rental expense, those that live in larger cities pay over 30% of their gross wages on housing. This compares to the national average of XX%. People who work in these cities may choose to live further away to reduce their cost of living, but typically suffer longer commutes and may not have access to public transportation.

3. Crime is not always in cities

Certain factors help convince people to live in a specific area. One of those is how safe the area is. There is a reason why Maslow's Hierarchy of Needs has basic needs (safety, shelter) at the bottom of the pyramid. The data suggests that crime may not always be in cities, but it does gravitate towards them.

4. Population Growth

Most of the U.S. population growth occurs in major cities because jobs tend to encourage people to live in the area and have families which creates the virtuous cycle of more jobs, more people, and repeat. Immigration also helps the population growth, but that too is fueled by where the jobs are located.

5. Inflation

Inflation tends to increase the price of real assets such as housing. When looking at city size as a function of inflation larger cities have experienced higher inflation over the past 10 years.

![Inflation Chart](Images/inflation_chart.png)

### Future State of the Housing Market

The past does not always predict the future, but let us assume that is does. Forecasting the future rate of growth of the median house price in metropolitan statistical areas (MSA) across the U.S. for the next five years gives insight in to where the current environment may have unique investment opportunities.

Using this forecasted growth combined with our historical analysis we created a housing market rating by msa. The rating takes a customized basket of weights to High Total Return (Price and Yield) 45% + High Population Growth 10% + Affordability 20% + Low Crim 15% + COVID Impact 10%. An investor would want to choose msa that rank highly as they are favorable markets across all metrics.

![Image of HPA Map](Images/investment_opportunites.png)

The most attractive investment opportunities appear to be the cities of Oklahoma, Seattle, Tampa, Austin, and Denver.

### Choose Your Own Adventure

Given the analysis above our tool allows one to explore cities with the attom API that gives live listings of homes.


#### Sources of Data

1. Zillow (https://www.zillow.com/research/data/)
2. U.S. Census Bureau (www.census.gov)
3. U.S. Bureau of Economic Analysis (www.bea.gov)
4. API: Attom Data Solutions (www.attomdata.com)
5. U.S. Bureau of Labor Statistics (www.bls.gov)
6. Latitude, Longitude, and Population data (www.simplemaps.com/data/us-cities)
7. Crime Data (https://ucr.fbi.gov/crime-in-the-u.s/2015/crime-in-the-u.s.-2015/offenses-known-to-law-enforcement/violent-crime/violentcrimemain_final)

#### Considerations for Grading

Alex Hall: If you got it, he'll code it. Researched and compiled numerous datasets including our crime dataset, population, and latitude/longitude locational data. Cleaned data like the best of us. Mapped it in cool charts and had good ideas like the house price appreciation rank.

Carlos Tacchi: Master combinator and even with a smile. Arduously gave his right brain to the task of getting our population data in the right format, stitching our final dataframe and csv, and putting all our individual code in a dashboard.

Eli Holden: Monte Eli to the rescue. Writing code for all occasions. Crafting datasets and running the simulation that ties all the data together into a final equation of prediction. 

Matthew Musgrave: Resident API guru -- all things JSON. You want it, he's got it. Also the only reason we finished our presentation on time. 

Nika Chan: The utilitarian of the group. She can do it all. Pull it, clean it, map it. It's not just the newest bop-it game, but a priestess warrior of coding. Taking our employment data to the next level and keeping us all on track. 


