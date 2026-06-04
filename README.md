# 🤖 AI Interview Question Generator

> Generate technical interview questions instantly using Generative AI.

---

## 📌 Overview

AI Interview Question Generator is a GenAI-powered tool that creates
technical interview questions on any topic using **Llama 3.3 70B** 
via the **Groq API**. Built as part of the YBI Foundation Internship 
program.

---

## 🚀 Features

- ✅ Topic-based question generation
- ✅ Difficulty level selection (Easy / Medium / Hard)
- ✅ Custom number of questions (1–10)
- ✅ Powered by Llama 3.3 70B (fast inference via Groq)
- ✅ Secure API key handling via Colab Secrets
- ✅ Saves output to .txt file
- ✅ Runs on Google Colab (no local setup needed)

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core programming language |
| Groq API | LLM inference engine |
| Llama 3.3 70B | Question generation model |
| Google Colab | Development environment |

---

## ⚙️ Setup & Usage

### 1. Get Groq API Key
- Visit [console.groq.com](https://console.groq.com)
- Sign up → Create API Key → Copy it

### 2. Open in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gKa9-Jxrd7jJ3RxSiA4b1DTs2EkNvw03?usp=sharing)

### 3. Add Your API Key Safely
- Open the 🔑 **Secrets** tab in Google Colab (left sidebar)
- Click **Add new secret**
- Name: `GROQ_API_KEY` → Value: paste your key
- Enable notebook access toggle
- ✅ Key is never hardcoded or exposed in the notebook

### 4. Install & Run
```python
pip install groq
```
Then run all cells — enter topic, difficulty, and number of questions when prompted.

---

## 📄 Sample Output
<img width="1884" height="928" alt="image" src="https://github.com/user-attachments/assets/9912d1f9-728a-4bf3-a397-c8d60bc10207" />





