# NLP, Deep Learning, & Reddit Project

### Contents:
- [Background](#Background)
- [Problem Statement](#Problem-Statement)
- [Research Questions](#Research-Questions)
- [Executive Summary](#Executive-Summary)
- [Project Repo Contents](#Project-Repo-Contents)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [References](#References)

### Background 
Having a mental health issue can be a confusing and isolating experience. One way individuals seek information and support is through social media forums such as Reddit. People often share their emotions looking for connection or somewhere to just voice their feelings. This presents an opportunity for researchers to learn more about how those with emotional pain and/or a psychiatric illness may reach out for help, what words they use, and what type of language is more characteristic of one illness over another. The use of NLP in analyzing support communities for psychiatric illness can help us gain insight into hard to understand diseases in order to offer better support for patients.

### Problem Statement  
Building on a previous project using Natural Language Processing (NLP) to analyze texts from two subreddits r/Anorexia and r/Bulimia and further inspired by a Nature Scientific Report paper titled "A deep learning model for detecting mental illness from user content on social media", this project aims to employ a Convolutional Neural Network (CNN) classification model based on user comments from Reddit to identify whether a user's post belongs to a mental illness subreddit category.

### Research Questions 
- Can we identify whether a user's post belongs to a mental illness subreddit category? 
- How have posts changed pre and post onset of covid-19?

### Executive Summary 
Still working on the project so this is more of a to-do list:
- Make sure I've added random seed to each analysis
- Add requirements.txt file
- Will further investigate whether the use of a CNN on each subreddit makes the most sense 
- Need to finish running the CNN models
- Whether SMOTE was the optimal way to handle class imblanace 
- Will go back and tune the XGBoost model changing the max depth 
- Would like to continue with EDA and look at pre- and post- covid onset
- Will provide more background context for the project including links and references to similar research

### Project Repo Contents

**Main Contents:**
- Raw Data: upon request - or use the code to scrape
- [Scrape Data](step1-scrape_and_clean_data.ipynb)
- [Pre-pocess Data](step2-pre-process_text.ipynb)
- [EDA Notebook](step3-EDA.ipynb)
- [XGBoost Models](step4-model-xgboost-classifier.ipynb)
- [Create Word2Vec](step5-word2vec.ipynb)
- [CNN Models](step6-model-CNN.ipynb)
