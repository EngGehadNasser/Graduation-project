# Sentiment Analysis System 📊

##Project Overview
This project is a robust sentiment analysis system that supports both Arabic and English languages. It leverages state-of-the-art Transformer models like BERT to classify text into three categories: Positive, Negative, and Neutral.

## Features 🌟

1. **Multi-language Support**:
   - Uses `aubmindlab/bert-base-arabertv02` for Arabic.
   - Uses `bert-base-uncased` for English.

2. **Advanced Data Cleaning**:
   - Includes preprocessing steps such as removing URLs, mentions, hashtags, numbers, and special characters.
   - Normalizes text by converting it to lowercase and trimming extra spaces.

3. **Customizable Training**:
   - Fine-tunes pre-trained models on custom datasets.
   - Splits data into training and validation sets for evaluation.

4. **Flask API**:
   - Provides a RESTful API for real-time sentiment predictions.
   - Supports both Arabic and English inputs.

5. **Weights & Biases Integration**:
   - Tracks training metrics and performance using W&B.

6. **Model Export**:
   - Saves trained models as ZIP files for easy reuse.

## Dataset 📊

The project uses two datasets:
- **Arabic Dataset**: Contains reviews and ratings.
- **English Dataset**: Contains summaries and sentiment labels.
  
## Models 🤖
- **Arabic Model**: Fine-tuned `aubmindlab/bert-base-arabertv02`.
- **English Model**: Fine-tuned `bert-base-uncased`.


