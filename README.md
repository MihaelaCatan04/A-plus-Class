# A+ Class presents: Twitter-o-nality | Rediscover People Around You

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
We have used 4 Random Forest Models. In order to run them, you have to download the files from the repository and update the cells with the local paths. Here is the link to the models for downloading: https://drive.google.com/drive/folders/1VROhiv83O8LLHxG_taYdRBBGHj99lGdl?usp=sharing 
### Architecture
![Untitled Diagram (7)](https://user-images.githubusercontent.com/66206241/120068658-7ec82d80-c08a-11eb-8d7a-424398b5a99d.png)



## Content
* Personality_Model_Creation.ipynb includes Data Import, Exploratory Data Analysis, Posts Preprocessing and Modeling.
* Personality_Prediction includes.ipynb includes Input Preprocessing, Input Reading and Prediction Obtainment.

## How to use the program?
In order to predict the personality type, you have to copy-paste a tweet into the input cell, preprocess it, load the models and properly, predict it. Use the Personality_Prediction.ipynb notebook.

## Bibliography
You can acces the data set here: https://www.kaggle.com/datasnaek/mbti-type

General Information about MBTI: https://en.wikipedia.org/wiki/Myers%E2%80%93Briggs_Type_Indicator

Presentation: (this will be added after the competition :] )

## Author
Mihaela Catan, mentored by Oriana Oniciuc.
