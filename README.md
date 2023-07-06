# Fake News Detection using Machine Learning

![Fake News](https://img.shields.io/badge/Fake%20News-Detector-red)
![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
![Scikit-learn Version](https://img.shields.io/badge/scikit--learn-0.24.2-orange)

This project focuses on detecting fake news using machine learning techniques. With the rapid spread of information through social media and online platforms, distinguishing between real and fake news has become increasingly important. The goal is to implement a supervised learning model that can effectively identify and classify news articles as real or fake.

## Project Idea
Fake news has become a pervasive issue in today's era, where misinformation spreads rapidly, potentially influencing public opinion and decisions. This project aims to tackle the challenge of differentiating between genuine and fabricated news articles using machine learning techniques. By leveraging the power of supervised learning, we can train a model to automatically classify news articles and provide users with a reliable indicator of their authenticity.

## Dataset
The dataset used for this project is called news.csv. It comprises 7,796 news articles with the following features:

### News: 
Identification of the news article
### Title: 
Title of the news article
### Text: 
Content of the news article
### Label: 
Denotes whether the news is real or fake

## Approach
### 1. Preprocessing:
Data preprocessing steps are performed, including text cleaning, removal of irrelevant information, and handling missing values.

### 2. Feature Extraction:
The TF-IDF (Term Frequency-Inverse Document Frequency) technique is utilized to convert the textual data into a numerical representation suitable for machine learning algorithms.

### 3. Model Building:
A PassiveAggressiveClassifier algorithm, a type of online learning algorithm, is employed to train the model on the labeled dataset.

### 4. Model Evaluation:
The model's performance is evaluated using accuracy score and confusion matrix metrics. This allows assessment of the model's ability to correctly classify news articles as real or fake.

## Dependencies
To run this project, ensure you have the following dependencies installed:

Python 3.7 or above

Scikit-learn 0.24.2

## Results
After training the model, an accuracy of 93.21% was achieved in classifying news articles as real or fake. This indicates the effectiveness of the approach in accurately detecting fake news. By leveraging machine learning techniques and natural language processing, the project contributes to the ongoing efforts in combating misinformation and promoting information integrity.

## Contribution
🌟 Contributions to this project are welcome and encouraged! 🌟

If you would like to contribute, we appreciate your effort and support. Here's how you can get started:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name.
3. Make the necessary changes and improvements in your branch.
4. Test your changes thoroughly.
5. Submit a pull request to the original repository.

🙌 Thank you for your valuable contribution and for being a part of this project's growth! 🙌
