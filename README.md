
# Part 3 - NLP and Sequence Modeling Mini Project

## Project Overview

This project demonstrates a complete Natural Language Processing (NLP) workflow using a customer support text classification dataset.

The project compares traditional text vectorization techniques with sequence-based deep learning models.

## Objectives

- Understand text datasets
- Perform text preprocessing
- Convert text into numerical vectors
- Build a baseline machine learning model
- Build a sequence model using LSTM
- Understand attention and transformer concepts

## Dataset

Dataset Used:
customer_support_text_classification.csv

## Tasks Performed

### 1. Dataset Understanding

- Loaded dataset
- Checked number of records
- Analyzed target classes
- Viewed sample text records
- Calculated average text length
- Visualized class distribution

### 2. Text Preprocessing

- Lowercasing
- Removing special characters
- Tokenization
- Stopword removal

### 3. Text Vectorization

TF-IDF vectorization was used to convert text into numerical format.

### 4. Baseline Model

- Logistic Regression with TF-IDF

### 5. Sequence Model

- LSTM (Long Short-Term Memory)

### 6. Attention and Transformer Reflection

Includes explanations about:
- RNN limitations
- LSTM memory
- Attention mechanism
- Transformers

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- TensorFlow

## Project Structure

part-3-nlp-sequence-modeling/

README.md
notebook.ipynb
requirements.txt
results/

## How to Run

pip install -r requirements.txt

Run notebook.ipynb

## Results

The project demonstrates:
- NLP preprocessing
- TF-IDF vectorization
- Logistic Regression
- LSTM sequence modeling

