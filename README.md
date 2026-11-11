# Day3-AI_challenge
# 🚀 Day 3 – Text is Data (Turning Words into Numbers) | 60 Days AI Coding Challenge

Welcome to Day 3 of my **60 Days AI Coding Challenge**!

Machines do not read words directly—they read numbers. Preprocessing is the fundamental first transformation that turns raw human language into structured numerical data that Machine Learning models can understand.

This repository contains my Day 3 implementation of the complete Natural Language Processing (NLP) preprocessing pipeline and Bag-of-Words representation.

---

## 🎯 Tasks Completed

### 1. Text Cleaning & Normalization
- Converted raw input text to lowercase.
- Stripped punctuation marks using Python's `string` module.
- Retained clean text tokens without external model dependencies.

### 2. Tokenization
- Split sentences into individual word tokens.
- Structured the raw sentence into discrete units ready for feature filtering.

### 3. Stop Words Removal
- Filtered out high-frequency, non-informative English stop words (*is, the, and, at, they, etc.*).
- Isolated meaningful context-bearing keywords.

### 4. Bag-of-Words (BoW) Representation
- Converted cleaned tokens into a document-term frequency matrix using Scikit-Learn's `CountVectorizer`.
- Formatted the vector output into a clear Pandas DataFrame representing Machine Learning input.

---

## 📊 Before & After Comparison

### 1. Raw Text (Before)
```text
Machines do not read words directly. They read numbers!
Natural Language Processing turns human language into data.
