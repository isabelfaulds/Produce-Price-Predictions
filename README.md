# Fruit-Soup
A Beautiful Soup of Fruit Prices

# 


Fresh produce prices are viewed as the most volatile of commodities. (link)[https://gro-intelligence.com/insights/articles/fresh-produce-prices-top-volatility-rankings-gro-model-shows]
Soil Temperature & rainfall have both been considered as factors in agricultural yield. Seasonal differences also affect supply & demand with an influx of supply during the months in late summer, early autumnn.


Using linear regression from this dataset we can seek to predict:
End price for consumer
Initial farmer price
Average mark up of grocery stores

We may also examine further:
How month may affect prices
How year may affect prices
How weather condition may affect prices

## Initial Data Insight
- Slight downward trend with average spread (grocery store markup) over years
- Slight downard trend with average spread over months

- Slight upward trend in farm price over years
-Very slight upward trend in farm price over months

- Stronger upward trend in Chicago Retail price over years
- Slight upward trend in Atlanta, NY Retail price over years

- No trend in Chicago, LA, NY, Atlanta Retail price over months

- Compare upward trend in prices in Atlanta, LA, NY, & Chicago
- Coefficient of Atlnta:
- Coefficient of Chicago:
- Coefficient of NY:
- Coefficient of LA:

-Including Produce dummy variables substantially raised R Squared from 0.677 to 0.747 in test

## Features
- Farm Price
- Date

## Target Variable Potentials
- Year
- 

Could split up observations with one hot for location
Also one hot for produce
