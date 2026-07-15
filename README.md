# Sentiment Analysis Using Embeddings and Transformer Models

## Overview

This project performs sentiment classification on Twitter data using both traditional machine learning and modern transformer-based techniques. It explores multiple approaches, compares their performance, and ultimately fine-tunes a transformer model for high-quality sentiment prediction.

The project demonstrates the complete machine learning workflow, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Text embedding generation
- Traditional ML models
- Transformer fine-tuning
- Model evaluation
- Real-world sentiment prediction

---

## Dataset

The project uses the Twitter sentiment dataset downloaded using KaggleHub.

Each tweet is classified into one of three categories:

- Positive
- Neutral
- Negative

---

## Project Pipeline

### 1. Data Loading

- Load Twitter sentiment dataset
- Select relevant columns
- Inspect dataset structure

### 2. Data Preprocessing

- Remove URLs
- Remove special characters
- Clean text
- Prepare labels

### 3. Exploratory Data Analysis

- Sentiment distribution
- Word Cloud visualization
- Tweet length analysis

### 4. Sentence Embeddings

Text is converted into dense vector representations using Sentence Transformers.

### 5. Machine Learning Models

The project evaluates multiple models:

- XGBoost
- Logistic Regression

### 6. Transformer Fine-Tuning

A Hugging Face transformer model is fine-tuned for sentiment classification using:

- AutoTokenizer
- AutoModelForSequenceClassification
- Trainer API
- TrainingArguments

### 7. Model Evaluation

Performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### 8. Prediction

The notebook includes a prediction function that classifies custom user-provided text.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- WordCloud
- Scikit-learn
- Sentence Transformers
- XGBoost
- Hugging Face Transformers
- Hugging Face Datasets
- PyTorch
- KaggleHub

---

## Project Structure

```
sentiment-analysis-transformer/
│
├── Sentiment_Classification_Using_Embeddings.ipynb
├── README.md
├── .gitignore
└── requirements.txt
```

> Note: The trained model files are intentionally excluded because they exceed GitHub's file size limit.

---

## Results

The project compares multiple sentiment classification approaches and demonstrates that transformer-based fine-tuning achieves the strongest overall performance.

---

## Future Improvements

- Hyperparameter optimization
- Cross-validation
- Deploy using Streamlit or Flask
- Publish the trained model on Hugging Face Hub
- Build a web application for real-time predictions

---

## Author

**Srikar Balusani**

GitHub: https://github.com/SrikarBalusani
