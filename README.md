# Analysis of Twitter Data on Women's Safety
A ML model that analyzes Twitter data to uncover patterns, sentiments, and discussions related to women's safety. Includes data processing, sentiment analysis, and visualization of key trends and hotspots.

![Picture1](https://github.com/user-attachments/assets/e20dbf63-c159-4474-86e0-d969d874615b)

## Introduction
---
### Women Inclusion and Safety in Society

- The inclusion and safety of women in modern society is a problem that over the years has become increasingly important in all countries, leading to a large number of awareness campaigns and social movements. 
- Several investigations were held mainly focusing on interpreting the behaviors of people, also according to their geopolitical situations, for preventing and reducing discrimination situations against women.
- Women often feel aggressive harassment which includes trolling, stalking and making sexist remarks.
  
![image](https://github.com/user-attachments/assets/ad8eb00d-2dff-4ce7-8fce-dbe91fac8414)


### Role of Twitter

- Twitter is the most popular platform among numerous microblogging platforms that are available on the internet where people share their opinions, ideas, and messages with a limit of 280 characters called “tweets”. 
- Twitter provides a platform to spread information worldwide. Millions of tweets are posted on Twitter every day from all over the world. 
- Each tweet expresses an opinion and opinion on the topic. These tweets help to carry out social awareness, product promotion, social issues, and health issues. 

Therefore, twitter conversations can be  used to analyze the sentiments of people about women’s issues which are very critical issues in our society.

![image](https://github.com/user-attachments/assets/eefc4aa0-e4bd-4d8c-aaca-8e2a5d5cf6dc)


## Objective
---
- To highlight the rising issue of  inclusion and safety of women in modern society by analyzing the opinions, behavior and sentiments of people through tweets.
- To investigate the assorted wrongdoings against the ladies by making use of preferred and powerful social media data with the help of specific keywords and hashtags.
- To show true insights and educate people about the sensational expansion in the quantity of wrongdoings against women in the form of a web application.

## Methodology
---
1. **Data Collection**: Twitter Scraper and the data world website is used for collecting the dataset of tweets.
2. **Preprocessing**: Once tweets are collected, tweets are pre-processed to remove unnecessary noise.
4. **Sentiment Analysis**: With the help of Text Blob and VADER labeled each tweet as Positive, Negative, and Neutral. Also, emotions will be analyzed using Text_to_Emotion library.
5. **Classifiers**:  The model goes through different types of classifiers to get the most accurate model, hence, comparative analysis is done between Support Vector Machine (SVM), Random Forest, Naive Bayes and Logistic Regression models.
6. **Visualization**: An in-depth visualization will be done with respect to geographical analysis of data.
7. **Model Deployment**: The model will be deployed into a web application using Streamlit to make it easier to analyze and visualize.

![image](https://github.com/user-attachments/assets/e3c264f5-16f3-4658-a636-cb6abf36abed)

## Results
---
### Comparative Analysis of Different Classifiers

The accuracy of Naive Bayes is 90.77%, Logistic Regression is 95.62%, Random Forest is 96.28% and Support Vector Machine is 96.41%. 

Therefore, the best accuracy amongst all  is of Support Vector Machine classifier.

![image](https://github.com/user-attachments/assets/b076b1ff-fa50-4443-842d-f8dac69f1d42)

### 1. Home Page
The home page of the model let's us to upload the tweets file. Make sure the tweets file consists of preprocessed and cleaned data for better accuracy.

![image](https://github.com/user-attachments/assets/fe745cd6-dc93-4b35-8e9a-8c2770121b7f)

### 2. Sentiment Analyzer Page
The sentiment analyzer let's us choose the type of sentiment analyzer we want to choose for our analysis.

![image](https://github.com/user-attachments/assets/f4b39320-6fe9-4c1c-af69-9ea02b61fd9b)

### 3. Data Analysis Page 
The data analysis page consists of detailed analysis of the data consiting of various charts depicting different measures and KPI's.

![image](https://github.com/user-attachments/assets/ef5d9941-aeb9-4d2b-b098-b0969f97697a)


### 4. Visualization Page
The visualization page let's you visualize the data and the accuracy of the model you chose, including the others you could have choosen and shows the best typeof classifier for the data.

![image](https://github.com/user-attachments/assets/4d5693f9-ccb5-4737-913e-b5c2862026ba)


