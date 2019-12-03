# Analysing Seattle Airbnb data and insights
<b>Table of Contents:</b>
<b>Libraries Used:</b>
<b>Files Description</b>
<b> My Questions </b>
<b>My findings</b>
<b>Acknowledgments and thanks</b>






<b>Libraries Used:</b>

The project was done on Jupyter Notebook and Python 3.0, below are the libraries used:
1. Matplotlib
2. Seaborn
3. Pandas
4. Numpy
5. Sklearn

<b>Files Description</b>
The Seattle Airbnb data is available at Kaggle (https://www.kaggle.com/airbnb/seattle),
the data has three files listed below:

1. Calendar
2. Listing
3. reviews


<b> My Questions </b>
After looking into the data, and trying to understand what is collected and how it can be used to better visual the data,
below are a few question i came up with. The answers should provide some insight.

1. What effect the prices of the hosts rental properties?
2. Does the area they are renting in effects the price? is it the number of reviews they got?
2. What are the different counts of properties and does the property type effect the price?
3. Does the cancelation policy play any role in the price? and is the review score rating biased?
4. Is the rental sector in Seattle seasonal? and when is the best time to rent?
5. What are the most important features affecting the price?



<b>My findings</b>
I will summarise the finding here in sections based on the topic:
Prices:
The highest three neighbourhoods are, Magnolia 177 USD, Queen Anne at 157 USD, and Downtown at 154 USD
Down town neighbourhood has the highest prices as outliers, and second highest as of counts of rental properties.
The highest mean prices of the year at July at 151 USD. It is surely summer and tourist are in Seattle. The lowest month is January which is after all the holidays at a mean price of 121 USD.
Also there is a correlation between a higher price and the rental property accommodating type, the more it accommodates the higher the price. Also 67% of the rentals are priced between 20 to 220 USD per night, with a mean if 127 USD.
If you had a boat to rent out, you can charge higher than most property type, you have a larger spread.

Property Type:
The Apartments and Houses are the main rental properties by far (45% and 44% respectively). Apartment and Houses are close from a price standpoint. Houses have a larger spread of prices in comparison with Apartments. 

Peak Rental Dates:
The highest month for rental is July and the lowest is January. Also cancellation policy seems to play no effect on the rentals, but only on the Downtown area where they are strict with cancellation and  it seems because downtown has a lot of places with higher priced rentals. The higher you are pricing your rental property the less flexible you are with cancellations. 

Review Scores:
One issue i feel that the data is biased is that the review score rating are shifted to the higher end of the rating, closer to 100% with a mean score of 94%. I feel this maybe biased because most of the data is rated high. There is also a clear relationship with higher review rates and higher prices. The less your ratings the less you charge.

Important Features:
After running a linear regression on all the features, many features have been removed if they had many Nans and if they provided little variance. Also cleaned the missing data in the numerical features and took the average of the column when needed. 

property_type_Dorm
host_has_profile_pic_t
room_type_Shared room
host_acceptance_rate_100%
room_type_Private room 	
neighbourhood_group_cleansed_Downtown
neighbourhood_group_cleansed_Northgate
property_type_Chalet
neighbourhood_group_cleansed_Delridge
property_type_Loft

Above some features make sense like neighbourhood of Downtown affects the price positively and Northgate affects it negatively.



<b>Acknowledgments and thanks</b>
Thanks to AirBnb for providing the data to analyse. 

