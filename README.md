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

This project found that we can, with high accuracy, predict whether text belongs to one subreddit compared to the other 8 mental illness category subreddits. However, it is unclear whether this is the best approach to the problem. Although preliminary results are promising with the individual models, we have yet to build a multi-class model that has high prediction accuracy. 

Future directions include: 
- Continuing with the convolutional neural network models.
- Explore differences in posts pre and post covid shutdown.
- Tuning a model to achieve a higher accuracy score in discerning between all categories at once.
- Learning more about text classification and convolutional neural networks. 

### Project Repo Contents

**Main Contents:**
- Raw Data: The files are too large to store on this git repo, you can find the files stored [here](https://drive.google.com/drive/folders/10mQxBlSw-WP42Xnz3ehMS6ilqThiXQRT?usp=sharing)
- [Scrape Data](./notebooks/step1-scrape_and_clean_data.ipynb)
- [Pre-pocess Data](./notebooks/step2-pre-process_text.ipynb)
- [EDA Notebook](./notebooks/step3-EDA.ipynb)
- [XGBoost Models](./notebooks/step4-model-xgboost-classifier.ipynb)
- [Create Word2Vec](./notebooks/step5-word2vec.ipynb) - This notebook creates a text file which should output to the repo directory
- [CNN Models](./notebooks/step6-model-CNN.ipynb)

### References

Kim, J., Lee, J., Park, E., & Han, J. (2020). A deep learning model for detecting mental illness from user content on social media. Scientific Reports, 10(1), 1-6.

Chawla, N. V., Bowyer, K. W., Hall, L. O., & Kegelmeyer, W. P. (2002). SMOTE: synthetic minority over-sampling technique. Journal of artificial intelligence research, 16, 321-357.

https://news.mit.edu/2020/covid-19-impact-mental-health-1105

https://realpython.com/python-keras-text-classification/

https://machinelearningmastery.com/how-to-reduce-overfitting-with-dropout-regularization-in-keras/

https://towardsdatascience.com/boosting-techniques-in-python-predicting-hotel-cancellations-62b7a76ffa6c

https://israelg99.github.io/2017-03-23-Word2Vec-Explained/

https://radimrehurek.com/gensim/models/word2vec.html


