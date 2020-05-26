
# Introduction


New York City's demographics show that it is a large and ethnically diverse metropolis. It is the largest city in the United States with a long history of international immigration. New York City was home to nearly 8.5 million people in 2014, accounting for over 40% of the population of New York State and a slightly lower percentage of the New York metropolitan area, home to approximately 23.6 million. Over the last decade the city has been growing faster than the region. The New York region continues to be by far the leading metropolitan gateway for legal immigrants admitted into the United States.

Throughout its history, New York City has been a major point of entry for immigrants; the term "melting pot" was coined to describe densely populated immigrant neighborhoods on the Lower East Side. As many as 800 languages are spoken in New York, making it the most linguistically diverse city in the world. English remains the most widely spoken language, although there are areas in the outer boroughs in which up to 25% of people speak English as an alternate language, and/or have limited or no English language fluency. English is least spoken in neighborhoods such as Flushing, Sunset Park, and Corona.

With it's diverse culture , comes diverse food items. There are many resturants in New york City, each beloning to different categories like Chinese , Indian , French etc.

So as part of this project , we will list and visualize all major parts of New York City that has great indian resturants.

#  Data

Data For this project we need the following data :

New York City data that contains list Boroughs, Neighborhoods along with their latitude and longitude.
Data source : https://cocl.us/new_york_dataset Description : This data set contains the required information.
And we will use this data set to explore various neighborhoods of new york city.
Indian resturants in each neighborhood of new york city.
Data source : Fousquare API Description : By using this api we will get all the venues in each neighborhood. We can filter these venues to get only indian resturants. GeoSpace data Data source : https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm Description : By using this geo space data we will get the New york Borough boundaries that will help us visualize choropleth map.

# Approach


1) Collect the new york city data from https://cocl.us/new_york_dataset \
2) Using FourSquare API we will find all venues for each neighborhood. \
3) Filter out all venues that are Indian Resturants. \
4) Find rating , tips and like count for each Indian Resturants using FourSquare API. \
5) Using rating for each resturant , we will sort that data. \
6) Visualize the Ranking of neighborhoods using folium library(python)

#  Queries that can be answered using above dataset

1) What is best location in New York City for Indian Cuisine ? \
2) Which areas have potential Indian Resturant Market ? \
3) Which all areas lack Indian Resturants ? \
4) Which is the best place to stay if I prefer Indian Cuisine ? \

#  Analysis

### Required Libraries

1) pandas and numpy for handling data. \
2) request module for using FourSquare API. \
3) geopy to get co-ordinates of City of New York. \
4) folium to visualize the results on a map


```python

```
