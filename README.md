# Discussion Detox
## Multilingual Machine Learning algorithms to identify toxic comments on the internet

#### Data Sience Capstone Project with the [Neue Fische](https://www.neuefische.de/) school and pool for digital talent.

This project is still in progress. 

![Parental Advisory Logo](https://media.npr.org/assets/img/2010/10/29/parental-advisory_custom-d61ea6192ebc478d3a7ff147dbbe3e884ebcb5ac-s800-c85.jpg)

# INTERNET RULE #1: Never read the comments.

How is it possible that the very democratic element of the internet - the comment section - has been turned into a tool of cruelty by so called *trolls*?

# Objective 

The goal of this project is to build a natural language model that classifies text input (social media comments) into toxic and non-toxic catetegories in multiple languages.

# Methods
In order to achieve this, I decided to go with pretrained representations like GloVE, [DistilBERT](https://huggingface.co/distilbert-base-multilingual-cased) and [LASER](https://research.fb.com/downloads/laser-language-agnostic-sentence-representations/). As a baseline model I chose logistic regression as a binary classifier. Furthermore, I deploeyed recurrent neural networks, particularly LSTM models, which are considered best suited for NLP tasks.

# Data

Google and Jigsaw provided the dataset for a kaggle competition. The data can be downloaded [here](https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification/overview).<br/>
*Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.*

# Data Science Lifecycle

The work process follows the data science lifecycle with adjustments:
+ Business Understanding
+ Data Minig
+ Data Cleaning 
+ Data Exploration
+ Feature Engineering
+ Predictive Modeling 
+ Data Visualization

# Files included:
1_EDA_Toxic_Comments <br/>
2_Feature_Engineering_Part2_Toxic_Comments <br/>
3_Baseline Model_Logistic_Regression_Toxic_Comments<br/>
4_Pipeline_Ensemble_Methods_Classic_Classifiers<br/>
5_LSTM_Model_with_GloVe_Toxic_Comments<br/>
6_Predictive_Modelling_with_BERT_multilingual<br/>
6.1_BERT_multilingual_downsized_data.ipynb<br/>
7_Predictive_Modelling_with_LASER_multilingual<br/>
Presentation Slides<br/>
8_nlp_preprocessing_for_AutoML_in_GCP.ipynb<br/>
