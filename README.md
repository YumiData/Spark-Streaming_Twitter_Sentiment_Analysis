# Spark-Streaming Twitter Sentiment Analysis

## Project Overview
Our approach to making Twitter sentiment predictions is to first train a Naive Bayes model using a labeled dataset available on Kaggle. We then save the trained model and will load and use it subsequently in a streaming application (in a different notebook).

## Analysis Process
1. Download and explore data
2. Data cleaning and target variable transformation
3. Define and fit a ML pipeline containing data preprocessing and model training
4. Train the pipeline
5. Obtain the accuracy of the model using our predefined evaluator
6. Save the model on DBFS
7. Test the saved model
