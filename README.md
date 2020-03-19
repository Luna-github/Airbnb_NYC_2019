# Airbnb_NYC_2019
Udacity Data Scientist Nanodegree Project
Analysis on 2019 NYC Airbnb Data
## Installation
This project uses the following Python libraries under Python version 3.7:
  `Pandas` 
  `Numpy` 
  `Matplotlib` 
  `Seaborn` 
  `Scikit-learn`

Clone this repo to your local machine using ```$ git clone https://github.com/Luna-github/Airbnb_NYC_2019```. 

## Project Motivation
This project analyzes 2019 NYC Airbnb data to explore the differences in price and availability among different area groups in NYC, to identify the busiest hosts in NYC, and to build up a preliminary linear regression model to predict the listing price of each listing. 

## File Descriptions
`AB_NYC_2019.csv`: This file contains data that is used in this project, originally from [Kaggle](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data).

`Airbnb_NYC_2019.ipynb`: This file is the python file that includes codings used for this project.

## Interactions
### Findings
#### Area Differences
Mahattan and Brooklyn are two areas that are the most popular among the five boroughs in NYC. Within these two areas, private room and entire room/apartment are the most popular room types. Mahattan has the greatest listing price among the five boroughs in all three room types. 

#### The Most Successful Hosts
In my analysis, I calculate the average revenue for each host in NYC by multiplying the number of days their rooms booked with the list price and averaging this to each listing if the host has more than one listing. I picked those hosts as the most successful with average revenue of $37,497.5 or above. The majority of these most successful hosts have listed their rooms in Manhattan and Brooklyn as entire home/apartment

#### The Price Prediction
Based on two categorical variables (room type and neighbourhood_group) and six numerical variables (longitude, latitude, reviews_per_month, minimum_nights, availability_365, and calculated_host_listings_count), the linear regression model has an R-squared on the test data as 0.11. 

## Author
Luna Li
Github: https://github.com/Luna-github

## License
Usage is provided under the [MIT License](../blob/master/LICENSE). See LICENSE for the full details.
