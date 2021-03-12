# NLP, Deep Learning, & Reddit Project

### Contents:
- [Problem Statement](#Problem-Statement)
- [Background](#Background)
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

### Project Repo Contents

Before running the notebooks below you can find the software requirements here: [requirements file](requirements.txt) (NEED TO ADD THIS)

**Main Contents:**
- [Raw Data]: upon request - or use the code to scrape
- [Scrape Data](step1-scrape_and_clean_data.ipynb)
- [Pre-pocess Data](step2-pre-process_text.ipynb)
- [EDA Notebook](step3-EDA.ipynb)
- [XGBoost Models](step4-model-xgboost-classifier.ipynb)
- [Create Word2Vec](step5-word2vec.ipynb)
- [CNN Models](step6-model-CNN.ipynb)
