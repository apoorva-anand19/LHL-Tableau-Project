# Final-Project-Tableau

## Project/Goals
Using AirBnB data for New York City, tyring to find a trend in listing prices and 
  properties based on the 5 Boroughs or NYC. One thing to note is this is data from
  2008 - 2015

## Process
1. Looked through the data and noted the missing values and datat types of the fields given.
2. Changed the datatype of some fields from integer to string, since those fields didn't need to be aggregated.
3. Replaced the null values with appropirate room count and with 0 in reviews and reviews scoring bin fields.
4. Continued on to exploring the data by plotting fields against one another to find insights.

  Sheet1 - Bubble representation of the type of property based on the boroughs
      We can see that Apartments are the most common type of properties available on AirBnB.

  Sheet2 - Scatterplot showing the avg.price of accomodation depending on no.of bedrooms
      Here we get an idea of the avg. price of listings and no.of bedrooms offered. Most
      common is 0, which is studio apartments, and 1-2 bedrooms. We can also find some outliers 
      here where some properties have 8-16 bedrooms, which obvisouly are either mutli-dwelling 
      lsitings like dorms or villas for events.

  Sheet3 - Bar chart to show avg. pricing to the type of accomodations
      Entire-home/apartment seems to be the majority in all boroughs. Here again, we can identify an outlier
      in Staten Island. The information there is based on just one property which is a villa with multiple bedrooms
      which ends up giving a wrong idea about the lsitings in Staten Island.

  Sheet4 - Choropleth of NYC boroughs based on ZIPCode of listings
      This was an interesting and interactive way to see where in the map are the cluster of listings
      with highers per-night average to other cheaper lsitings.

  Sheet5 - Cluster chart for pricing based on boroughs
      In this cluster analysis we can see that max amount of clusters are located with cluster 1 and 2.
      Cluster 4 especially shows us clearly the outliers, one from Staten Island and one from Manhattan 
      which are priced enormously higher than the average per-night cost.

  Sheet6 - Forecasting the trend for no.of listings after 2015 to 2018
      The trend line in the begining years, 2008-2014, is a bit erratic and doesn't give much insight. But from 2014
      and 2015 we can see that there is a clear spike in July and falls down in September. This tells us that the tourist 
      activity during summer vacations casues an increase in no.of listing in those months. There is again a spike near
      November and December. This again can be attributed to the holiday season. Based on this, we can forecast that in
      the future years too, this trend may be followed.

  Sheet7 - Scatter plot of price based on reviews
      Today we know that reviews on AirBnB are very important. But this data is from 2008-2015. And it looks like
      not much importance was given to reviews as almost 25% of the data there is 0 or null. 


## Results
  From the data given we can get a good idea of which parts of NYC have listings based on price ranges. And also with
  better maping we could figure out the point of interests for the listings along with other informations like public transport.

## Challenges 
  The numerous null values in Reviews feild hindered in the analysis process, as it could have given a better insight to 
  which properties and in which locations are more in demand and what that the other properties do to meet this demand.

