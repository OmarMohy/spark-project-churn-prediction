# spark-project-churn-prediction
Udacity Data Science Capstone Project


## Table of contents
* [Dataset](#dataset)
* [Context](#context)
* [Files](#files)
* [Setup](#setup)
* [Results](#results)

## Dataset
This data is taken from Udacity from data science nanodegree program for the capstone project.                    
There are 286000 logs for 225 customers activities on the service in this dataset. 

## Context
Imagine you are working on the data team for a popular digital music service similar to Spotify or Pandora. Millions of users stream their favorite songs to your service every day either using the free tier that place advertisements between the songs or using the premium subscription model, where they stream music as free but pay a monthly flat rate. Users can upgrade downgrade or cancel their service at any time. 

This data contains the key insights for keeping the users happy and helping the business thrive.

The target is to predict which users are at risk to churn either downgrading from premium to free tier or cancelling their service altogether. If you can accurately identify these users before they leave the business can offer them discounts and incentives potentially saving the business millions in revenue.

## Files
*mini_sparkify_event_data.json*: The 125 MB data file                                                    
*Sparkify.ipynb*: The code steps


## Setup
This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. It is highly recommended that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks. The following libraries are expected to be used in this project:

* Pyspark
* NumPy                                         
* pandas                                                   
* Matplotlib                                 
* Seaborn                                      

## Results
Random Forrest Classifier were used to predict churn users and got a 76% F1-Score and 57% AUC score.                          
You can find detailed steps and results at my medium blog post link https://omarmohyeldin.medium.com/predict-customer-churn-using-pyspark-aa9d1a46f642
