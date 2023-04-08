# Airbnb Booking Analysis
---
![Airbnb_Logo_Bélo svg](https://user-images.githubusercontent.com/63404689/230721853-dd746e43-c7ed-4646-86b1-1f51b63430c3.png)
---

## Abstract: 
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through 

**Keywords:** *Exploratory Data Analysis*


---
![airbnb europe](https://user-images.githubusercontent.com/63404689/230721962-899b8b59-ff4c-4bad-b9dd-022f9dabff41.jpg)
---


### 1. Problem Statement
I have a dataset of lodging for New York City and will try to extract some information that will help the company to understand the behaviors. There are multiple features that can help us in mapping or exploring the dataset such as:
id: ID for Traveler
name: Traveler Name
host_id: ID for host
host_name: Name of host
neighbourhood_group: Location
neighbourhood: Area
latitude: Latitude Coordinates
longitude: Longitude Coordinates
room_type: Type of stay
price: Cost fro the booking
minimum_nights: Number of stay in days
number_of_reviews: Number of reviews by customers
last_reviews: Number of reviews given per month
calculated: Amount of listing per host
availability_365: No. of days when listing is available for booking


### 2. Introduction

Travel is becoming so popular in this era, that people around the world started to visit countries. When we travel, we need options for stay such as room, hostel, house, guest, etc. Airbnb is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Based on multiple locations, the platform is accessible via the website and mobile applications. I have a dataset of lodging for New York City and will try to extract some information that will help the company to understand the behaviors.


### 3. Steps involved:


**Exploratory Data Analysis**
After loading the dataset I checked for data shape and some descriptive statistics of numerical data to take a gist of the dataset, later on, did some bivariate and univariate analysis on the categorical and numerical features to extract information. There were some columns which are not as importance for the analysis, so, dropped those columns.

**Null values Treatment**
The dataset contains a large number of null values for a few features, and treating null values depend upon the features and based on the situations, in this problem I used mean for a column, however, this is the analysis part I tried to analyze as it is rather doing any feature engineering.

**Feature Extraction**
In this data set, there is a feature whose data type is datetime and I extracted only months from this feature as this is only for same year data.

### 4. Conclusion:

That's it! We reached the end of our exercise.
Starting with loading the data so far we have done EDA , data preprocessing, null values treatment, feature extraction. Represented the insight in form of graph or plot.

### Tools Used
- Pandas![Pandas_logo svg](https://user-images.githubusercontent.com/63404689/230722152-c4684f18-a6aa-4ddd-9f23-0d43b985f4e1.png)
- NumPy![1200px-NumPy_logo_2020 svg](https://user-images.githubusercontent.com/63404689/230722144-bc289382-614e-4b74-8614-0a4b55952dcd.png)
- Matplotlib![logo2](https://user-images.githubusercontent.com/63404689/230722098-4234baa9-780f-4391-9073-c45a1bef0061.svg)
- Seaborn![fd110d80-63d1-11eb-9ae4-de7c23c9dedc-min](https://user-images.githubusercontent.com/63404689/230722459-fe27a978-3a4c-49d5-98e9-06f7ab6c94af.png)



First Capstone Project of Airbnb with 49000 entries.
