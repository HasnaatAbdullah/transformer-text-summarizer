# t5-question-answering
Implementation of Question Answering using the T5 Transformer model. This project demonstrates pretraining on the C4 dataset, fine-tuning on SQuAD 2.0, and building a custom QA system.
# 🤖 Question Answering with T5 (Text-to-Text Transfer Transformer)

This repository contains my implementation of **Question Answering** using the **T5 Transformer model**.  
The project focuses on **pretraining** the T5 model on the **C4 dataset**, **fine-tuning** it on the **SQuAD 2.0 dataset**, and building a **custom Question Answering system**.

T5 converts **every NLP problem** into a **text-to-text format**, making it highly flexible for tasks like summarization, translation, and QA.

---

## 🚀 Project Overview

This project demonstrates:

1. **Pretraining T5** on the **C4 dataset** using a **masked language modeling** objective.
2. **Fine-tuning T5** on **SQuAD 2.0** for **question answering**.
3. Implementing a **custom QA system** capable of answering natural language queries.

---

## 📌 Key Features
- 🔹 Implements **T5 Transformer architecture** for text-to-text tasks.
- 🔹 Uses **C4 (Colossal Clean Crawled Corpus)** for pretraining.
- 🔹 Fine-tunes on **SQuAD 2.0** for better QA performance.
- 🔹 Preprocessing pipeline includes **tokenization, masking, and sequence generation**.
- 🔹 Builds a **custom inference function** to answer user-defined questions.
- 🔹 Hands-on implementation using **TensorFlow** and **Hugging Face**.

---

## 🧩 Project Workflow

| Step                              | Description |
|----------------------------------|------------|
| **Data Preparation**            | Process the **C4 dataset** and prepare text pairs |
| **Tokenization & Masking**      | Apply **SentencePiece tokenizer** and masking for pretraining |
| **T5 Pretraining**             | Train on C4 using a masked language modeling objective |
| **Fine-tuning**                | Use **SQuAD 2.0 dataset** to improve QA performance |
| **Question Answering**         | Implement a **predict()** function to answer queries |

---

## 📂 Project Structure

```bash
t5-question-answering/
│── data/                     # C4 and SQuAD datasets
│── notebooks/                # Jupyter notebook implementation
│── models/                   # Pretrained and fine-tuned T5 models
│── results/                  # Evaluation metrics and predictions
│── utils/                    # Helper functions for preprocessing & evaluation
│── requirements.txt          # Project dependencies
└── README.md                # Documentation
