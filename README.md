# Product Sentiment Analysis

This project focuses on performing **Sentiment Analysis** on **Amazon Product Reviews** using a combination of **traditional Machine Learning (ML)** and **Deep Learning (DL)** techniques. It provides a complete pipeline from data preprocessing to model evaluation.

## 📁 Project Structure

```
product-sentiment-analysis/
├── DL/                        # Deep Learning models (e.g., RNN, LSTM)
├── ML/                        # Traditional ML models (e.g., SVM, NB, LR)
├── Old dataset/              # Previously used raw/old data
├── Preprocessing_code/       # Scripts for data cleaning, tokenization, etc.
├── Processing dataset/       # Final processed datasets
└── README.md                 # Project documentation
```

## Techniques Used

### Machine Learning Models (ML)

* Logistic Regression
* Naive Bayes
* Support Vector Machines (SVM)
* Decision Trees / Random Forests

### Deep Learning Models (DL)

* Recurrent Neural Networks (RNN)
* Long Short-Term Memory Networks (LSTM)

## Preprocessing Steps

* Lowercasing and cleaning text
* Removing stopwords and punctuation
* Tokenization
* Vectorization using TF-IDF / Word Embeddings

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Dataset

Amazon product review data (may include versions of old vs processed sets).

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/EliasHossain001/product-sentiment-analysis.git
   cd product-sentiment-analysis
   ```

2. Install required libraries (create virtualenv if preferred):

   ```bash
   pip install -r requirements.txt
   ```

3. Explore the code:

   * For ML models: go to `ML/`
   * For DL models: go to `DL/`
   * For preprocessing: check `Preprocessing_code/`

4. Run example scripts to train and evaluate models:

   ```bash
   python ML/train_model.py
   python DL/train_lstm.py
   ```

---

## Future Improvements

* Include Transformer-based models like BERT
* Deploy as a sentiment analysis web API
* Improve data balancing and augmentation techniques

---

## 👨‍💼 Author

**Elias Hossain** <br>
*Machine Learning Researcher | PhD in Progress | AI x Reasoning Enthusiast*

[![GitHub](https://img.shields.io/badge/GitHub-EliasHossain001-blue?logo=github)](https://github.com/EliasHossain001)
