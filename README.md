# NLP-Projects: Emotion & Sentiment Analysis
​This repository showcases the development of machine learning models for Natural Language Processing (NLP) tasks. The projects focus on transforming raw text data into actionable insights through sophisticated preprocessing and classification techniques.
​🚀 Projects Overview
​1. Text-Based Emotion Detection
​This project identifies six distinct emotional states in text: sadness, anger, love, surprise, fear, and happy.
​Workflow: Includes duplicate removal, tokenization, and WordNet Lemmatization to maintain semantic meaning.
​Feature Engineering: Utilized TfidfVectorizer with an ngram_range of (2,2) (Bigrams), capturing 118,344 unique features.
​Model: Random Forest Classifier.
​Results: Achieved a test accuracy of 65.0%, with high precision in identifying specific categories like anger (0.89).
​2. Twitter Sentiment Analysis
​A robust classifier built to categorize the sentiment of tweets as Negative (-1), Neutral (0), or Positive (1).
​Model Performance: Reached a test accuracy of 59.79%.
​Key Strength: The model is highly specialized at identifying Negative sentiments, with a recall score of 0.97.
​📊 Technical Implementation & Visualization
​Pipeline: Handled the full lifecycle from data ingestion and cleaning to model evaluation.
​Evaluation Tools: Utilized Confusion Matrices and Classification Reports to measure precision, recall, and F1-scores.
​Insights: Visualized class distributions using Seaborn countplots to address and understand dataset imbalances.
​🛠️ Tech Stack
​Language: Python
​Libraries: Scikit-Learn, NLTK, Pandas, NumPy, Matplotlib, Seaborn
​Methodology: TF-IDF Vectorization, Bigram Analysis, Random Forest
