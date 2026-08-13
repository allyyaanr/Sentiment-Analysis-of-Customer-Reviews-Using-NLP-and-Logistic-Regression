# 📝 Sentiment Analysis of Customer Reviews Using NLP and Logistic Regression

## 🔎 Project Overview

This project applies **Natural Language Processing (NLP)** and Machine Learning techniques to analyze customer reviews and classify them into **positive and negative sentiments**.

The project covers the complete text classification workflow, starting from text preprocessing and Exploratory Data Analysis (EDA), followed by TF-IDF feature extraction and Logistic Regression modeling. The model performance was evaluated using several classification metrics to assess its ability to distinguish between positive and negative reviews.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- 📝 Analyze customer reviews using NLP techniques.
- 🧹 Preprocess and clean textual data.
- 🔍 Explore sentiment patterns and text characteristics.
- 🔢 Transform textual data into numerical features using TF-IDF.
- 🤖 Build a sentiment classification model using Logistic Regression.
- 📊 Evaluate the performance of the classification model.
- 💡 Identify the overall sentiment distribution within customer reviews.

---

## 📂 Dataset

The dataset contains **customer review text** together with sentiment information used for sentiment classification.

The reviews were analyzed to determine whether the expressed sentiment was:

- 😊 **Positive**
- 😠 **Negative**

The dataset was used as the basis for text preprocessing, feature extraction, exploratory analysis, and sentiment classification.

---

## 🔄 Analytical Workflow

The project followed the following workflow:

**Customer Reviews**  
⬇️  
**Text Cleaning**  
⬇️  
**Lowercasing**  
⬇️  
**Stopword Removal**  
⬇️  
**Stemming**  
⬇️  
**Tokenization**  
⬇️  
**Exploratory Data Analysis**  
⬇️  
**TF-IDF Feature Extraction**  
⬇️  
**Logistic Regression**  
⬇️  
**Model Evaluation**  
⬇️  
**Sentiment Classification**

---

## 🧹 1. Text Preprocessing

Text preprocessing was performed to transform raw customer reviews into cleaner and more consistent textual data.

The preprocessing steps included:

### 🔤 Lowercasing
Converted all text into lowercase to ensure that words with different capitalization were treated consistently.

### 🧹 Text Cleaning
Removed unnecessary characters and elements that were not useful for sentiment classification.

### 🚫 Stopword Removal
Removed common words that provide limited information for sentiment classification.

### 🌱 Stemming
Reduced words to their basic word forms to help group words with similar meanings.

### ✂️ Tokenization
Separated the text into individual tokens or words for further processing.

---

## 📊 2. Exploratory Data Analysis

EDA was conducted to understand the characteristics of the review dataset and sentiment distribution.

The analysis included:

- 📈 Sentiment distribution
- ☁️ WordCloud visualization
- 🔍 Frequently occurring words
- 📝 Review text characteristics

The analysis showed that:

- 😊 **Positive sentiment: 53.1%**
- 😠 **Negative sentiment: 46.9%**

This indicates a relatively balanced distribution between the two sentiment classes, with positive reviews slightly more dominant.

---

## 🔢 3. TF-IDF Feature Extraction

After text preprocessing, **Term Frequency-Inverse Document Frequency (TF-IDF)** was applied to transform textual data into numerical feature representations.

TF-IDF assigns weights to words based on their importance within individual reviews and across the overall dataset.

This numerical representation was then used as input for the machine learning model.

---

## 🤖 4. Logistic Regression

**Logistic Regression** was applied as the classification algorithm to predict whether a customer review belonged to the positive or negative sentiment class.

The model used the TF-IDF representation of the reviews as its input features.

The classification process can be summarized as:

**Preprocessed Reviews**  
➡️ **TF-IDF Features**  
➡️ **Logistic Regression**  
➡️ **Positive / Negative Sentiment**

---

## 📈 5. Model Evaluation

The Logistic Regression model was evaluated using several performance metrics:

### 🎯 Accuracy

The model achieved an accuracy of:

**71%**

### 📊 Confusion Matrix

The confusion matrix was used to examine the model's correct and incorrect predictions across the positive and negative classes.

### 📋 Classification Report

Precision, recall, and F1-score were used to provide a more detailed evaluation of classification performance.

### 📈 ROC-AUC

The model achieved a:

**ROC-AUC Score: 0.81**

The ROC-AUC result indicates that the model had a good ability to distinguish between positive and negative sentiment classes.

---

## 🏆 Results

The sentiment analysis successfully classified customer reviews into two sentiment categories:

| Sentiment | Percentage |
|---|---:|
| 😊 Positive | 53.1% |
| 😠 Negative | 46.9% |

The Logistic Regression model achieved:

| Evaluation Metric | Result |
|---|---:|
| 🎯 Accuracy | 71% |
| 📈 ROC-AUC | 0.81 |

---

## 💡 Key Insights

- 😊 Positive reviews slightly outnumbered negative reviews.
- 📊 The sentiment distribution was relatively balanced.
- 🔤 NLP preprocessing helped transform raw customer reviews into structured textual data.
- 🔢 TF-IDF provided numerical representations suitable for machine learning.
- 🤖 Logistic Regression was able to classify customer sentiment with **71% accuracy**.
- 📈 The **0.81 ROC-AUC score** indicates good discrimination between positive and negative reviews.

---

## 🖼️ Project Outputs

The project includes several analytical outputs:

- 🔄 Text preprocessing results
- ☁️ WordCloud visualization
- 📊 Sentiment distribution
- 🔢 TF-IDF feature representation
- 🤖 Logistic Regression classification
- 🔲 Confusion Matrix
- 📈 ROC Curve
- 📋 Classification Report

---

## 🛠️ Tools & Technologies

### 💻 Programming
- Python

### 🧠 NLP
- Text Cleaning
- Lowercasing
- Stopword Removal
- Stemming
- Tokenization
- TF-IDF

### 🤖 Machine Learning
- Logistic Regression
- Binary Sentiment Classification

### 📊 Data Analysis & Visualization
- Pandas
- NumPy
- Matplotlib
- WordCloud
- Scikit-learn

### 📓 Development Environment
- Jupyter Notebook / Google Colab

---

## 🧠 Skills Demonstrated

- Natural Language Processing (NLP)
- Sentiment Analysis
- Text Classification
- Text Preprocessing
- Feature Extraction
- TF-IDF
- Logistic Regression
- Exploratory Data Analysis
- Data Visualization
- Model Evaluation
- Python
- Scikit-learn
- Data Interpretation

---

## 📌 Project Highlights

✨ End-to-end NLP text classification workflow  
✨ Customer review sentiment analysis  
✨ Text preprocessing and feature engineering  
✨ TF-IDF feature extraction  
✨ Logistic Regression classification  
✨ 71% classification accuracy  
✨ 0.81 ROC-AUC score  
✨ Sentiment distribution analysis and visualization  

---

## 📚 Project Context

This project was developed as a data mining / machine learning project to apply NLP techniques and supervised learning methods to real-world customer review data.

**Research Focus:**  
Natural Language Processing • Sentiment Analysis • Text Classification • Machine Learning • Customer Review Analytics
