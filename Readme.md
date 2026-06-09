# NLP - Natural Language Processing Collection
- A collection of NLP projects and implementations covering text preprocessing, feature extraction, and word embeddings using Python and Jupyter Notebooks.

## About
- This repository is built for learning and practicing core NLP concepts step by step. It includes hands-on notebooks that walk through how raw text is cleaned, transformed, and represented as numbers that machine learning models can understand.

## Text Preprocessing
- Before any NLP model can work, raw text needs to be cleaned and structured. This section covers the full preprocessing pipeline:

- Tokenization:- breaking a sentence into individual words or tokens.
- Lowercasing:- converting all text to lowercase for consistency.
- Punctuation & Noise Removal:- stripping out special characters, URLs, and irrelevant symbols using Regular Expressions.
- Stop Word Removal:- eliminating common words like "the", "is", "and" that carry little meaning.
- Stemming:- reducing words to their root form (e.g., "running" → "run").
- Lemmatization:- similar to stemming but more accurate, using vocabulary and grammar rules.


## Word Embeddings — Word2Vec
Once text is clean, it needs to be converted into numbers. This section covers Word2Vec, a technique that represents words as dense vectors in a multi-dimensional space:

Training a Word2Vec model using the Gensim library
Understanding Skip-gram and CBOW architectures
Finding semantically similar words using cosine similarity
Visualizing word relationships in vector space


## Tech Stack
Python, Jupyter Notebook, NLTK, Gensim, NumPy, Pandas
