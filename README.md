# Airbnb_NYC_2019
Analysis on 2019 NYC Airbnb Data
## Installation
This project uses the following Python libraries under Python version 3.7:
  Pandas, 
  Numpy, 
  Matplotlib, 
  Seaborn, 
  Scikit-learn

Clone this repo to your local machine using ```$ git clone https://github.com/Luna-github/Airbnb_NYC_2019```. 

## Project Motivation
This project analyzes 2019 NYC Airbnb data to explore the differences in price and availability among different area groups in NYC, to identify the busiest hosts in NYC, and to build up a preliminary linear regression model to predict the listing price of each listing. 

## File Descriptions
`AB_NYC_2019.csv`: This file contains data that is used in this project, originally from [Kaggle](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data).

`Airbnb_NYC_2019.ipynb`: This file is the python file that includes codings used for this project.

## Interactions
### Findings
#### Area Differences
Mahattan and Brooklyn are two areas that are the most popular among the five boroughs in NYC. Within these two areas, private room is the most popular room type. Mahattan has the greatest list price among the five boroughs in all three room types. 

#### The Busiest Hosts
The busiest hosts are hosts who have multiple listings and whose listings are very popular (suggesting a low availability). There are 142 hosts who are identified that has more than or equal to 10 listings over the year and whose listings have less than or equal to ten days' availability. 

#### The Price Prediction
Based on two categorical variables and four numerical variables, the linear regression model has an R-squared on the test data as 0.09. 

## License
Usage is provided under the [MIT License](../blob/master/LICENSE). See LICENSE for the full details.
