# TripAdvisor Sentiment Analysis

This project explores the **impact of data preprocessing techniques** on sentiment analysis of TripAdvisor hotel reviews. The study examines the role of text preprocessing methods, such as stemming and lemmatization, and evaluates various machine learning models to predict user sentiments and classify hotel ratings effectively.

## Overview

Understanding customer sentiments expressed in online reviews is crucial for the hospitality industry. This project focuses on analyzing TripAdvisor reviews to identify effective preprocessing strategies and model combinations for sentiment classification. It also investigates the impact of n-gram strategies on model performance.

### Key Features:
- Data preprocessing techniques: stemming, lemmatization, and stopword removal.
- Machine learning models: Logistic Regression, Support Vector Classifier (SVC), Decision Tree, and Random Forest.
- Evaluation of n-gram strategies for text feature engineering.
- Accuracy and performance comparison of preprocessing and modeling approaches.

## Dataset

- **tripadvisor_hotel_reviews.csv**: The dataset contains 20,000 hotel reviews from TripAdvisor, with textual reviews and their corresponding numerical ratings. It is publicly available under a CC-BY-4.0 license.

## Files in Repository

- **Report.ipynb**: Jupyter Notebook containing the code implementation, methodology, results, and visualizations for the project.
- **tripadvisor_hotel_reviews.csv**: Dataset used for sentiment analysis, containing 20,000 reviews and ratings.

## Methodology

1. **Data Preprocessing**:
   - Lowercasing text, removing punctuation, stopwords, and numbers.
   - Comparing stemming vs. lemmatization for text standardization.
   
2. **Feature Engineering**:
   - TF-IDF vectorization with various n-gram configurations (unigrams, bigrams, and trigrams).
   
3. **Model Training and Evaluation**:
   - Logistic Regression was identified as the best-performing model, with an accuracy of **85.68%**.
   - Stemming slightly outperformed lemmatization for this dataset.
   - Unigram with all features offered the best accuracy but required higher computational resources.

4. **Results and Insights**:
   - Preprocessing strategies and simpler models like Logistic Regression can yield effective results for sentiment analysis.
   - Optimal n-gram strategies depend on balancing accuracy and computational efficiency.

## Findings and Future Work

- **Findings**:
  - Logistic Regression provided the most accurate predictions among models tested.
  - Stemming is a practical preprocessing technique, showing slight improvement over lemmatization.
  - Unigrams with all features are accurate but computationally intensive.

- **Future Work**:
  - Explore advanced NLP techniques such as deep learning models.
  - Investigate scalability of methods for larger datasets.
