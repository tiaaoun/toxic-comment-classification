# Toxic Comment Classification using Machine Learning & Deep Learning

A Natural Language Processing (NLP) project that detects and classifies toxic online comments using both traditional machine learning and deep learning techniques.

This project compares the performance of Logistic Regression, Linear SVM, LSTM, and Bidirectional LSTM (BiLSTM) models on the Jigsaw Toxic Comment Classification dataset to evaluate their effectiveness in toxicity detection.

---

## Features

- Text preprocessing and cleaning
- Multi-label to three-class label conversion
- TF-IDF feature extraction
- Tokenization and sequence padding
- Word embeddings
- Logistic Regression
- Linear Support Vector Machine (SVM)
- Long Short-Term Memory (LSTM)
- Bidirectional LSTM (BiLSTM)
- Performance evaluation using Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC

---

## Dataset

This project uses the **Jigsaw Toxic Comment Classification Challenge** dataset available on Kaggle.

The original multi-label dataset was converted into three mutually exclusive classes:

- Non-toxic
- Toxic
- Abusive

---

## Technologies

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- NLTK
- Matplotlib
- Seaborn

---

## Models Implemented

| Model | Approach |
|--------|----------|
| Logistic Regression | Machine Learning |
| Linear SVM | Machine Learning |
| LSTM | Deep Learning |
| BiLSTM | Deep Learning |

---

## Project Pipeline

1. Data preprocessing
2. Text cleaning
3. Tokenization and lemmatization
4. Feature engineering (TF-IDF / Embeddings)
5. Model training
6. Model evaluation
7. Performance comparison

---

## Results

The implemented models were compared using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve (AUC)

The comparison highlights the trade-offs between traditional machine learning methods and deep learning architectures. While Linear SVM achieved the highest accuracy, the BiLSTM model demonstrated stronger contextual understanding of language, making it particularly effective for detecting complex toxic patterns.

---

## Repository Structure

```
.
├── toxicity_detection.ipynb
├── Project_Report.pdf
├── README.md
└── requirements.txt
```

---

## Report

A detailed report describing the methodology, preprocessing pipeline, model architectures, experiments, and evaluation is available in **Project_Report.pdf**.

---

## Authors

- Tia Aoun
- Alaedine Fathallah
- Ali Mourad

---

## Course

**CSC464 – Deep Learning & Natural Language Processing**

Lebanese American University (LAU)
