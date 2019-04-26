# CMPE256Project
CMPE 256 Spring 2019 Large-Scale Analytics

Project Title ：HappyDB Prediction

Team Happy
Members:
Fulbert Jong
Min Lu

Project Overview
We are going to use the happyDB database for this project. The database consists of the happy moments description and user demographic. By using classification techniques, we will try to predict gender/marriage status/parenthood groups based on happy moment texts. 

Resources/Datasets to be used
HappyDB:
https://www.kaggle.com/ritresearch/happydb
cleaned_hm.csv: the cleaned-up corpus of 100,000 crowd-sourced happy moments. Includes 101K rows x 9 columns.
demographic.csv: the demographic information of the worker who provided the moment. The information includes worker id, age, country, gender, marital status, and status of parenthood.Includes 10.8K rows x 6 columns.

Project Description 
In order to predict gender/marriage status/parenthood groups based on happy moment texts, we have to build a classification model to group people into different classes, basing on features of their clean_hm text. 
Things we will learn by working on the project:
How to preprocess text and investigate the important features of a dataset.
How to use KNN to classify data based on the features.
How to determine the model for predictions from unseen data.
How to evaluate a model’s performance on imbalanced data.

Project Process
Step 1: Preprocessing data
We will preprocess the cleaned_hm text, delete all the stop words and the words less than 4 characters . 
Step 2: Feature selected
We will put people in the train set to different groups based on the gender/marriage status/parenthood. Then we will make a words dictionary for each group.
Step 3: Techniques/Methodology
We will use KNN and other algorithms to classify people in test set based on the words of their cleaned_hm text.
Step 4: Test and Validation Method
The F1 score and accuracy will be used to measure a test’s accuracy, compare the performance and select the best algorithm to build the classification model.


