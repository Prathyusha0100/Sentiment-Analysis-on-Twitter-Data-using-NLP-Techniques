# 📝 Sentiment Analysis on Twitter Data using NLP Techniques  

This project implements **sentiment classification** on Twitter text data using **two different NLP techniques**:
1. **TF-IDF & One-Hot Encoding Approach**
2. **Word2Vec & GloVe Embedding Approach**

It compares how different **text representation methods** impact **classification performance** using machine learning models.

## 🚀 Project Overview  
  - **Dataset:** Twitter sentiment dataset (labels: 0 = Negative, 4 = Positive).  
  - **Approach 1:** One-hot encoding & TF-IDF tokenization for feature extraction.  
  - **Approach 2:** Word embeddings using **Word2Vec** & **GloVe**.  
  - **Model Training:** Classification model trained with **hyperparameter tuning**.  
  - **Performance Evaluation:** Accuracy, precision, recall, F1-score.  

## 📌 Features  
  **NLP Preprocessing:**  
  - Tokenization using **TF-IDF, One-Hot Encoding, Word2Vec, and GloVe**.  
  - Stopword removal & text cleaning.  
  
   **Sentiment Classification Models:**  
  - Experimented with various classifiers (**Logistic Regression, Random Forest, LSTMs**).  
  - Hyperparameter tuning (e.g., **learning rate, dropout rate**).  
  
  **Evaluation & Results:**  
  - **Accuracy, Precision, Recall, and F1-score**.  
  - **Comparison of different embedding techniques**.  

## 📦 Installation & Setup  
  To set up and run the project locally:  
  
  1. **Clone this repository:**  
     ```bash
     git clone https://github.com/your-username/Twitter-Sentiment-Analysis.git
     cd Twitter-Sentiment-Analysis
  2. **Install dependencies:**
      ```bash
      pip install -r requirements.txt
  3. **Run the Jupyter Notebook:**
     ```bash
     jupyter notebook

📊 **Dataset**
The dataset consists of tweets labeled as negative (0) or positive (4).
Data is preprocessed into train, validation, and test splits.

📈 **Results**
Model Accuracy for different NLP techniques.
Confusion matrix & classification report for model comparison.
