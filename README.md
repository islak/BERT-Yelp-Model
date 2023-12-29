# Yelp Sentiment Analysis Model

This repository contains a simple sentiment analysis model for Yelp reviews, utilizing the Hugging Face Transformers library. The model uses the `prajjwal1/bert-small` pre-trained transformer.

## Installation

Ensure you have the required dependencies installed:

```bash
pip install torch transformers datasets wordcloud matplotlib
```

## Usage

1. **Import necessary libraries:**

   - `torch`: PyTorch for deep learning.
   - `AutoTokenizer` and `AutoModelForSequenceClassification` from `transformers`: For BERT model and tokenizer.
   - `load_dataset` from `datasets`: For loading the Yelp review dataset.
   - `WordCloud` from `wordcloud`: For generating word clouds.
   - `matplotlib.pyplot` as `plt`: For visualization.

Feel free to adapt the code for your needs. This model provides a quick way to analyze sentiment in Yelp reviews and visualize positive sentiments with a Word Cloud.
