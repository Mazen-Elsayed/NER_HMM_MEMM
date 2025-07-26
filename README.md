# NER-HMM-MEMM

## Project Description
This repository contains Python implementations of Hidden Markov Model (HMM) and Maximum Entropy Markov Model (MEMM) for Named Entity Recognition (NER) tasks. The project processes the CoNLL-2003 dataset to identify named entities (e.g., person, organization, location) using both greedy and Viterbi decoding for HMM and greedy decoding for MEMM. It includes data preprocessing, feature extraction with regular expressions, model training, and evaluation with metrics like accuracy, confusion matrix, and F1-scores. The code is designed to run in environments like Google Colab or local setups, with experiments comparing model performance on training and test corpora.

## Key Features
- **Preprocessing**: Tokenization and feature extraction using regular expressions.
- **Models**: HMM with greedy and Viterbi decoding, MEMM with greedy decoding.
- **Dataset**: CoNLL-2003 for training and evaluation.
- **Evaluation**: Metrics include accuracy, confusion matrix, and F1-scores.
- **Environment**: Compatible with Google Colab or local Python environments.

## Requirements
- Python 3.x
- NumPy, Pandas, Scikit-learn, NLTK
- CoNLL-2003 dataset
