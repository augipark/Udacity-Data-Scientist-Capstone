# Udacity-Data-Scientist-Capstone
Project #4 for Udacity's Data Science Nanodegree Program

## Project Motivation
The purpose of this project is to use customer data to help Starbucks become more profitable. The basic task is to use the data to identify which groups of people are most responsive to each type of offer, and how best to present each type of offer.

## Libraries and Installation
import pandas as pd
import numpy as np
import math
import json
import matplotlib.pyplot as plt

## Python Scripts
### 1. The ETL script: _process_data.py_
Takes the messages.csv and categories.csv files as input and then merges and cleans the dataset to be used for machine learning.
### 2. The machine learning script: _train_classifier.py_
Creates and trains a classifier using the data output from the ETL script.
### 3. The web app: _run.py_
Uses the trained model to display a web app. When a user inputs a message the web app, a classification result is output.

## File Descriptions 
1. README.md - read me file
2. portfolio.json - contains information about the types of offers offered by Starbucks
3. profile.json - contains demographic data for each customer
4. transcript.json - contains transactional data (i.e. records for offers received, offers viewed, transactions, and offers completed)
5. Starbucks_Capstone_notebook-Copy2.ipynb - notebook with data cleaning and preprocessing steps and final visualizations and outputs.

## Summary of the Results
In summary, sending discount and BOGO offers to customers tend to have the highest offer response rate. Informational offers see less success.
Please see the blog post here for more comprehensive documentation and results: https://medium.com/@augikpark/udacity-data-science-capstone-starbucks-project-e6af275bd742

## Acknowledgements 
Thank you to Udacity and Starbucks for providing the dataset to work with.
