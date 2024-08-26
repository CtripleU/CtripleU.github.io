---
title: "BERT-Based Medical Chatbot"
date: 2022-08-23 #changed date to bring it up. actual 2024-06-23
author_profile: true
excerpt: "This project implements a machine learning model for answering medical questions using the BERT architecture, specifically the Bio_ClinicalBERT model, fine-tuned on the ChatDoctor-HealthCareMagic-100k dataset."
tags: [BERT, chatbot, medical, machine learning, NLP]
header:
  image: "images/projects/bert-chatbot/1.png"
  teaser: "images/teasers/1.png"
categories:
  - Natural Language Processing
  - Machine Learning
  - Healthcare
  - Chatbot
mathjax: "true"
---


This project implements a machine learning model for answering medical questions. It uses the BERT architecture (Bidirectional Encoder Representations from Transformers), specifically the Bio_ClinicalBERT model, to understand and respond to medical queries. The model is fine-tuned on the ChatDoctor-HealthCareMagic-100k dataset, which contains a large number of medical questions and their corresponding answers.

## Features

- Utilizes Bio_ClinicalBERT for understanding medical terminology
- Handles both the instruction and the input query
- Implements text cleaning and preprocessing
- Includes semantic search functionality for improved response selection
- Has an interactive interface built using Flask, HTML, and CSS
- Provides a Flask API for easy integration into web applications

## Dataset

The project uses the ChatDoctor-HealthCareMagic-100k dataset, which contains medical queries and their corresponding responses.

Dataset Details:
- Source: Lavita - ChatDoctor-HealthCareMagic-100k
- Size: 100,000 medical queries and responses
- Subset: The first 15,000 rows are selected for this project


For the full implementation and to explore the code in detail, see the GitHub Repository [here](https://github.com/CtripleU/BERT-Chatbot.git).