# Car-Models-Listings
Reports shows the analysis of used Car listings.
# Project Name:  Car Model Listing
## Project Details
The dataset contains information of price, transmission, mileage, fuel type, road tax, miles per gallon (mpg), and engine size. They were separated into files corresponding to each car manufacturer.
The objective of this project is to use Power BI to visualize the data and answer the following questions and more:
* What is the average price of each car manufacturer in the dataset?
* What is the correlation between the price and mileage of the cars?
* What is the distribution of fuel types across the dataset?
* How does the road tax impact the price of the car?
* What is the trend of the mileage and price of the cars over the years?

## Data collection: 
Dataset was gotten from Kaggle.
Link to the dataset: 
https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes

## Data Cleaning
In this task, I needed to clean the data set by removing any missing or irrelevant data, formatting the data types correctly, removed any null or duplicate values and transforming the data to a more usable form. 
After the data was cleaned, I prepared the data for modeling by splitting the data into training and testing sets, performed EDA to explore the relationships between the features and the target variable (price)
![car list power query editor](https://github.com/uduaklawrence/Car-Models-Listings/assets/141685463/597ba955-04d5-48e8-9526-7724176fedd5)


## Data Transformation: 
Transformed the data to create the following new columns:
* Age of the car (calculated using the year of manufacture)
* Price per Mileage (calculated by dividing the price by mileage)
* Average price per model (calculated using the DAX function)

## Data Visualization:
![car list 1](https://github.com/uduaklawrence/Car-Models-Listings/assets/141685463/debb50ef-9872-4071-9557-63394c81e474)
![car list 2](https://github.com/uduaklawrence/Car-Models-Listings/assets/141685463/4f7c4a91-033d-49eb-9cad-922d42647dd1)


  
## Insights:
* Ford manufacturer has the highest average price over 1 million per each car model
* There is an association or correlation between the price and mileage values. The lower the mileage,     the higher the price; the higher the mileage , the lower the price.
* The road tax does not have any impact on the prices of the cars; though at one point, the price         increased rapidly
* Visible variation between the price and mileage of the car is seen within the years
* Cars that use petrol and diesel as fuel type have relatively high prices
* Cars with relatively higher ages commands lower price.
