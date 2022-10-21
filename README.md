# Zomato EDA

The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the establishment
of different types of restaurant at different places in Bengaluru, aggregate rating of each restaurant and many more.

## Breakdown of this notebook:
1.) Loading the dataset: Load the data and import the libraries.

2.) Data Cleaning:
* Deleting redundant columns.
* Renaming the columns.
* Dropping duplicates.
* Cleaning individual columns.
* Remove the NaN values from the dataset 
* Some Transformations 

3.) Regression Analysis
* Linear Regression
* Decision Tree Regression
* Random Forest Regression

**Data Visualization:** Using plots to find relations between the features.
* Restaurants delivering Online or not
* Restaurants allowing table booking or not
* Table booking Rate vs Rate
* Best Location
* Relation between Location and Rating
* Restaurant Type
* Gaussian Rest type and Rating
* Types of ServicesRelation between Type and Rating
* Cost of Restuarant
* No. of restaurants in a Location
* Restaurant typeMost famous restaurant chains in Bengaluru

## **Dataset**

Zomato Bangalore Restaurants - https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants

The data is accurate to that available on the zomato website until 15 March 2019.
The data was scraped from Zomato in two phase. After going through the structure of the website I found that for each neighborhood there are 6-7 category of restaurants viz. Buffet, Cafes, Delivery, Desserts, Dine-out, Drinks & nightlife, Pubs and bars.
