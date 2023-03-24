## Zillow Target City Analysis

### Overview 

This project analyzes the housing market of four target cities - Minneapolis, Seattle, Portland, and Boulder - using Zillow data. The analysis includes examining the relationships between home values, home list prices, and home sales prices, as well as exploring median home values, home inventory, and median list and sales prices.

### Methodology

The data used for this analysis is from Zillow's Home Value Index (ZHVI), a measure of the typical home value and market changes across a given region and housing type. For this project, the data includes the ZHVI for all homes (SFR, condos, and co-ops) smoothed and seasonally adjusted.

The analysis involves calculating the correlation coefficients between median home values and years in each target city, as well as examining trends in home inventory and median list and sales prices.

### Project Results
When examining median home values by year from 2000 to 2022, each city follows similar trends from 2011 onward. Prior to that, Seattle and Portland show a dramatic rise, peaking in 2007 during the subprime mortgage crisis, and following a decline. Minneapolis was less affected by this but does show a peak and dip. Boulder's home prices held steady from 2002 until 2012, after which all home prices for all four cities started to rise.

<img src="[figures/median_values_all.png](https://github.com/earlyann/Zillow_target_city_analysis/blob/09f19e9a924e692f8b45b61b698ec7b4c79c963c/figures/median_values_all.png)" width="500">

The correlation coefficients (r) for median home values in Minneapolis, Seattle, Portland, and Boulder are 0.75, 0.81, 0.88, and 0.89, respectively. These values suggest a moderate to strong positive correlation between the years and the median home values in each of these cities. The highest correlation is seen in Portland, indicating a stronger relationship between time and home values in that city compared to the others.

<img src="[figures/median_values_linregress_all.png](https://github.com/earlyann/Zillow_target_city_analysis/blob/09f19e9a924e692f8b45b61b698ec7b4c79c963c/figures/median_values__linregress_all.png)" width="500">

The analysis of home inventory for the target cities from 2018 to 2022 reveals the cyclical nature of inventory in all four cities. Minneapolis historically has had the most inventory, followed by Seattle and Portland. As of mid-2022, Seattle overtook Minneapolis. Boulder has far less inventory than the other three cities.

<img src="[figures/inventory_all.png](https://github.com/earlyann/Zillow_target_city_analysis/blob/09f19e9a924e692f8b45b61b698ec7b4c79c963c/figures/inventory_all.png)" width="500">

When examining median list prices from 2018 to 2022, Boulder is and always has been the most expensive, followed by Seattle and Portland, with Minneapolis home prices falling far below the others.

<img src="[figures/median_list_price_all.png](https://github.com/earlyann/Zillow_target_city_analysis/blob/09f19e9a924e692f8b45b61b698ec7b4c79c963c/figures/median_list_price_all.png)" width="500">

Finally, the analysis of median list price vs. sales price from 2018 to 2022 shows a general trend in all four cities of sales prices falling below list prices but approaching even around 2021. Minneapolis and Seattle had a brief time in 2021 where sales prices topped list prices.

<img src="[figures/sales_v_list_all.png](https://github.com/earlyann/Zillow_target_city_analysis/blob/09f19e9a924e692f8b45b61b698ec7b4c79c963c/figures/sales_v_list_all.png)" width="500">

### Conclusion

This analysis provides insight into the housing market of four target cities and can help inform decisions related to real estate and investment. Future analysis could explore additional variables, such as square footage and the number of bedrooms, to further examine the housing market trends in these cities.

Author: Lacey Morgan
