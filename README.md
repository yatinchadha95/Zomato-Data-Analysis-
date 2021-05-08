# Zomato-Data-Analysis

- Performed Data Cleaning, Exploratory Data Analysis and Data Visualization on Zomato Dataset for Bengaluru city. 

- The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the aggregate rating of each restaurant, establishment of different types of restaurant at different places.

- Bengaluru being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world. With each day new restaurants opening the industry has'nt been saturated yet and the demand is increasing day by day. Inspite of increasing demand it however has become difficult for new restaurants to compete with established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don't have time to cook for themselves. With such an overwhelming demand of restaurants it has therefore become important to study the demography of a location. What kind of a food is more popular in a locality. Do the entire locality loves vegetarian food. If yes then is that locality populated by a particular sect of people for eg. Jain, Marwaris, Gujaratis who are mostly vegetarian. These kind of analysis can be done using the data, by studying different factors.

## Breakdown of this notebook:

1. **Loading the dataset:** Load the data and import the libraries. <br> <br>
2. **Data Cleaning:**
 - Deleting redundant columns.
 - Renaming the columns.
 - Dropping duplicates.
 - Cleaning individual columns.
 - Remove the NaN values from the dataset
 - Some Transformations<br><br>
3. **Data Visualization:** Using plots to find relations between the features.
 - Restaurants delivering Online or not
 - Restaurants having table booking or not
 - No. of restaurants in a Location
 - Best Location
 - Relation between Location and Rating
 - Restaurant Type
 - Relation between Restaurant Type and Rating
 - Types of Services
 - Relation between Service Type and Rating
 - Cost of Restuarant
 - Most famous restaurant chains in Bengaluru 
 - Most Liked Dishes in Bengaluru 
 - Most Liked Cuisines in Bengaluru 
 - Relationship between Rating and Online Order


## Data

The dataset is taken from kaggle, PFB the link:<br>
https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants

The dataset contains the following features :

- **url** : This feature contains the url of the restaurant on the Zomato website
- **address** : This feature contains the address of the restaurant in Bangalore
- **name** : This feature contains the name of the restaurant
- **online_order** : whether online ordering is available in the restaurant or not
- **book_table** : table book option available or not
- **rate** : contains the overall rating of the restaurant out of 5
- **votes** : contains total number of upvotes for the restaurant
- **phone** : contains the phone number of the restaurant
- **location** : contains the neighborhood in which the restaurant is located
- **rest_type** : restaurant type
- **dish_liked** : dishes people liked in the restaurant
- **cuisines** : food styles, separated by comma
- **approx_cost(for two people)** : contains the approximate cost of meal for two people
- **reviews_list** : list of tuples containing reviews for the restaurant, each tuple consists of two values, rating and review by the customer
- **menu_item** : contains list of menus available in the restaurant
- **listed_in(type)** : type of meal
- **listed_in(city)** : contains the neighborhood in which the restaurant is located
