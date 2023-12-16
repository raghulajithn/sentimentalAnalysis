# Sentiment Analysis for Movie Reviews

## Abstract

Sentiment analysis has become a crucial component in natural language processing, offering insights into the emotional tone of textual content. In this project, we perform sentiment analysis on a dataset of movie reviews using machine learning techniques.

We utilize a dataset containing 50,000 movie reviews from IMDb, classifying them as either positive or negative sentiments. The analysis involves exploratory data analysis (EDA), data preprocessing, and the implementation of machine learning models. We focus on using the Complement Naive Bayes (CNB), Multinomial Naive Bayes (MNB), and Bernoulli Naive Bayes (BNB) algorithms to classify reviews based on sentiment.

## Import Libraries

The project leverages various Python libraries for data manipulation, analysis, and visualization, including pandas, matplotlib, plotly, wordcloud, nltk, and scikit-learn.

## Import the Dataset

The IMDb dataset, containing movie reviews and corresponding sentiments, is imported using the pandas library.

## Exploratory Data Analysis (EDA)

Exploratory data analysis is performed to understand the structure and characteristics of the dataset. This includes checking data types, handling missing values, and visualizing key statistics and distributions.

## Preprocessing

The preprocessing steps involve cleaning the text data by converting it to lowercase, removing URL links, special characters, punctuations, numbers, and emojis. Additionally, short forms are replaced with their full forms, and stop words are removed.

## Tokenization and Lemmatization

The text data is tokenized into words, and lemmatization is applied to convert words to their base forms. This step is crucial for creating meaningful features for machine learning models.

## Feature Engineering

The dataset is processed to remove frequent words, and the most common words are visualized using bar plots. This helps in understanding the distribution of words in positive and negative reviews.

## Model Implementation

Three Naive Bayes models—Complement Naive Bayes (CNB), Multinomial Naive Bayes (MNB), and Bernoulli Naive Bayes (BNB)—are implemented to classify the sentiment of movie reviews.

## Model Evaluation

The models are evaluated based on accuracy, confusion matrix, and classification reports. The performance of each model is analyzed to determine its effectiveness in sentiment classification.

## How to Run Locally

1. **Clone the repository:**

```bash
git clone https://github.com/raghulajithn/sentimentalAnalysis.git
```
2.**Navigate to the project directory:**
```bash

cd sentimentalAnalysis
```
3.**Install the required libraries:**
```bash
pip install pandas matplotlib plotly nltk wordcloud scikit-learn
```
4.**Run the Jupyter Notebook or Python script:**
```bash
python sentimentAnalysis.py
```

## Conclusion
Sentiment analysis on movie reviews provides valuable insights into audience reactions. The project demonstrates the application of machine learning techniques for sentiment classification, allowing users to understand and analyze sentiments expressed in textual content. Customize and extend the project to suit specific requirements and explore additional techniques for further improvements.
