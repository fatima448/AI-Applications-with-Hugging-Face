# Hugging Face Chatbot (BlenderBot)

## 🤖 Overview
This project implements a conversational chatbot using a pre-trained
Hugging Face transformer model.

The chatbot is built with **Facebook BlenderBot (400M distilled)** and
demonstrates how to load, interact with, and maintain conversation
context using modern NLP models.

---

## 🧠 Model Used
- **facebook/blenderbot-400M-distill**
- Pre-trained sequence-to-sequence transformer
- Designed for open-domain conversational AI

---

## ✨ Features
- Text-based chatbot interaction
- Maintains conversation history
- Generates dynamic responses using sampling
- Adjustable generation parameters (max length, temperature)

---

## 🛠️ Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Jupyter Notebook

---

## ⚙️ How It Works
1. Loads tokenizer and model from Hugging Face
2. Accepts user input as text
3. Maintains conversation history
4. Concatenates past messages to preserve context
5. Generates responses using the transformer model

---

## ▶️ How to Run
1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Install dependencies:
   ```bash
   pip install transformers torch
