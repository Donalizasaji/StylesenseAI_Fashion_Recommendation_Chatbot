# 👗 StyleSense AI – Fashion Recommendation Chatbot

## 🚀 Overview

**StyleSense AI** is an intelligent fashion recommendation chatbot that uses **Retrieval-Augmented Generation (RAG)** and **Large Language Models (LLMs)** to provide personalized outfit, styling, and color suggestions.

The system combines semantic search with conversational AI to deliver context-aware fashion advice based on knowledge extracted from fashion documents.

## 🎥 Demo Video

[![Watch the demo](https://img.youtube.com/vi/uyah8vyBtHU/0.jpg)](https://www.youtube.com/watch?v=uyah8vyBtHU)

## 💡 Features

* 👗 Personalized outfit recommendations
* 🎨 Smart color combination suggestions
* 👜 Accessory and styling tips
* 💬 Conversational AI stylist experience
* 📄 Knowledge grounded in fashion PDF (RAG)
* 🧠 Context-aware responses using LLM

---

## 🧠 How It Works

1. 📄 Extracts text from a fashion PDF
2. ✂️ Splits text into smaller chunks
3. 🔎 Converts chunks into embeddings using Sentence Transformers
4. 📊 Retrieves relevant chunks using cosine similarity
5. 🤖 Sends context + query to LLM (Qwen2.5)
6. ✨ Generates human-like fashion recommendations

---

## 🛠️ Tech Stack

* **Python**
* **Transformers (HuggingFace)**
* **Sentence Transformers**
* **Scikit-learn (Cosine Similarity)**
* **PyPDF**
* **Gradio (UI)**

---

## 📂 Project Structure

```
.
│
├── fashion_recommendation_chatbot.ipynb
├── requirements.txt
├── README.md
├── .gitignore
│
├── data/
│   └── fashion.pdf
│
├── assets/
│   └── background.jpg

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/stylesense-ai.git
cd stylesense-ai

pip install -r requirements.txt
```

---


---

## 🎯 Example Use Cases

* “Suggest a wedding outfit for summer”
* “What should I wear for an office meeting?”
* “How to style a black dress?”

---

## 🔥 Key Highlights

* Implements **Retrieval-Augmented Generation (RAG)**
* Uses **semantic similarity search for context retrieval**
* Integrates a **lightweight LLM for real-time responses**
* Designed with a **custom-styled interactive UI**

---

## 🚀 Future Improvements

* 🎤 Voice-based interaction
* 🖼️ Outfit image generation
* 👤 User personalization & preferences
* ☁️ Deployment (HuggingFace Spaces / Render)

---

## 👩‍💻 Author

**Dona Liza Saji**
Master’s in Artificial Intelligence & Machine Learning

---



