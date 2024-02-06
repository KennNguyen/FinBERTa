# FinBERTa : My Attempts in Building a Sentiment Analyzer of Financial News Utilizing RoBERTa  

## Overview: 

This project is centered around the advanced language model, RoBERTa, and its application in understanding the nuances of sentiment in financial news. The study is conducted in two distinct stages to evaluate the impact of domain-specific pre-training on the model's performance.

### Stage One: Baseline Sentiment Training: (On-Going)

In the first stage, RoBERTa is directly employed to analyze the sentiment of financial news articles without any prior specialized training in the financial domain. This stage aims to establish a baseline for the model's ability to interpret and classify sentiments in the context of financial news, relying solely on its general language understanding capabilities.

### Stage Two: Financial Corpus Pre-Training: (Upcoming)

The second stage introduces an additional pre-training phase where RoBERTa is first exposed to a comprehensive financial corpus. This step is designed to fine-tune the model's understanding of financial jargon, concepts, and contexts. Following this domain-specific training, the model is then trained for sentiment analysis, similar to the first stage.

### Objective: 

The primary objective of this project is to conduct a comparative analysis of RoBERTa's performance in sentiment analysis of financial news across these two stages. The comparison aims to quantify the benefits, if any, of pre-training RoBERTa on a financial corpus before conducting sentiment analysis. This study will contribute to a better understanding of the importance of domain-specific training in enhancing the accuracy and reliability of sentiment analysis models in specialized fields like finance.

### Methodology:

- Collection of a diverse set of financial news articles.
- Pre-training RoBERTa on a comprehensive financial corpus in Stage Two.
- Training RoBERTa for sentiment analysis in both stages.
- Comparing the performance metrics (such as accuracy, precision, recall, etc.) of the model from both stages.

### Expected Outcomes: 

The project expects to demonstrate the efficacy of domain-specific pre-training in sentiment analysis tasks. The results are anticipated to provide insights into how pre-training on a specialized corpus can enhance a model's interpretive accuracy and contextual understanding in a specific field like finance.

## Built With:

- ### PyTorch: An open-source machine learning library for Python, favored for its flexibility, ease of use, and dynamic computational graph, that facilitates building deep learning models.

- ### PyTorch Utilities: Auxiliary tools and libraries that extend PyTorch, offering additional functionalities like model optimization and simplified coding interfaces to enhance development efficiency.

- ### Datasets by Hugging Face: A lightweight Python library providing easy access to a vast array of machine learning datasets, designed to simplify data loading and preprocessing for quicker experimentation.

- ### Transformers by Hugging Face: A comprehensive library that provides pre-trained models for natural language processing tasks, enabling easy utilization and fine-tuning of state-of-the-art NLP models with minimal effort.
