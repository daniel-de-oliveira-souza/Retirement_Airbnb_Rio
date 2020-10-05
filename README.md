# Retirement_Airbnb_Rio
Retiring in Rio through Airbnb.

The goal of this project is to solidify an investment back at home in Rio to prepare for my retirement. One of the most efficient ways to do it is through the purchase of a property in Rio to Airbnb.

As I am not familiar with this business model, I think a great way to start my endeavors would be by checking the average rates for a room in Rio. 

To accomplish it, I imported Airbnb data sets available at insideairbnb.com. Then, I started the analysis by cleaning the data, selecting only the data points that are relevant to my investigation. Also, I replaced Null values with zeros, listings where price and availability cells were equal to zero,  to make the data more structured and pleasant to the eye. 
From that point on, the goal was to find the most popular spots to host. Through analyzing the frequency of listings per neighborhood, I found out that Copacabana, Barra da Tijuca, and Ipanema are the neighborhoods with the most listings. Also, I checked the average price for a room in Rio, converting it to USD. The average price is $129.

However, knowing the most popular spots to host and the average price doesn't mean that I have found my perfect match.

To narrow down my options, I created a second bar chart to show the neighborhoods that most offer rooms at a $200 rate. The second chart gave me Lagoa as the neighborhood with the most $200 listings.
A histogram gave me extra peace of mind, as I was able to see that other neighborhoods offer, on average, rooms at similar rates, just in case properties in Lagoa are not available for purchase.

By curiosity, I created a pie chart to see the room type distribution in Rio, and a scatterplot to see the relationship between reviews and price.

Before starting to reach out to hosts in Lagoa, I decided to narrow down the ones with the most reviews during Carnival, a Brazilian festival traditionally held every February.

Firstly, I combined my listing data set with a review data set, also available at insideairbnb.com. The second contains the dates that those listings where booked. Later, I filtered the data to show me only the listings located in Lagoa, which costs between $175 and $200, and which received at least eight reviews.
Lastly, after updated the date column from string to date, using import datetime, I printed the list with the name of three hosts - Paula, Regina, and Luiz Andre - as well as their id numbers. 
With that data, I can go to the app and look for their contact information and hopefully get some insights into how does it take to host a property that is very similar to the one I plan on purchasing soon.
