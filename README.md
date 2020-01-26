# Airbnb_NYC
![New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2](https://user-images.githubusercontent.com/48190655/71230772-cfd1d080-229f-11ea-979b-3ae1782eb87b.jpg)

Airbnb provides a platform for hosts to accommodate guests with short-term lodging and tourism-related activities. Guests can search for lodging using filters such as lodging type, dates, location, and price. Guests have the ability to search for specific types of homes, such as bed and breakfasts, unique homes, and vacation homes. 


Hosts provide prices and other details for their rental or event listings, such as the allowed number of guests, home type, rules, and amenities. Pricing is determined by the host, with recommendations from Airbnb Hosts and guests have the ability to leave reviews about the experience.

Since its inception in 2008, Airbnb has seen a exponential growth with the number of rentals listed on its website. Airbnb has successfully disrupted the traditional hospitality industry as more and more travellers utilize Airbnb as their premier acccomdation provider.

New York City has been one of the hottest markets for Airbnb. In the project, I performed an exploratory analysis of the Airbnb dataset to understand the rental landscape in New York City. The listings are from 2011-2019. 


Questions to be explored:

1. Who has the most listings? 

![Hosts with most listings](https://github.com/aclao89/Airbnb_NYC/blob/master/Images/top10hostlistings.png)

The first host has 300+ listings. Third through tenth hosts have evenly distributed amount of listings.


2. Which neighbourhood group have the most listings?

![Listings by Neighbourhood Groups](https://github.com/aclao89/Airbnb_NYC/blob/master/Images/neigh_group_listings.png) 

Each subplot is for the room type: entire home/apartment, private room, and shared room. The X-axis is the neighbourhoods and Y-axis is the count of listings in that particular neighbourhood. The first observation is the limited availability of shared room listings. We could attribute this to the small living conditions of New York City. Out of the neighbourhoods groups, only Manhattan and Brooklyn are presented which is to no suprise since they are the most traveled areas in New York City.Williamsburg and Bedford-Stuyvesant is most popular neighbourhood in Brooklyn. Harlem has the most listings in Manhattan.

3. What is the price range of listings in the neighborhood groups?

![Listing price by Neighborhood Groups](https://github.com/aclao89/Airbnb_NYC/blob/master/Images/neigh_group_price.png)


4. List the price distribution of listings in the 5 bouroughs.

![Rental Price Distribution](https://github.com/aclao89/Airbnb_NYC/blob/master/Images/rentalpricedistribution.png)

Based on this violin chart, Manhattan has the widest distribution (wide range of prices) with $ 150 as average. Brooklyn has the second highest distribution. Queens and Staten Island have similar distributions and averages. Bronx is the cheapest of them all. This violin chart is logical since Manhattan is known as one of the most expensive places in the world to live in whereas Bronx has a lower standard of living costs.

5. Create a heatmap of the listings in the New York City bouroughs.
6. What is the average price of the top-reviewed listings? 
7. Find a trend in the words used in the listing description.





Data Source: Kaggle [https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data]
