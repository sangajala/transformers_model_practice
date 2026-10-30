# README: Sentiment Analysis Notebook

### Overview
This Google Colab notebook demonstrates how to perform sentiment analysis on text data using the Hugging Face `transformers` library. It uses a lightweight, state-of-the-art pre-trained deep learning model (`distilbert-base-uncased-finetuned-sst-2-english`) to classify the emotional tone of sample customer reviews.

### Getting Started
1. **Run All Cells**: Click on `Runtime` > `Run all` in the top menu to execute the entire notebook.
2. **No Setup Needed**: There are no external credentials or API keys required to execute this code; it uses publicly available assets directly from the Hugging Face Hub.

### Notebook Structure
- **Installation**: Installs the Hugging Face `transformers` package.
- **Pipeline Loading**: Initializes the sentiment classification pipeline.
- **Prediction**: Analyzes five sample customer reviews and prints their prediction labels (`POSITIVE` / `NEGATIVE`) alongside confidence scores.
- **Conceptual QA**: Explains the core mechanics of Transformers (Self-Attention & Attention Weights).

### Dependencies
- `transformers` (Hugging Face Core Library)
- `torch` or `tensorflow` (Backend frameworks, automatically configured in Colab)
