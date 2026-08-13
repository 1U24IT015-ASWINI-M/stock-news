# stock-news

# Stock News Sentiment Analysis Using Generative AI

### AI / Machine Learning Project

This project analyzes stock-related news and predicts the sentiment polarity of news articles as Positive, Neutral, or Negative.

The project uses text embeddings and machine learning/deep learning models to understand news sentiment and support better stock-market analysis.

 ### Objective

To build an AI-based sentiment analysis system that can process stock news, identify market sentiment, and provide useful insights for financial analysis.

### What I Did

Explored and analyzed stock news and market data

Performed Exploratory Data Analysis (EDA)

Processed news text data

Created text embeddings using Word2Vec

Used Sentence Transformers

Trained Random Forest models

Built Neural Network models

Compared different models using classification metrics

Performed hyperparameter tuning

Selected the best-performing approach based on test-set performance

### Technologies Used

Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | TensorFlow | Keras | Gensim | Sentence Transformers

### Embedding Models

Word2Vec

BAAI/bge-base-en-v1.5

all-MiniLM-L6-v2

### Sentiment Classes

# Label                Sentiment

 1                     Positive

 0                     Neutral

-1                    Negative

### Best Model

Based on the notebook's test-set evaluation, the Sentence Transformer all-MiniLM-L6-v2 with a Neural Network achieved the best reported F1-score of 0.6230.

### Business Use

The sentiment results can help financial analysts:

Understand market sentiment from news

Monitor positive and negative news trends

Generate useful insights for investment analysis

Support future stock-price prediction systems

### Project File

Stock_Analysis_GenAI.ipynb — Complete Jupyter Notebook containing data analysis, embeddings, model training, evaluation, and conclusions.
