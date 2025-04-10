# Whispers of Wall Street: Predicting Stock Reactions with BoW and LLMs

## Overview
This repository contains the final individual assignment for the **NLP for Finance** course at **EDHEC Business School**, completed as part of the **MSc in Financial Engineering** program for the 2024/2025 academic year. The project focuses on constructing and comparing sentiment measures from earnings call transcripts to predict stock market reactions. It explores both traditional **Bag-of-Words (BoW)** approaches and **Large Language Models (LLMs)**, analyzing their effectiveness in capturing sentiment and forecasting subsequent market movements.

---

## Project Description
The goal of this project is to:
- Construct sentiment measures from earnings call transcripts using multiple methods.
- Compare the performance of these methods in predicting stock market reactions.
- Investigate whether sentiment from the full transcript, management presentation, or Q&A section is most predictive.

### Sentiment Analysis Methods
1. **Bag-of-Words (BoW) Approaches**:
   - Harvard Dictionary
   - Loughran-McDonald (LM) Dictionary
   - Negation Handling
   - Custom Dictionary (created used Grok)
2. **Large Language Models (LLMs)**:
   - Fine-tuned BERT (e.g., FinBERT)
   - Custom fine-tuning strategies and knowledge distillation

The analysis evaluates correlations between sentiment measures and assesses their predictive power against stock market data post-earnings calls.

---

## Repository Structure

Whispers of Wall Street: Predicting Stock Reactions with BoW and LLMs/
├── src/                   # Source code
│   ├── 1-preprocess.ipynb      # Data cleaning and preprocessing
│   ├── 2-bow_sentiment.ipynb   # BoW-based sentiment analysis
│   ├── 3-llm_sentiment_bert.ipynb   # LLM-based sentiment analysis using BERT models
│   ├── 4-llm_sentiment_openai.ipynb   # LLM-based sentiment analysis using OpenAI models
│   ├── 5-analysis.ipynb        # Correlation and prediction analysis
│   └── 9-api_keys.ipynb        # API key to ChatGPT (Hidden)
│   └── data.db                 # Replication database
├── Individual Final Assignment.pdf         # Assignment
├── Whispers of Wall Street.pdf             # Final report (~2-3 pages + Appendix)
└── README.md                               # This file