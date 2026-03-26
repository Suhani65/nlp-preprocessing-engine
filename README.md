# nlp-preprocessing-engine
# 🧠 NLP Preprocessing Engine (Advanced)

## 📌 Overview

This project focuses on building a **robust and scalable NLP preprocessing pipeline** to clean and transform noisy real-world text into meaningful tokens for machine learning applications.

---

## 🎯 Objectives

* Handle messy and unstructured text data
* Remove noise such as URLs, numbers, emojis, and repeated characters
* Normalize text for better NLP model performance
* Perform token-level and frequency analysis

---

## ⚙️ Features

* ✅ Lowercasing text
* ✅ Removal of URLs and email patterns
* ✅ Removal of numbers and special characters
* ✅ Handling repeated characters (e.g., "soooo" → "so")
* ✅ Removal of extra spaces
* ✅ Filtering short tokens (with exceptions like "no", "not")
* ✅ Tokenization and clean sentence generation

---

## 🧪 Tasks Covered

### 🔹 Task 1: Conceptual Understanding

Explains key NLP concepts such as case sensitivity, stopwords, stemming, and lemmatization.

### 🔹 Task 2: Preprocessing Function

Implements a modular function `preprocess_text()` to clean and normalize text.

### 🔹 Task 3: Stress Testing

Tests the function on diverse noisy inputs including emojis, slang, URLs, and repeated characters.

### 🔹 Task 4: Token Analytics

Computes:

* Total tokens
* Unique tokens
* Average token length

### 🔹 Task 5: Frequency Analysis

Uses `Counter` to identify:

* Top 10 most frequent words
* Top 5 least frequent words

### 🔹 Task 6: Full Pipeline

Builds a reusable pipeline:

```python
def full_pipeline(text_list):
```

### 🔹 Task 7: Error Handling

Handles edge cases such as:

* Empty input
* Only emojis
* Only numbers

---

## 🛠️ Tech Stack

* Python 🐍
* Google Colab / Jupyter Notebook
* Libraries: `re`, `collections`

---

## 📂 Project Structure

```
NLP_Preprocessing_Engine.ipynb
README.md
```

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter
2. Run all cells sequentially
3. View preprocessing outputs and analysis

---

## 📊 Sample Input

```
"I absolutely looooved this product 😍😍"
```

## 📊 Sample Output

```
Tokens: ['absolutely', 'loved', 'this', 'product']
Clean Sentence: absolutely loved this product
```

---

## 💡 Key Learnings

* Importance of text normalization in NLP
* Handling real-world noisy data
* Writing modular and reusable preprocessing pipelines
* Performing token-level and frequency analysis

---

## 🔗 Submission

GitHub repository link is submitted as part of the internship assignment.

---

## 🙌 Author

**Suhani Sharma**
