# 📝 Transformer-based Text Summarization

This repository contains my implementation of a **Transformer Summarizer** using an **Encoder-Decoder architecture**.  
The project demonstrates **how Transformers use attention mechanisms** to generate concise summaries of long texts.

This implementation builds a summarization model from scratch using **multi-head attention**, **positional encoding**, **causal masking**, and a **fully custom Transformer decoder**.

---

## 🚀 Project Overview

This project covers:

1. Implementing the **scaled dot-product attention** mechanism.
2. Building a **Transformer Decoder** from scratch.
3. Using **masking techniques** to manage dependencies.
4. Training the model for **abstractive summarization**.
5. Evaluating and generating **summaries for unseen text**.

---

## 📌 Key Features
- 🧠 Implements the **Transformer architecture** from scratch.
- 🧩 Builds **custom encoder-decoder blocks**.
- 🔹 Uses **multi-head attention** and **positional encoding**.
- 🛠️ Implements **causal masking** for sequential decoding.
- 📄 Generates **abstractive summaries** of long-form text.
- 🖼️ Includes visualizations of **attention weights** and **training metrics**.

---

## 🧩 Project Workflow

| Step                        | Description |
|---------------------------|------------|
| **Data Preprocessing**    | Tokenizes and cleans text for summarization |
| **Positional Encoding**   | Encodes token positions for sequential awareness |
| **Scaled Dot-Product Attention** | Computes context-based attention scores |
| **Multi-Head Attention**  | Uses multiple heads for better context learning |
| **Decoder Implementation**| Builds the Transformer decoder block manually |
| **Training**              | Trains the summarizer on the dataset |
| **Evaluation**            | Generates summaries and evaluates performance |

---

## 📂 Project Structure

```bash
transformer-text-summarizer/
│── data/                  # Training & test datasets
│── notebooks/             # Jupyter notebook implementation
│── models/                # Saved models & checkpoints
│── utils/                 # Helper functions for attention, masking, etc.
│── results/               # Evaluation metrics & sample summaries
│── requirements.txt       # Dependencies
└── README.md             # Project documentation
