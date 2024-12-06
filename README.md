# Sentiment Analysis on E-Commerce Reviews

## Project Overview

This project focuses on developing a sentiment analysis system that leverages natural language processing (NLP) techniques to classify e-commerce reviews as positive or negative. By analyzing sentiments expressed in customer reviews, businesses can gain valuable insights into customer satisfaction and product performance.

## Project Objectives

### Create Various Sentiment Analysis Pipelines:

1. **Text → VADER:** Utilizing VADER for sentiment analysis without preprocessing.
2. **Text → Remove Stopwords → VADER:** Enhancing VADER by cleaning the text.
3. **Text → Remove Stopwords → Bag of Words → Custom Model:** Employing a Multinomial Naive Bayes classifier.
4. **Text → Remove Stopwords → TF-IDF → Custom Model:** Using TF-IDF vectors with a custom classifier.

### Model Evaluation:

Assess each model's performance through various metrics, including accuracy, precision, recall, and F1-score.

## Methodology

1. **Data Collection:** Utilized datasets containing e-commerce reviews, which were loaded into Python for analysis.
2. **Data Preprocessing:** Essential preprocessing steps included tokenization and the removal of stopwords to enhance the quality of the text data.
3. **Feature Engineering:** Created two main feature representations: Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF) for training various machine learning models.
4. **Model Training:** Employed both VADER for sentiment scoring and Multinomial Naive Bayes for classification. Each model was trained and evaluated based on its predictive accuracy.

## Dataset

The dataset used in this project is sourced from [amdari.io](https://amdari.io) and contains:
- **3.6 million rows for the training data**
- **400,000 rows for the test data**

## Results

The evaluation of the models yielded notable results:

- **VADER Analysis:** Accuracy of approximately **72%**.
- **VADER with Stopwords Removed:** Accuracy of around **68%**.
- **BoW with Multinomial Naive Bayes:** Best accuracy achieved was **85%**.
- **TF-IDF with Multinomial Naive Bayes:** This model yielded an accuracy of **83%**.

## Conclusion

This project successfully illustrated the effectiveness of multiple approaches to sentiment analysis, with the highest performance stemming from the pipeline involving stopword removal followed by Bag of Words features processed through the Multinomial Naive Bayes classifier.


## Future Work

Future enhancements may include extending the analysis to multilingual reviews and investigating advanced modeling techniques, such as BERT, to further improve accuracy and contextual understanding.


## Acknowledgments

