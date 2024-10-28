# Project: Sentiment Analysis on E-commerce Product Reviews

## Description
This project performs sentiment analysis on customer reviews from an e-commerce platform, using a Naive Bayes model to classify reviews as positive, neutral, or negative.

## Objectives
- Analyze customer reviews to understand overall sentiment.
- Use machine learning models to classify reviews into positive, neutral, or negative categories.
- Provide insights to improve product offerings and customer satisfaction.

## Data
The dataset contains simulated product review data, including:
- Review text describing customer feedback.
- Ratings from 1 to 5 stars, indicating customer satisfaction.
- Sentiment labels derived from the ratings (positive, neutral, negative).

## Methodology
1. **Data Preparation:** Load and preprocess the review data, adding sentiment labels based on ratings.
2. **Exploratory Data Analysis:** Analyze sentiment distribution, rating trends, and correlations.
3. **Modeling:** Train a Naive Bayes model to classify review sentiments.
4. **Evaluation:** Use metrics like accuracy, confusion matrix, and ROC curve to evaluate model performance.
5. **Visualization:** Generate visualizations for sentiment distribution, ratings, and model performance.

## Results
The model achieved the following performance metrics:
- **Accuracy:** Measures the proportion of correct predictions.
- **Confusion Matrix:** Displays true vs. predicted sentiments for each category.
- **ROC Curve:** Plots the true positive rate against the false positive rate.

## How to Run
1. Ensure all dependencies are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn fpdf nbformat
   ```
2. Run the main script to execute the project:
   ```bash
   python sentiment_analysis.py
   ```

## Recommendations
- Use a larger, real-world dataset for better model accuracy and insights.
- Incorporate more advanced NLP techniques like TF-IDF or Word2Vec for feature extraction.
- Experiment with other machine learning models, such as Random Forests or Logistic Regression.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- fpdf
- nbformat

