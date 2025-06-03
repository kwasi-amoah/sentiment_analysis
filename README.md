BERTweet-Based Sentiment Classifier for X (Twitter) Posts
This repository contains a machine learning pipeline for classifying X (formerly Twitter) posts into eight sentiment or thematic categories using a fine-tuned BERTweet model. The project consists of two main Jupyter notebooks:

🔧 1. model_training.ipynb
This notebook covers:

Preprocessing and cleaning of X post data

Fine-tuning of the BERTweet transformer model on labeled text data

Evaluation of model performance (achieved over 94% accuracy)

Saving the final model for downstream inference

⚙️ 2. trained_model_sentiment_classification.ipynb
This notebook automates:

Scraping or downloading recent X posts via an API

Running these posts through the trained BERTweet model

Appending results (predicted category, confidence scores, etc.) to a master list for ongoing sentiment tracking or analysis

🧠 Model
The model is built on top of BERTweet, a language model pre-trained on English Tweets, making it highly suitable for short-form, informal text.

📦 Use Cases
Social media sentiment monitoring

Brand reputation tracking

Public health or misinformation trend detection

Thematic tagging of large tweet datasets
