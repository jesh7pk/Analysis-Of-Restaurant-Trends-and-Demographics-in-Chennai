# Analysis-Of-Restaurant-Trends-and-Demographics-in-Chennai
## Project Desciprtion
This project focuses on predicting restaurant ratings in Chennai by combining restaurant data, like location, cuisine type, and cost, with demographic information, such as literacy rates, sex ratio, and population in different areas. By analyzing these datasets together, we aim to find patterns, such as how the demographics of an area influence the popularity of certain cuisines and the ratings restaurants receive.
Using machine learning (ML) and deep learning (DL) techniques, we build models that can predict the rating of a restaurant based on its features and the demographic characteristics of its location. These models help us better understand the relationship between restaurant preferences and community traits, offering useful insights for restaurant owners, marketers, and planners to make smarter, data-driven decisions.

## Dataset Description
1. Swiggy Restaurants Dataset (Chennai)
This dataset contains detailed information about restaurants in Chennai sourced from Swiggy. It includes fields such as the restaurant's ID, name, city (area within Chennai), average rating, number of reviews, approximate cost for two people, and the type of cuisine offered. This dataset was filtered to include only relevant columns like restaurant name, location, rating, cost, and cuisine, while extraneous details like address and license numbers were excluded.

Key Fields:

* id: Unique identifier for each restaurant.
* name: Name of the restaurant.
* city: Area within Chennai where the restaurant is located.
* rating: Average user rating (1-5).
* rating_count: Number of user reviews.
* cost: Approximate cost for two people.
* cuisine: Type of cuisine(s) served (e.g., Indian, Chinese).

2. Chennai Area Demographic Dataset
This dataset provides demographic details for various areas within Chennai, sourced from the 2011 Census and supplemented with other publicly available information. It includes population statistics, literacy rates, sex ratios, and geographical coordinates for 17 selected areas. Data for 37 areas from Swiggy was not fully available or accurate, so analysis was restricted to the 17 most reliable locations.

Key Fields:

* Location: Name of the area in Chennai.
* Population Total: Total population of the area.
* Population Male: Male population.
* Population Female: Female population.
* Literates Total: Total number of literates in the area.
* Literacy Rate: Literacy rate of the entire population.
* Sex Ratio: Number of females per 1000 males.
* Coordinates: Latitude and longitude of the area.

3. Merged Dataset (Swiggy + Chennai Area)
The merged dataset combines the Swiggy Restaurants dataset and the Chennai Demographic dataset based on the shared "city" or "Location" field. This unified dataset allows for the analysis of restaurant data in the context of the demographic characteristics of different areas within Chennai, enabling more insightful trend analysis.

Key Fields:

Includes all fields from both the Swiggy Restaurants and Chennai Area Demographic datasets.
* Location: Area name (common across both datasets).
* Population Data: Demographic information such as total population, literacy rates, and sex ratio.
* Restaurant Data: Restaurant name, rating, cuisine, and cost details.
