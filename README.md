# Produce-Soup
Linear Regression Performed on a Beautiful Soup of Vegetable & Fruit Prices

## Intent
Fresh produce prices are viewed as one of the most volatile of commodities, [see more here](https://gro-intelligence.com/insights/articles/fresh-produce-prices-top-volatility-rankings-gro-model-shows) For twenty years (1999-2019) Western Growers tracked produce prices at farm, as well as in retail in four cities, within in their [produce price index](http://www.producepriceindex.com/). This produce price index, once web scraped, serves as an extensive data source on trends in prices.

Using linear regression from Western Growers' dataset we can seek to predict the final retail price for consumers, taken as an average of cities Atlanta, Chicago, Los Angeles and New York.

### Tools Used
For this regression Python packages employed within **Jupyter Notebooks** include:
Pandas, BeautifulSoup, Numpy, Matplotlib, Seaborn, Sci Kit Learn, & Yellow Brick

## Findings
While produce categories have correlation with the Average Price at retail, the volatility of these variables affects their efficacy as dummy variables in the regression project. Including selected produce categories did have a positive affect on root mean squared error as well r squared values. 

It should be noted that high performing feature Previous Price was created representing the previous price of an observation's produce category. Thus unique produce trend characteristics have been used in this regression, although binary categorization use is in need of further analysis. 

Relying on produce types as features became most noteably susceptible to errors in years 2010 2011. This may have been due to the model highly favoring the use of a produce's categorization to predict prices. 

### At a Glance Data Trends 
- Slight downward trend of grocery store markup over years
- Slight downard trend of grocery store markup months--may be due to lower markups in harvest months
- Slight upward trend in farm price over years
- Stronger upward trend in Retail price over years

# Conclusion
Using time series splits of training & testing, this linear regression model predicted on average with an error of 25 cents away from actual price. The r squared score of this amounts to 0.91. The predictions were made for 2 year periods & were most successful at the beginning and end of the twenty year period.
