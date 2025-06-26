# 🩺 General Health Chatbot – OpenAI GPT-3.5

This is a command-line health chatbot built using OpenAI's GPT-3.5 model. It safely answers **general health-related questions** while avoiding direct medical advice or prescriptions. Designed as part of my AI/ML Internship Task 4 and structured for real-world deployment.

---

## ✨ Features

- ✅ Powered by OpenAI GPT-3.5 Turbo  
- ✅ Secure API key handling using `.env`  
- ✅ Prompt-engineered for safe general health responses  
- ✅ Simple, clean, modular Python structure  
- ✅ Follows GitHub best practices (.env, venv, `__pycache__` ignored)

---

## 📁 Project Structure

health_chatbot/

├── main.py  Launch the chatbot

├── config.py  Contains API request logic

├── .env  Stores API key (not pushed to GitHub)

├── .gitignore  Ignores venv, .env, cache, pyc files

├── requirements.txt  Required packages (auto-install)

└── venv/  Virtual environment (ignored)

---

## 🚀 How to Run This Project (Step-by-Step)

### 🔹 1. Clone the Repository
```bash
`git clone https://github.com/jabran-adeel/Health-Chatbot-OpenAI-GPT-3.5.git
cd health_chatbot`
```
### 🔹 2. Create and Set Up .env File
Store your OpenAI secret key here (keep it private!)

Create a .env file and paste this inside:
```bash
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```
### 🔹 3. Create and Activate Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate     # On Windows
# or
source venv/bin/activate  # On macOS/Linux
```
### 🔹 4. Install Required Dependencies
```bash
pip install -r requirements.txt
```
### 🔹 5. Run the Chatbot
```bash
python main.py
```
💬 Ask the bot questions like:

`"What causes a sore throat?"`

`"Is it safe to drink milk during fever?"`

`"What are symptoms of the flu?"`
### 📈 Example Chat Interaction
```bash
You: What causes headaches?
Bot: Headaches can be caused by stress, dehydration, lack of sleep, or other common triggers. If they persist, it's best to consult a medical professional.
```
### 📦 Tech Stack
~ Python 3

~ OpenAI GPT-3.5 Turbo

~ python-dotenv

~ openai Python SDK

~ Virtual Environment (venv)

~ VS Code (recommended)

### 🔐 Git & Security Best Practices
✅ `.env` – hides your secret OpenAI key
✅ `.gitignore` – avoids pushing secrets, venv, and cache
✅ `requirements.txt` – clean dependency tracking for deployment
✅ Modular files – `main.py` for UI, `config.py` for API logic

### ⚠️ Disclaimer
This chatbot is for educational and informational use only. It does not provide any medical diagnosis, emergency guidance, or prescriptions.
Always consult a licensed healthcare professional for medical advice.

### 🙋‍♂️ Created by `Jabran Adeel`
This project is part of my AI/ML Internship Series.
⭐ Star this repo if it helped you, and feel free to fork or contribute!
