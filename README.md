# NLP-assignments
Completed coding assignments for DATA 340 Natural Language Processing

### Webscraping 2/21
packages: requests, re, beautifulsoup4, nltk, pandas, numpy, matplotlib, sklearn
  1.  Write a function that takes a URL as input and returns the HTML of the page as a string. 
  2.  Inspect the HTML of the page and use regular expressions to extract the documents within the page. 
  3.  Model the documents in a corpus 
  4.  Analyze the corpus using the bag of words model 
  5.  Implement a TF-IDF model to extract the most n-important words for each document in the corpus. 

### Exploratory Data Analysis 3/6
packages: pandas, numpy, matplotlib, seaborn, spaCy

Analyze a corpus of news documents to answer the following:

What is the nature of our data?
1. What is the size of the corpus?
2. Are there any duplicates in the corpus? If so, drop them. -- source, title, text
3. Are there any missing values in the corpus?
4. How many unique documents are there in the corpus?
 
What is the distribution of tokens per document?
1. What is the longest article?
2. What is the shortest article?
3. What is the 95th percentile of article lengths?

How many different sources are there in the corpus?
1. How many different sources are there in the dataset?
2. What is the distribution of articles per source?

### Naive Bayes 3/24
packages: spacy, nltk, pandas, numpy, seaborn, sklearn

Train a Naive Bayes model on the [Sentiment Analysis on Movie Reviews](https://www.kaggle.com/competitions/sentiment-analysis-on-movie-reviews/overview). The dataset contains 15,000 movie reviews
  - objectives: feature engineering, training Naive Bayes models, evaluating model performance, exploring model limitations.
  
 ### Logistic Regression 3/31
 packages: numpy, pandas, spacy, seaborn, sklearn
 
 Train two logistic regression models on the [IMDB Movie Review Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). One model is trained on noun and adjectivial phrases and the other on verb and adverbial phrases. Compare the performance of both models. 
 - objectives: feature engineering, logistic regression training, performance evaluation, analysis.
 
