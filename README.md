# Toxic Comment Classification using Machine Learning & Deep Learning

A Natural Language Processing (NLP) project that detects and classifies toxic online comments using both traditional machine learning and deep learning techniques.

This project compares the performance of Logistic Regression, Linear SVM, LSTM, and Bidirectional LSTM (BiLSTM) models using the Jigsaw Toxic Comment Classification dataset to evaluate different approaches for toxicity detection.

> This project was completed as part of the **CSC464 – Deep Learning & Natural Language Processing** course at the **Lebanese American University (LAU)**.

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
- Model evaluation using Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC

---

## Dataset

The project uses the **Jigsaw Toxic Comment Classification Challenge** dataset from Kaggle.

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

| Model | Category |
| ------ | -------- |
| Logistic Regression | Machine Learning |
| Linear SVM | Machine Learning |
| LSTM | Deep Learning |
| BiLSTM | Deep Learning |

---

## Project Pipeline

1. Data preprocessing
2. Text cleaning and normalization
3. Tokenization and lemmatization
4. Feature engineering (TF-IDF & Word Embeddings)
5. Model training
6. Model evaluation
7. Performance comparison

---

## Results

The implemented models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve (AUC)

The comparison demonstrates the strengths and trade-offs of both traditional machine learning and deep learning approaches. Linear SVM achieved the highest overall accuracy, while the BiLSTM model provided stronger contextual understanding for toxicity detection.

---

## Repository Structure

```text
.
├── toxicity_detection.ipynb
├── Toxic_Comment_Classification_Report.pdf
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Report

A detailed technical report describing the methodology, preprocessing pipeline, model architectures, experiments, and evaluation can be found here:

📄 **[Toxic_Comment_Classification_Report.pdf](./Toxic_Comment_Classification_Report.pdf)**

---

## License

This project is intended for educational and portfolio purposes.
