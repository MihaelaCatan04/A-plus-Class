# A+ Class presents: Twitter-o-nality Predictor

## Introduction
Everyone has certain likes, dislikes, quirks and idiosyncrasies — all the qualities that make up your personality, the things that make you you. That everyone has unique personalities makes life more interesting (or, sometimes, more difficult). But has it ever happened to you that an online pal or an influencer turned out to be have a different personality, other than you thought? If so, this project has been intended for you!

## Project Scope
The main goal of this program is to predict a person's personality based on his/her twitter posts. 

## Description
This project is made out of 4 Machine Learning Models that predict every letter of the personality type, which, in the end, are concatenated into an unic value.
### Exploratory Data Analysis
We have cleaned our dataset, dropped NaN values, removed duplicated rows, splitted the "post" column into multiple posts and the personality type into letters. Also, this parts includes Multivariate Analysis and Univariate Analysis.
### Preprocessing
The preprocessing part consists of deleting the rows that contain links and applying the NLTK tools: tokenization, stemming, stopwords extraction and punctuation removal. 
### Model Creation
We have used 4 Random Forest Models. In order to run them, you have to download the files from the repository and update the cells with the local paths.   

## How to use the program?
In order to predict the personality type, you have to copy-paste a tweet into the input cell, preprocess it, load the models and properly, predict it.

## Bibliography
You can acces the data set here: https://www.kaggle.com/datasnaek/mbti-type

## Author
Catan Mihaela, mentored by Oniciuc Oriana.
