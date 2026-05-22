# Online Threat Message Classification on X (Twitter) Using Machine Learning and NLP
A Machine Learning system for classifying threatening messages in Thai language on X (Twitter) into multiple threat categories using NLP techniques.

## Overview
This research develops and evaluates Machine Learning models for classifying threatening text in Thai on social media. It covers three main threat categories to support the development of automated content moderation systems and promote a safer online environment for users.
## Dataset
Source: X (Twitter) platform
Size: 2,032 public posts
Language: Thai

## Methodology
### Feature Extraction
- TF-IDF (Term Frequency-Inverse Document Frequency)
- Bag-of-Words (BoW)

### Feature Selection
- Information Gain

### Pipeline
- Text preprocessing
- TF-IDF feature extraction
- Machine Learning classification

## Models
- Naive Bayes
- XGBoost
- Random Forest
- Gradient Boosted Trees

## Results
The best overall performance was achieved by the Naïve Bayes model combined with TF-IDF feature extraction, reaching an accuracy of 79.98% and an F1-Score of 80.17%.

## Tools
- Python
- Scikit-learn
- Google Colab
- Rapid miner

## Author
Chatchai Phoum And Thanita Khammoonin
