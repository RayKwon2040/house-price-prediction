# House-Price-Prediction

## Project Goal
It is a dataset house sold between May 2014 to May 2015 in King County an area. The dataset consisted of 21 variables and 21,613 observations.

Key features

  * Description of houses
  * Location
  * Date of selling
  * Price

The primary objective of this project is to develop an accurate predictive model that estimates house prices based on location and type of house for real estate development projects in King county. This predictive model forecast the ideal selling price based on the property features, locatinon, allowing for more competitive pricing and faster sales.

## Project Workflow

![workflow_price](images/workflow_price.png)

## Exploratory Data Analysis

### Distribution of Features

![eda_price_dis](images/eda_price_dis.png)

* The size and the number of bathrooms and bedrooms are highly left-skewed because there are a few exceptionally large houses. Accordingly, the price is highly left-skewed.

* Most houses in king county have been built since 1960, so it shows right skewed distribution.

* Most houses in king county have not been renovated.

### Correlation of Continuous Features

![cor_price](images/cor_price.png)

Multicolinearity is present when we include 'sqft_living15','sqft_lot15', 'sqft_living', and 'sqft_above'. the coefficient is higher than 0.7. Therefore, these features will be removed to develop linear regression model.
