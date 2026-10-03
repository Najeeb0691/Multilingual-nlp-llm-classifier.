# Multilingual NLP Topic Classification & Normalization Pipeline

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Kaggle Score](https://img.shields.io/badge/Kaggle_Public_Score-0.57686-success.svg)](#results)

An end-to-end Machine Learning and LLM text-processing pipeline designed for multilingual topic classification and headline generation across low-resource African languages (Yoruba, Hausa, Igbo, and Nigerian Pidgin). Developed for the **DSN Bootcamp Hackathon 2026**.

---

## 📌 Key Technical Highlights

- **Multilingual Handling:** Processes and classifies news headlines in Yoruba, Hausa, Igbo, and Pidgin while preserving native UTF-8 diacritics and character encodings.
- **Automated Text Normalization:** Engineered regex-based cleaning functions to strip model chatter, markdown artifacts, quotes, and unwanted formatting.
- **Multi-Task Submission Schema:** Programmatically maps and formats predictions across 3,486 evaluation entries with `[id]_topic` (classification) and `[id]_headline` (text extraction) output rows.
- **Benchmarked Baselines:** Evaluated TF-IDF + LinearSVC and Groq LLM API inference, achieving a top verified score of **0.57686**.

---

## 📊 Results & Validation

| Model Pipeline | Benchmark Score | Target Rows | Schema Status |
| :--- | :--- | :--- | :--- |
| **Groq LLM / LinearSVC Pipeline** | **0.57686** | **3,486** | **Verified (100% Match)** |

---

## 🚀 How to Run

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Najeeb0691/multilingual-nlp-llm-classifier.git](https://github.com/Najeeb0691/multilingual-nlp-llm-classifier.git)
   cd multilingual-nlp-llm-classifier

   pip install -r requirements.txt
   

