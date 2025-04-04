# Twitter Sentiment Analysis using Deep Learning & Machine Learning

## Overview  
This project focuses on classifying tweets into **positive, negative, or neutral** sentiments using **Machine Learning** and **Deep Learning** techniques. Various models, including traditional ML algorithms and advanced deep learning architectures, are implemented.

## Models Implemented  
### Deep Learning Models  
- Long Short-Term Memory (**LSTM**)  
- Convolutional Neural Networks (**CNN**)  
- Hybrid Model (**LSTM + CNN**)  
- **BERT** (Bidirectional Encoder Representations from Transformers)  

### Machine Learning Models  
- **Naïve Bayes**  
- **Logistic Regression**  
- **Support Vector Machine (SVM)**  
- **Random Forest**  

## Dataset  
The dataset contains thousands of tweets labeled as **positive, negative, or neutral**.  

- Preprocessed tweets by removing:
  - Hashtags, mentions, and URLs  
  - Stopwords and special characters  
- Applied **TF-IDF**, and **BERT embeddings** for feature extraction.

## Methodology  
1. **Data Collection & Preprocessing**  
   - Removed noise such as special characters, URLs, and mentions.  
   - Tokenized and vectorized the text.  

2. **Feature Engineering**  
   - Used **TF-IDF** for ML models.  
   - Used **BERT embeddings** for Transformer-based models.  

3. **Model Training & Evaluation**  
   - Trained all models and fine-tuned **LSTM, CNN, Hybrid, and BERT** models.  
   - Evaluated using **accuracy, precision, recall, and F1-score**.  

4. **Results & Comparison**  
   - Deep learning models, especially **BERT**, outperformed traditional ML models.  
   - The **LSTM+CNN hybrid model** also performed competitively.
