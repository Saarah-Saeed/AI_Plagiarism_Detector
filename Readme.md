# 🔬 PlagioScan AI

An AI-powered plagiarism detection system that goes beyond exact text matching by combining **Semantic Analysis**, **Stylometric Analysis**, and **TF-IDF Keyword Matching**.

## 🚀 Features

* Semantic similarity detection using Sentence Transformers
* Stylometric analysis to compare writing styles
* TF-IDF based keyword similarity scoring
* Single Text Analysis mode
* Compare Two Texts mode
* Multiple input methods:

  * Text Input
  * File Upload (.txt, .pdf, .docx)
  * URL-based text extraction
* Interactive Streamlit web interface
* Real-time plagiarism risk assessment

## 🛠️ Tech Stack

* Python
* Streamlit
* Sentence Transformers (all-MiniLM-L6-v2)
* Scikit-learn
* NLTK
* NumPy
* BeautifulSoup4
* PyPDF2
* python-docx

## 📊 Detection Pipeline

1. Input collection (Text, File, or URL)
2. Text preprocessing and sentence tokenization
3. Semantic embedding generation using Sentence Transformers
4. Cosine similarity calculation
5. Stylometric feature extraction
6. TF-IDF keyword similarity analysis
7. Risk classification (Safe, Moderate, High Risk)
8. Interactive result visualization

## 🎯 Plagiarism Risk Levels

* 🟢 Safe
* 🟡 Moderate
* 🔴 High Risk
