# Loptop-price-prediction-end-to-end-project-using-ecommerce-website-data
In this project, I tried to create a model that can predict the price of a laptop based on the criteria of the desired laptop by using the data of the available laptops that I collected from the Digikala website, the largest e-commerce site in Iran.

***Note: Since the price of laptops in Iran is constantly changing, this model is trained based on the data of laptops available on 11-06-2022 (8-15-1401) in Digikala. And in the coming years, it may not have an accurate prediction, and the solution to this problem is to update the model with the most up-to-date data.***


Watch Demo here : 
https://loptop-price-prediction.herokuapp.com/


![alt Text](https://github.com/meysamraz/laptop-price-prediction-end-to-end-project-using-ecommerce-website-data/blob/master/src/preview.gif)

<p><img src="src/demo.png" alt=""></p>

# Project Overview : 

## 1 - Collect Data 
- #### Collect Laptop main data 
- #### Collect Laptop details data
- #### Merge Collected data
- #### Remove duplicated rows 
- #### Save data into csv file 

## 2 - Take a look at data :
- #### Check shape of data 
- #### Check is there any null value
- #### Check data types
- #### Check number of unique values in each column

## 3 - Cleaning data 
- #### Convert brands name from persian to english
- #### Convert ram from persian to english digits
- #### Clean and convert internal storage to english
- #### Convert and clean internal storage to english
- #### Convert and clean laptops screen size
- #### Clean laptops resolution

## 4 - EDA 
- #### Laptops price distribution
- #### Number of laptops of each brand
- #### Number of cpu of each cpu manufacturer
- #### Number of laptops for each ram group 
- #### Number of laptops for each ram type group
- #### Number of laptops with diffrent internal storage
- #### Number of laptops for each internal storage group
- #### Number of laptops with diffrent screen sizes
- #### Number of laptop with diffrent screen resolution


## 5 - Feature Engineering
- #### Remove outliers base on laptops price using z score
- #### Convert screen resolution to number
- #### Extract Gaming brands from title (asus rog , acer nitro ...)
- #### Remove brand with only one laptop
- #### Extract clean gpu model from gpu model column
- #### Remove laptops with only less than 3 model gpu
- #### Label endcoding cleand gpu models
- #### Convert internal storage from tb and gb to mg
- #### Label encoding internal storage type
- #### Convert ram from str to int
- #### Extract port count
- #### Label encoding ram type
- #### Label encoding cpu series
- #### One hot encoding brand - cpu manufacturer - gpu manufacturer (nominal categorical variables)


## 6 - Feature Selection
- #### Check correlation
- #### Mutual information regression

## 7 - Model training  


## 9 - Cross validation

## 10 - Save model
