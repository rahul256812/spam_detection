# Spam Detection ML Project

A machine learning project to classify SMS messages as spam or ham using various classification algorithms.

## Overview

This project uses Natural Language Processing (NLP) and machine learning techniques to detect spam messages. It compares the performance of three different classification models on the SMS Spam Collection dataset.

## Dataset

- **Source**: `spam.csv` (SMS Spam Collection Dataset)
- **Columns**: 
  - `v1` (label): ham (0) or spam (1)
  - `v2` (message): text content of SMS
- **Size**: 5,574 messages

## Models Used

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Support Vector Machine (SVM)**

## Features

- **TF-IDF Vectorization**: Converts text messages into numerical features
- **English Stop Words Removal**: Improves feature quality
- **Model Comparison**: Evaluates accuracy, F1 score, precision, and recall

## Results

| Model | Accuracy | F1 Score | Precision | Recall |
|-------|----------|----------|-----------|--------|
| Logistic Regression | 95.25% | 79.05% | 97.09% | 66.67% |
| Random Forest | 97.58% | 90.25% | 98.43% | 83.33% |
| **SVM (Best)** | **97.94%** | **91.93%** | **97.04%** | **87.33%** |

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

## Usage

Open `poster.ipynb` in Jupyter Notebook and run all cells to:
1. Load and preprocess the dataset
2. Train the three models
3. Compare performance metrics
4. Test custom messages for spam detection

## Project Structure

```
.
├── README.md
├── poster.ipynb      # Main notebook with ML pipeline
├── spam.csv          # Dataset
└── ml_env/           # Virtual environment
```

## Author

Rahul
