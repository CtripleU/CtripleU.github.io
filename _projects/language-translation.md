---
title: "English to Igbo Neural Machine Translation"
date: 2024-06-14
author_profile: true
excerpt: "This project implements a neural machine translation model to translate English sentences to Igbo using a sequence-to-sequence LSTM architecture."
tags: [NLP, machine translation, deep learning, LSTM, English, Igbo]
header:
  image: "images/projects/translation/download.png"
  teaser: "images/teasers/download.png"
categories:
  - Natural Language Processing
  - Machine Learning
  - Neural Machine Translation
mathjax: "true"
---


This project implements a neural machine translation model to translate English sentences to Igbo using a sequence-to-sequence LSTM architecture. The model is trained on a dataset of English-Igbo sentence pairs and achieves high accuracy in translation tasks.

## Features

- Utilizes a sequence-to-sequence LSTM model for translation
- Implements data preprocessing techniques for text cleaning
- Uses TensorFlow and Keras for model building and training
- Achieves high accuracy on both training and validation sets

## Dataset

The project uses the "english_to_igbo" dataset from Hugging Face:

- Source: ccibeekeoc42/english_to_igbo
- Total samples: 525,618 (522,322 train, 3,296 test)
- Features: 'English' and 'Igbo' sentence pairs

For this project, I sampled 10,000 rows from the training dataset to reduce computational requirements.


For the full implementation and to explore the code in detail, see the GitHub Repository [here](https://github.com/CtripleU/Language-translation.git).