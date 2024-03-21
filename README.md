# Starbucks-Customers-Response-Prediction

## Medium Blog Post
https://medium.com/@yaser.ahmad.jaber/predicting-starbucks-customers-response-to-offers-773232afa58a

## Project Overview
The Starbucks Capstone Challenge is part of Udacity's Data Science Nanodegree program. This project explores transaction, demographic, and offer data from Starbucks' mobile app to predict customer response to promotional offers. The goal is to understand customer behavior and to optimize marketing strategies by sending targeted offers to customers most likely to respond.

## Problem Statement
The primary objective is to predict whether a customer will complete an offer sent through the Starbucks app. By analyzing customer profiles and their interactions with previous offers, we aim to identify key factors influencing offer completion and leverage this insight to improve future marketing efforts.

## Datasets
The project uses simulated data provided by Starbucks, which mimics customer behavior on the app. The data is divided into three files:

portfolio.json - containing offer ids and metadata (duration, type, etc.).

profile.json - demographic data for each customer.

transcript.json - records for transactions, offers received, offers viewed, and offers completed.

## Installation
This project requires Python 3.10 and the following Python libraries installed:

NumPy

pandas

Matplotlib

Seaborn

scikit-learn

XGBoost

## File Descriptions
Starbucks_Capstone_notebook.ipynb: Jupyter notebook containing the data analysis and modeling.

data/: Folder containing the dataset files.

data/portfolio.json - containing offer ids and metadata (duration, type, etc.).

data/profile.json - demographic data for each customer.

data/transcript.json - records for transactions, offers received, offers viewed, and offers completed.


## Evaluation Metrics
The project focuses on the recall score as the primary evaluation metric, emphasizing the model's ability to correctly identify as many actual positive cases (offer completions) as possible.

## Data Preprocessing
Data preprocessing steps included handling missing values, encoding categorical variables, and feature scaling. Detailed explanations and code for these steps are provided in the notebook.

## Data Modeling
An XGBoost classifier was trained to predict offer completion with a focus on maximizing the recall score. The model achieved an 86% recall score, indicating its effectiveness in identifying customers likely to respond to offers.

## Licensing, Authors, Acknowledgements
This project was completed as part of the Udacity Data Science Nanodegree program. The data was provided by Starbucks. Feel free to use the code as you please with attribution to the original author.
