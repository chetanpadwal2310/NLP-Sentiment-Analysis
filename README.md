# NLP Sentiment Analysis

A simple **Natural Language Processing (NLP)** project that predicts whether a given text/review is **Positive or Negative**.

The project demonstrates text preprocessing, feature extraction using `CountVectorizer`, machine learning classification, and deployment through a **Gradio interface**.

##  Features

* Text preprocessing
* HTML tag removal
* Punctuation removal
* Chat-word expansion
* Stopword removal
* Emoji handling
* Stemming
* Lemmatization
* Text vectorization using CountVectorizer
* Sentiment prediction using a trained ML model
* Interactive Gradio web interface

##  Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Gradio
* Jupyter Notebook

## Project Workflow

```text
User Review
    ↓
Text Preprocessing
    ↓
Stemming & Lemmatization
    ↓
CountVectorizer
    ↓
Machine Learning Model
    ↓
Sentiment Prediction
    ↓
Positive / Negative
```

##  How to Run

Install the required libraries:

```bash
pip install pandas numpy nltk scikit-learn gradio
```

Open the Jupyter Notebook:

```text
Sentiment_Analysis_chetan.ipynb
```

Run the cells in sequence and launch the Gradio interface.

##  Example

**Input:**

```text
This movie was absolutely fantastic!
```

**Output:**

```text
Positive
```

## 📌 Project Type

**Natural Language Processing + Machine Learning**

This project is a foundation for learning more advanced NLP techniques such as **TF-IDF, Word Embeddings, BERT, Transformers, Large Language Models (LLMs), and Generative AI**.
