# Flipkart-Review-Sentiment-Analysis
![image](https://github.com/Aftabbs/Flipkart-Review-Sentiment-Analysis/assets/112916888/d779bc6f-9f68-4a9b-9c06-728245c704c4)

## Overview
This project involves sentiment analysis of customer reviews from Flipkart, an e-commerce website. The analysis was performed using Jupyter Notebook, with various Python libraries for text processing, sentiment analysis, and visualization.

## Libraries Used
- pyforest
- nltk
- re
- os
- spacy

## Data Cleaning and Preprocessing
The text data was cleaned using regular expressions (re) and the following steps were performed:
- Removal of HTML tags
- Removal of special characters and numbers
- Conversion of text to lowercase
- Removal of stopwords using NLTK's list of English stopwords
- Stemming of words to their root form using NLTK's SnowballStemmer

## Sentiment Analysis
Sentiment analysis was conducted using NLTK's VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. The reviews were classified into three categories:
- Positive
- Negative
- Neutral

## Results
The sentiment analysis results are as follows:
- Positive: 924 reviews
- Negative: 97 reviews
- Neutral: 1284 reviews

## Visualizations
Several visualizations were created to better understand the data:
Word clouds to represent the most frequent words in positive, negative, and neutral reviews.
Bar charts to display the distribution of sentiment categories.

## Enhancements and Future Work
To further improve this project, consider the following enhancements:

- Advanced Text Processing: Implement more sophisticated text preprocessing techniques such as lemmatization.
- Feature Engineering: Extract additional features from the text data, such as bigrams and trigrams, to improve the sentiment analysis.
- Model Improvement: Experiment with different sentiment analysis models, such as machine learning classifiers (e.g., Naive Bayes, SVM) or deep learning models (e.g., LSTM, BERT).
- Interactive Visualizations: Use interactive visualization libraries like Plotly or Bokeh to create more engaging visualizations.
- Additional Data Sources: Incorporate reviews from other e-commerce platforms to compare sentiment trends across different websites.

## To Install Libraries
- pip install pyforest nltk wordcloud
Open the Jupyter Notebook and execute the cells to perform the sentiment analysis.

## Conclusion
This project provides insights into customer sentiment towards products on Flipkart. The analysis helps understand the distribution of positive, negative, and neutral sentiments, which can be useful for business decisions and improving customer satisfaction.

