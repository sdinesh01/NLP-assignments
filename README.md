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

0. What is the nature of our data?
  0a. What is the size of the corpus?
  0b. Are there any duplicates in the corpus? If so, drop them. -- source, title, text

  0c. Are there any missing values in the corpus?
  0d. How many unique documents are there in the corpus?
1. What is the distribution of tokens per document?
  1a. What is the longest article?
  1b. What is the shortest article?
  1c. What is the 95th percentile of article lengths?
2. How many different sources are there in the corpus?
  2a. How many different sources are there in the dataset?
  2b. What is the distribution of articles per source?
