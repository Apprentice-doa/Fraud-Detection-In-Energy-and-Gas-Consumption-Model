# Fraud Detection Model in Electricity and Gas Consumption
## Introduction
The Tunisian Company of Electricity and Gas (STEG) is a public and a non-administrative company, it is responsible for delivering electricity and gas across Tunisia. The company suffered tremendous losses in the order of 200 million Tunisian Dinars due to fraudulent manipulations of meters by consumers.

Using the client’s billing history, the aim of the project is to detect and recognize clients involved in fraudulent activities.

The project will enhance the company’s revenues and reduce the losses caused by such fraudulent activities.
### N.B: This is a winning solution to the IndabaX Nigeria 2023 hackathon.

## Problem Statement
The project aimed at using client and transactional data to classify whether a client is involved in fraudulent transaction. Through the application of advanced Machinel Learning and programming Techniques like: 
+ Data Memory Reduction
+ Time Series Analysis
+ Features Engineering using Aggregations
+ Features Encoding and
+ Cross-validation.

This project involved an in-depth understanding of the dataset provided which invloved the domain-level understanding of the features and their relationships. It made use of memeory reduction techniques to reduce the data size so that it could efficiently run under the avaialble memory resource. Data preprocessing  began by the application of time-series analysis on the data which saw the time column properly trnasformed into the datetime format and the relevant time features extarcted. Aggregations of the features were performed to describe the relationships between the features and the categorical columns were encoded using features encoding techniques like: label encoding and one-hot encoding. These problem resolutions led to the training and validation of the model.

## Solution Overview
### Data preparation & preprocessing
The dataset was taken through several techniques starting from the reduction of the data size to reduce memory usage by the kernel. The time series analysis was used to preprocess the data and extract useful time and date features from the data. The presence of outliers was resolved by data correction and then features were transformed to the right data format.

### Features Engineering
Data Aggregation techniques was performed on the dataset using arithmetic operations for numerical features  and groupby for categorical features. 

### Data Encoding
Label encoding and One-Hot encoding were used encode the categorical features for proper representation of the features to the model. Duplicate data were then dropped and missing values were filled using the median value. It was noticed that the choice of median for filling the missing values gave the model eval score a significant boost than the mean value.

### Model Trainig, Validation and Evaluation
