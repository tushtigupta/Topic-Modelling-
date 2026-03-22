**📌 Topic Modelling using LDA, LSA & NMF**

🚀 This project explores unsupervised Natural Language Processing (NLP) techniques to extract hidden topics from textual data using three powerful models:

Latent Dirichlet Allocation (LDA)

Latent Semantic Analysis (LSA)

Non-Negative Matrix Factorization (NMF)
**📖 Overview**

Topic Modeling is a technique used to automatically discover hidden themes in a collection of documents.
This project compares three widely used approaches and analyzes how each model identifies topics from text data.

**🎯 Objectives**
Extract meaningful topics from raw text data
Compare performance of LDA, LSA, and NMF
Understand differences between probabilistic and matrix factorization methods
Visualize and interpret topic distributions
**🛠️ Tech Stack**
Programming Language: Python 🐍
Libraries Used:
NumPy
Pandas
Scikit-learn
Gensim
NLTK / SpaCy
Matplotlib / Seaborn
**⚙️ Workflow**
Data Collection
Text Preprocessing
Tokenization
Stopword removal
Lemmatization
Vectorization
Count Vectorizer (for LDA)
TF-IDF Vectorizer (for LSA & NMF)
Model Building
LDA (Probabilistic Model)
LSA (SVD-based Model)
NMF (Matrix Factorization Model)
Topic Extraction
Evaluation & Comparison
Visualization of Topics
**🧠 Models Explained**
**🔹 LDA (Latent Dirichlet Allocation)**
A probabilistic model
Assumes documents are a mixture of topics
Topics are distributions over words
Works well for large datasets
**🔹 LSA (Latent Semantic Analysis)**
Based on Singular Value Decomposition (SVD)
Captures relationships between terms and documents
Reduces dimensionality
May lose interpretability sometimes
**🔹 NMF (Non-Negative Matrix Factorization)**
Factorizes document-term matrix into non-negative matrices
Produces more interpretable topics
Works best with TF-IDF features
📊 Results & Insights
LDA provides probabilistic topic distributions
LSA captures semantic relationships but less interpretable
NMF produces clear and human-readable topics

📌 Conclusion:
Each model has its strengths, but NMF often gives the most interpretable results, while LDA is best for probabilistic understanding of topics.
