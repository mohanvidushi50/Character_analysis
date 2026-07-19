# 📖 Character Analysis using NLP

This project is one of my learning projects while exploring **Natural Language Processing (NLP)** with **NLTK** and **spaCy**.

Instead of building a basic sentiment classifier, I wanted to work on something that felt more practical. The idea was to analyze an entire novel, identify the important characters automatically, understand the emotions throughout the story, and see how different NLP techniques work on real-world text.

For this project- I have  used *The Palace of Illusions* by Chitra Banerjee Divakaruni.

---

##  What this project does

- Cleans and preprocesses the novel
- Compares **Stemming** and **Lemmatization**
- Detects important characters using **Named Entity Recognition (NER)**
- Counts how frequently each character appears
- Creates simple character profiles
- Tracks the emotional journey of the story chapter by chapter using sentiment analysis
- Generates a word cloud of the most common words in the novel

---

## 🧠 NLP Concepts Used

- Text preprocessing
- Sentence & word tokenization
- Stopword removal
- Porter Stemmer
- WordNet Lemmatizer
- POS Tagging
- Named Entity Recognition (spaCy)
- VADER Sentiment Analysis
- Data Visualization

---

The notebook generates:

- Preprocessed text
- Stemming vs Lemmatization comparison
- List of detected characters
- Bar chart of most frequently mentioned characters
- Chapter-wise Emotional Arc
- Character profiles including:
  - Mention count
  - Average sentiment
  - Simple speech style analysis
-- Word Cloud

---

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Run the setup cells.
3. Upload your own `.txt` copy of the book.
4. Run all the cells in order.

If your book uses a different chapter format, you may need to modify the chapter splitting regex.

---

## ⚠️ Copyright

This repository only contains the analysis code.

The text of *The Palace of Illusions* is **not included** because it is copyrighted, to run this project upload your own legally obtained `.txt` copy of the book. You may need to alter or update code for i have specificy printed certain characters.

---

## What I Learned

Through this project, I got hands-on experience with:

- Working with unstructured text data
- NLP preprocessing techniques
- Named Entity Recognition
- Sentiment Analysis
- Data visualization
- Building an end-to-end NLP pipeline

It also gave me a better understanding of how multiple NLP techniques can be combined to extract meaningful insights from long-form text.

---

##  Requirements

The notebook automatically installs all required libraries inside Google Colab, so no additional setup is needed.
