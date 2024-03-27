# Chat Harassment Detection Hackathon

This repository contains the code and Persian report for the Divar platform's Health Hackathon, aimed at detecting harassment in user chats using NLP techniques. Divar is a classified ads and e-commerce online platform in Iran, boasting 30 million monthly active users. The chat data used for this project belongs to Divar.

In this hackathon, I secured the 6th position out of 50 competitors, achieving a model accuracy of 90%.

The notebook is also available on Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iWFmz-VUbeGX8-ueXcE7kLRK_hFGu4KJ?usp=sharing)

## Notebook Table of Contents

- **Setup Environment**: Preparing the necessary environment for the project.
- **Load and Read Data**: Loading the chat data for analysis.
- **Data Preprocessing and EDA**:
    - Extract Messages: Extracting messages from the dataset.
    - Post Title WordCloud: Visualizing frequent words in post titles.
    - Post Categories: Analyzing the categories of posts.
    - Normalize Texts: Normalizing text data for consistency.
    - Word Tokenize: Tokenizing words for further analysis.
    - Swear Extraction: Identifying swear words in the dataset.
    - Remove Stopwords: Eliminating common stopwords.
    - Stemming & Lemmatization: Reducing words to their base forms.
    - Check #Words Distribution: Analyzing the distribution of word counts.
    - Choosing Initial Features: Selecting initial features for the model.
    - Split Data: Splitting the data into training and testing sets.
    - TF-IDF Vectorizer: Converting text data into TF-IDF features.
    - Feature Selection with Chi-Squared: Selecting relevant features using the Chi-Squared test.
- **Model Data**:
    - Machine Learning Algorithm Selection and Initialization: Choosing and initializing the appropriate machine learning algorithms.
    - Tune Model with Hyper-Parameters: Fine-tuning the model with hyperparameter optimization.
    - Final Model and Competition Submission: Finalizing the model and preparing for competition submission.
