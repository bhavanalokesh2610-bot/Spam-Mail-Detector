# Spam Mail Detector using Naive Bayes

## Overview

This project is a Machine Learning application that classifies SMS messages as **Spam** or **Ham (Not Spam)** using the Naive Bayes algorithm and TF-IDF vectorization.

## Objective

Build a spam mail detection model that can identify whether a message is spam or not based on its text.

## Dataset

* **Dataset:** SMS Spam Collection Dataset
* **File:** `spam.csv`
* **Columns Used:**

  * `v1` – Label (ham/spam)
  * `v2` – Message

## Technologies Used

* Python
* Pandas
* NLTK
* Scikit-learn
* Regular Expressions (re)

## Machine Learning Algorithm

* Multinomial Naive Bayes

## Project Workflow

1. Import required libraries.
2. Load the spam dataset.
3. Select the required columns.
4. Preprocess the text:

   * Convert to lowercase
   * Remove punctuation and numbers
   * Remove stop words
5. Convert labels into numeric values.
6. Transform text into TF-IDF features.
7. Split the dataset into training and testing sets.
8. Train the Naive Bayes classifier.
9. Evaluate the model using:

   * Accuracy
   * Classification Report
10. Predict whether a user-entered message is Spam or Ham.

## Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score

## Skills Gained

* Text preprocessing
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Naive Bayes Classification
* Model Evaluation
* Spam Message Detection

## How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Ensure `spam.csv` is in the same folder as the notebook.
4. Run all cells.
5. Enter your own message when prompted to check whether it is Spam or Ham.

