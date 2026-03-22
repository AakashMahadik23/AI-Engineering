# ✈️ FlightAI – Airline Chatbot with Tool Calling (Ollama + SQLite + Gradio)

FlightAI is an AI-powered airline assistant that provides ticket prices using a local database.  
It uses **LLM + Tool Calling + SQLite** to fetch real-time structured data.

## 🚀 Features

- 🤖 Chat-based airline assistant
- 🧠 Powered by **Ollama (LLaMA 3.2)**
- 🛠️ Function calling (Tool usage)
- 💾 SQLite database for ticket prices
- 🎯 Short, accurate responses
- 🌐 Simple UI using Gradio

## 🏗️ Tech Stack

- **Python**
- **Ollama (Local LLM)**
- **OpenAI Python SDK (compatible with Ollama)**
- **SQLite**
- **Gradio**

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/FlightAI.git
cd FlightAI

Install dependencies
pip install openai gradio python-dotenv

Install & Run Ollama
Download Ollama from: https://ollama.com

Run the model:
ollama run llama3.2