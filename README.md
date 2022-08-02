# Abstractive-Text-Summarization

The basic idea behind abstractive text summarization is to be able to extract a short subset of the most important information from a large set and present it in a human-readable format. As the amount of textual data on the internet grows, automatic text summarization methods have the potential to be very useful because more useful information can be read in a shorter amount of time.

## PROPOSED SYSTEM 

### 1. Preprocessing and Dataset

Within this particular project, I trained the model on Kaggle's Inshorts news dataset, containing 55,000 headlines and their respective summaries which is frequently used for training models for abstractive summarization. We have trained the model to predict the abstract summary of the news headline.

- Inshorts Dataset: https://www.kaggle.com/shashichander009/inshorts-news-data

### 2. Model

Abstractive Text Summarization using Transformer

- Implementation of the state of the art Transformer Model from "Attention is all you need", Vaswani et. al.
  https://arxiv.org/abs/1706.03762

Abstractive Text Summarization using LSTM Encoder-Decoder

- A Three Layer Stacked LSTM Encoder-Decoder model with Global Attention Mechanism was used during implementation. On the training set, the algorithm was able to achieve an accuracy of 77.27 percent using this model. This model also achieved a cumulative BLEU-4 score of 0.8800 on the test set.
