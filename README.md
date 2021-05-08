# Zomato-Data-Analysis

<b>Performed Data Cleaning, Exploratory Data Analysis and Data Visualization on Zomato Dataset for Bengaluru city. </b>

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
