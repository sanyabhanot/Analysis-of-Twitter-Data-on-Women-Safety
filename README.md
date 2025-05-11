# Analysis of Twitter Data on Women's Safety
A ML model that analyzes Twitter data to uncover patterns, sentiments, and discussions related to women's safety. Includes data processing, sentiment analysis, and visualization of key trends and hotspots.

![Picture1](https://github.com/user-attachments/assets/e20dbf63-c159-4474-86e0-d969d874615b)

## Introduction
---
### Women Inclusion and Safety in Society

- The inclusion and safety of women in modern society is a problem that over the years has become increasingly important in all countries, leading to a large number of awareness campaigns and social movements. 
- Several investigations were held mainly focusing on interpreting the behaviors of people, also according to their geopolitical situations, for preventing and reducing discrimination situations against women.
- Women often feel aggressive harassment which includes trolling, stalking and making sexist remarks.
  
![image](https://github.com/user-attachments/assets/a96fc628-7c6a-41d9-99da-2b0899879576)

### Role of Twitter

- Twitter is the most popular platform among numerous microblogging platforms that are available on the internet where people share their opinions, ideas, and messages with a limit of 280 characters called “tweets”. 
- Twitter provides a platform to spread information worldwide. Millions of tweets are posted on Twitter every day from all over the world. 
- Each tweet expresses an opinion and opinion on the topic. These tweets help to carry out social awareness, product promotion, social issues, and health issues. 

Therefore, twitter conversations can be  used to analyze the sentiments of people about women’s issues which are very critical issues in our society.

![image](https://github.com/user-attachments/assets/9c2f2b3d-06fc-4b77-8e92-f901543e1125)

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
![image](https://github.com/user-attachments/assets/787bff5e-9221-4808-91f6-0ead3aed7bcc)

## Results

### Comparative Analysis of Different Classifiers

The accuracy of Naive Bayes is 90.77%, Logistic Regression is 95.62%, Random Forest is 96.28% and Support Vector Machine is 96.41%. 

Therefore, the best accuracy amongst all  is of Support Vector Machine classifier.

![image](https://github.com/user-attachments/assets/2e4d7594-72b4-4187-8f47-3601f6a4dfbf)


