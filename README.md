*A regressor model to predict youtube videos conversion rate #catboostRegressor #sklearn*

# YouTube Video Conversion prediction model

This project is a YouTube video engagement and conversion prediction system developed in `code.ipynb`. The goal of this project is to build a machine learning model that can predict videos conversion to brands looking for influencers. 

## Project Overview

The project involves the following steps:
1. **Data Preprocessing**: Cleaning and preparing the data for analysis.
2. **Data Visualisation**: Quick EDA
3. **Model Training**: Developing and training a regression model.
4. **Evaluation**: Assessing the performance of the model. 

## The dataset

A sample of **fake, generated data** (555 rows) - each row represents one sponsored video with conversion count
(and calculated conversion rate) and a small selection of potential features that could be used to
predict conversion rate:

- channel_id - youtube channel/influencer id
- video_id - sponsored video id
- published_at - date sponsored video published
- views - views of the sponsored video
- conversions - a raw count of sales attributed to the video used to calculate the
conversion rate
- conversion_rate - (conversions + 1) / views
- subscribers - count of people subscribed to the channel
- median_past_views - median views from the channels last 10 videos
- median_past_views_per_subscriber - median views divided by subscribers from the
channels last 10 videos
- median_past_comments - median comments from the channels last 10 videos
- median_past_comments_per_view - median comments divided by views from the
channels last 10 videos
- median_past_likes_per_dislike - median likes divided by dislikes from the channels last
10 videos
- median_past_likes_per_view - median likes divided by views from the channels last 10
videos
- average_retention - average number of videos a commenter commented on from the last
10 videos


## Model Description

The predictive model is built using catboost library. I used a catBoostRegressor model, I first tested the performance of a straight-forward approach with Linear Regression. I then used GridSearch and cross validation to tune and evaluate my model. Finally analysed residuals. 

## Features
✅ Uses **S`pandas`: For data manipulation and analysis** 
✅ Uses **`scikit-learn`: For machine learning algorithms and evaluation metrics** 
✅ Uses **`catboost` for building the regression model.**  


## Conclusion

This project demonstrates the development of a YouTube video recommendation system using collaborative filtering techniques. The model can be further improved by incorporating additional features and exploring other recommendation algorithms.


## Contact
If you have any questions, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/lilianmartin4/) 🚀
