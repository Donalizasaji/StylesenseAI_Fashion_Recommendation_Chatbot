# 👗 StyleSense AI – Fashion Recommendation Chatbot

## 🚀 Overview

**StyleSense AI** is an intelligent fashion recommendation chatbot that uses **Retrieval-Augmented Generation (RAG)** and **Large Language Models (LLMs)** to provide personalized outfit, styling, and color suggestions.

The system combines semantic search with conversational AI to deliver context-aware fashion advice based on knowledge extracted from fashion documents.

---

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
stylesense-ai/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── data/
│   └── fashion.pdf
│
├── assets/
│   └── background.jpg
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/stylesense-ai.git
cd stylesense-ai

pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app.py
```

The app will launch in your browser using Gradio.

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



