# AI-ML
# QSkill AI/ML Internship - Project Repository

## 👤 Intern Profile
* **Name:** Ganesh Mishra
* **Intern ID:** qsai2026061388
* **Domain:** Artificial Intelligence & Machine Learning
* **Batch Duration:** 1st June 2026 - 1st July 2026
* **Company:** QSkill (Squarcell Resource India Pvt. Ltd.)

## 📄 Overview
This repository contains the practical task submissions for the AI/ML Virtual Internship at QSkill. All models and scripts were developed and executed using Google Colab, focusing on fundamental machine learning concepts including classification, regression, and natural language processing (NLP). 

An official copy of the internship offer letter has been attached to this repository for verification purposes.

---

## 🛠️ Tasks Completed

### Task 1: Iris Flower Classification
* **Objective:** Classify iris flowers into three distinct species (Setosa, Versicolor, Virginica) based on the physical measurements of their petals and sepals.
* **Dataset:** Classic Iris dataset (UCI Machine Learning Repository / scikit-learn).
* **Workflow:**
  * Visualized data distributions using scatter plots and histograms.
  * Split the dataset into training and testing subsets.
  * Implemented and trained classification models (Logistic Regression / K-Nearest Neighbors / Decision Tree).
  * Evaluated model performance utilizing accuracy scores and confusion matrices.
* **Key Skills Applied:** Numeric data analysis, classification modeling, and performance evaluation.

### Task 2: Spam Mail Detector
* **Objective:** Build a robust NLP classifier capable of distinguishing between spam and non-spam (ham) emails utilizing textual data.
* **Dataset:** SMS Spam Collection (UCI) / Enron Email Dataset.
* **Workflow:**
  * Preprocessed raw text data (lowercasing, stopword removal, tokenization).
  * Converted textual data into numeric feature vectors using TF-IDF / Bag of Words methodologies.
  * Trained classification models (Naive Bayes / Logistic Regression).
  * Measured model reliability using accuracy, precision, and F1 scores.
* **Key Skills Applied:** Text preprocessing, feature extraction, basic Natural Language Processing (NLP), and text classification.

### Task 3: House Price Prediction
* **Objective:** Predict continuous housing prices based on various structural and locational features (e.g., size, number of bedrooms).
* **Dataset:** Boston Housing dataset (or equivalent numeric housing data).
* **Workflow:**
  * Explored data distributions and handled missing values.
  * Preprocessed and normalized input features.
  * Trained a Linear Regression model to predict continuous target variables.
  * Evaluated regression accuracy using Mean Squared Error (MSE).
* **Key Skills Applied:** Tabular data handling, regression analysis, feature engineering, and continuous metric evaluation.

---

## 🚀 Execution & Usage
These notebooks were designed to run seamlessly in **Google Colab**. 

1. Clone this repository or download the `.ipynb` files.
2. Upload the notebooks directly to [Google Colab](https://colab.research.google.com/).
3. Ensure the required libraries are installed (most are pre-installed in Colab environments):
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
