# Zomato Bangalore Data EDA

## Overview

The objective of this project is to for CRISP-DM Process while providing data solution.

The CRISP-DM Process (Cross Industry Process for Data Mining) can be summarised as:

1. Business Understanding
2. Data Understanding
3. Prepare Data                   
4. Data Modeling
5. Evaluate the Results
6. Deploy

We will follow below steps to do that:

1. Pick a dataset.
2. Pose at least three questions related to business or real-world applications of how the data could be used.
3. Create a Jupyter Notebook, using any associated packages you'd like, to:
    Prepare data:

    Gather necessary data to answer your questions
    Handle categorical and missing data
    Provide insight into the methods you chose and why you chose them
    Analyze, Model, and Visualize

4. Communicate your business insights.


You can download the dataset used in this project from here : https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants


## Motivation

As an avid foodie and a soul of an entrepreneur, I always try to taste out new dishes. Starting a new business is what keeps me excited.
So, when I got my hands on Zomato Bangalore dataset, I thought why not see what this data has to tell.

## Data

I found this dataset on Kaggle. You can download the same from here : https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants

### Features

* url : zomato url for the restaurants 
* address : complete location of the restaurant
* name : name of the restaurant
* online_order : whether restaurant accepts online order
* book_table : whether restaurant provides option for booking table
* rate : restaurants rating on zomato website 
* votes : number of individual who voted for restaurants
* phone : contact details of the restaurant
* localtion : area where restaurant is situated
* rest_type : Type of restaurants (Categorical value)
* dish_liked : what are all dishes of the restaurant that people liked 
* cuisines : cuisines offered by the restaurant
* approx_cost(for two people) : average cost for two people 
* review_list : reviews of the restaurant on zomato website
* menu_item : menu items available in the restuarant
* listed_in(type) : type of the restaurant
* listed_in(city) : locality of the restaurant position

## Conclusion

We based our analysis keeping restaurant business in mind. We tried to figure out answers to some of the common queries when opening any new restaurant.

* We figured BTM, Koramangala, HSR are good places to start restaurant. WhiteField has most number of unique restaurants and can be cheaper to get started. Koramangala, Indiranagar, BTM are most popular locations among foodies.

* Large number of votes can ensure better rating and 1K for 2 people is good to go price.

* Bangalorian love fast food.

* Providing online ordering can boast your chances.


Detailed blog post about the business findings can be find here : https://medium.com/@shubh1795/starting-a-new-restaurant-in-bangalore-heres-what-you-should-know-e53bbce55a8
