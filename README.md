# **Sentiment Classification with ML and BERT**

## **Overview**
This project explores sentiment classification using both traditional machine learning models (Naive Bayes, Logistic Regression) and state-of-the-art deep learning techniques with BERT. The dataset consists of twitter's tweet text labeled as positive, negative, or neutral. The repository demonstrates a comparison of methodologies, showcasing their performance and practical applications in sentiment analysis.

## **Key Features:**
Data preprocessing pipeline, including tokenization, lemmatization, and stop-word removal
Implementation of Naive Bayes and Logistic Regression for sentiment classification
Fine-tuning BERT for advanced sentiment analysis
Comprehensive performance evaluation and error analysis

## **Results Summary**

| Model                          | Accuracy |
|--------------------------------|----------|
| **Naïve Bayes**                | 0.6555   |
| **Logistic Regression**        | 0.6861   |
|--------------------------------|----------|
| **Baseline (Random DistilBERT)** | 0.3045   |
| **Manually Trained Model**      | 0.7290   |
|--------------------------------|----------|
| **DistilBERT Pre-trained**      | 0.2882   |
| **DistilBERT Fine-tuned**       | 0.7861   |
|--------------------------------|----------|
| **BERT Pre-trained**            | 0.4175   |
| **BERT Fine-tuned**             | 0.7931   |

## **Key Insights**
- Fine-tuned transformer models outperform traditional ML models, with BERT achieving the highest accuracy (79.31%).
- Pre-trained transformers (without fine-tuning) perform poorly, showing the need for domain-specific training.
- Logistic Regression and Naïve Bayes provide strong baselines with lower computational requirements.

