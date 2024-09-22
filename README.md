# Sentiment-Analysis-of-Arabic-with-AraBERT-
This repository contains the implementation of an Arabic sentiment analysis model using AraBERT, a transformer-based model specifically pre-trained for Arabic NLP tasks. The implementation uses PyTorch and the Huggingface `transformers` library to fine-tune AraBERT for sentiment analysis on Arabic text.
## Introduction
Arabic Sentiment Analysis is the task of determining the sentiment expressed in Arabic text. This project fine-tunes AraBERT on an Arabic sentiment dataset to classify text into positive, negative, or neutral sentiment classes.


## Dataset
The data has 40K+ reviews in Arabic for sentiment analysis each labelled with a rating and its associated company name.
## Dataset Glossary (Column-Wise)
- **Index column (integer)**
- **Review (text)**
- **Rating (-1,0,1)**
- **Company (text)**
