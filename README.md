# ai-health-assistant
An offline AI-powered health assistant for rural clinics, built with LangChain, Python, and Vosk. It helps health workers triage patient symptoms using voice input, local databases, and secure logging-designed for low-resource environments.
# 🩺 AI Health Assistant for Rural Clinics

A LangChain-powered offline AI agent that helps rural health workers triage patient symptoms using voice input, local databases, and secure logging.

## 🔧 Features
- Offline voice-to-text using Vosk
- Symptom triage using LangChain + TinyDB
- Encrypted patient logs for privacy
- CLI interface for low-resource environments

## 📁 Project Structure
- `main.py`: Entry point for the assistant
- `db/symptoms_db.json`: Offline symptom triage database
- `audio/input.wav`: Sample voice input
- `models/`: Vosk speech recognition model
- `utils/`: Modular tools for voice, encryption, and agent logic

## 🚀 Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/ai-health-assistant.git
cd ai-health-assistant

pip install -r requirements.txt

python main.py

🗣️ Recognized Symptom: fever
🩺 Triage Advice: Monitor temperature. Refer if >102°F or persistent >3 days.
🔐 Encrypted Log: gAAAAAB...


---

## 📄 requirements.txt

```txt
langchain
openai
tinydb
vosk
cryptography
