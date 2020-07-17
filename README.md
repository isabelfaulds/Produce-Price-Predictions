# Produce-Soup
A Beautiful Soup of Fruit & Vegetable Prices

## Intent
Fresh produce prices are viewed as one of the most volatile of commodities, [see more here].(https://gro-intelligence.com/insights/articles/fresh-produce-prices-top-volatility-rankings-gro-model-shows) For twenty years (1999-2019) Western Growers tracked produce prices at farm, as well as in retail in four cities, within in their [produce price index](http://www.producepriceindex.com/). This produce price index, once web scraped, serves as an extensive data source on trends in prices.

Using linear regression from Western Growers' dataset we can seek to predict the final retail price for consumers, taken as an average of cities Atlanta, Chicago, Los Angeles and New York.

### Tools Used
For this regression packages employed within **Jupyter Notebooks** include:
Pandas, BeautifulSoup, Numpy, Matplotlib, Seaborn, Sci Kit Learn, & Yellow Brick

## Findings
While produce categories have correlation with the Average Price at retail, these variables are subject to volatile conditions. Including selected produce category Strawberries did have a positive affect on root mean squared error as well r squared values.

Relying on produce types as features became most noteably susceptible to errors in years 2010 2011. This may have been due to the model highly favoring the use of a produce's categorization to predict prices. 

It should be noted that previous produce price was created as a reflection of price in that observation's produce category. Thus unique produce characteristics have been used in this regression, although binary categorization may be more volatile & in need of further analysis.

### At a Glance Data Trends 
- Slight downward trend of grocery store markup over years
- Slight downard trend of grocery store markup months--may be due to lower markups in harvest months
- Slight upward trend in farm price over years
- Stronger upward trend in Retail price over years

