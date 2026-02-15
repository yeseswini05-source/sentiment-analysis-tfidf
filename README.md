# Sentiment Analysis using TF-IDF and Naive Bayes

## Overview

This project implements an end-to-end sentiment analysis pipeline using TF-IDF vectorization and a Multinomial Naive Bayes classifier. The model classifies product reviews into three categories: positive, neutral, and negative.

The project demonstrates text preprocessing, feature extraction, supervised learning, model evaluation, and result visualization.

---

## Features

* Dataset creation and preprocessing using Pandas
* Text normalization and feature engineering
* TF-IDF vectorization for numerical representation of text
* Train/test split with stratified sampling
* Multinomial Naive Bayes classification
* Model evaluation using accuracy score and classification report
* Confusion matrix heatmap visualization using Matplotlib

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## Project Structure

```
sentiment-analysis-tfidf/
│
├── sentiment_analysis.py
├── requirements.txt
└── README.md
```

---

## How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/sentiment-analysis-tfidf.git
cd sentiment-analysis-tfidf
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the script:

```
python sentiment_analysis.py
```

---

## Model Pipeline

1. Generate sample dataset of labeled reviews
2. Perform data cleaning and preprocessing
3. Convert text data into numerical features using TF-IDF
4. Split data into training and testing sets
5. Train Multinomial Naive Bayes classifier
6. Evaluate model performance
7. Visualize confusion matrix

---

## Results

The model outputs:

* Accuracy score
* Detailed classification report (precision, recall, F1-score)
* Confusion matrix heatmap for performance visualization

---

## Future Improvements

* Compare with Logistic Regression and Support Vector Machines
* Use real-world datasets such as IMDb or Amazon reviews
* Implement cross-validation
* Deploy as a web application using Streamlit or Flask

