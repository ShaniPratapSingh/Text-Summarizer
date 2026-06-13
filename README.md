# 🚀 AI Text Summarizer

An AI-powered Text Summarization web application built using **FastAPI**, **PyTorch**, and **Hugging Face Transformers**. The application leverages a fine-tuned **T5 Transformer Model** to generate concise and meaningful summaries from lengthy text inputs through an intuitive web interface.

---

## 📌 Overview

Reading and understanding large amounts of text can be time-consuming. This project addresses that challenge by automatically generating concise summaries while preserving the essential information from the original content.

The application provides a simple and responsive interface where users can input long text passages and receive AI-generated summaries in real time.

---

## ✨ Features

* AI-powered text summarization
* Fine-tuned T5 Transformer model
* FastAPI backend for high-performance inference
* Responsive and user-friendly interface
* Real-time summary generation
* Automatic text preprocessing and cleaning
* Supports CPU, CUDA, and Apple Silicon (MPS)

---

## 🏗️ System Architecture

```text
User Input
    │
    ▼
Frontend (HTML/CSS/JavaScript)
    │
    ▼
FastAPI Backend
    │
    ▼
Text Preprocessing
    │
    ▼
Fine-Tuned T5 Model
    │
    ▼
Generated Summary
    │
    ▼
User Interface
```

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* FastAPI
* Pydantic
* Jinja2

### Machine Learning

* PyTorch
* Hugging Face Transformers
* T5 Transformer

### Development Tools

* Git
* GitHub
* Jupyter Notebook

---

## 📂 Project Structure

```text
Text-Summarizer/
│
├── app.py
├── index.html
├── requirements.txt
├── README.md
│
└── saved_summary_model/
    ├── config.json
    ├── generation_config.json
    ├── tokenizer.json
    ├── tokenizer_config.json
    └── model.safetensors
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Text-Summarizer.git
cd Text-Summarizer
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### macOS/Linux

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Locally

```bash
uvicorn app:app --reload
```

Open:

```text
http://127.0.0.1:8000
```

---

## 📡 API Endpoint

### POST /summarize/

#### Request

```json
{
  "dialogue": "Artificial Intelligence is transforming industries..."
}
```

#### Response

```json
{
  "summary": "AI is transforming industries through automation and intelligent decision-making."
}
```

---

## 🧠 Model Information

* Base Model: T5 Transformer
* Framework: Hugging Face Transformers
* Training Environment: Jupyter Notebook
* Inference Framework: FastAPI
* Device Support:

  * CPU
  * NVIDIA CUDA GPU
  * Apple Silicon (MPS)

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

* Natural Language Processing (NLP)
* Transformer-based architectures
* Fine-tuning Hugging Face models
* FastAPI development
* Model deployment workflows
* API integration with frontend applications

---

## 🔮 Future Enhancements

* PDF Summarization
* Document Upload Support
* Multi-Language Summarization
* User Authentication
* Dark Mode
* Summary Download (PDF/TXT)
* Cloud Deployment

---

## 👨‍💻 Author

**Shani Pratap Singh**

---

⭐ If you found this project useful, consider giving it a star.
