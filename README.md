# 🌆 City Agent — AI-Powered City Assistant

## 🚀 Overview

City Agent is an intelligent AI assistant that provides **real-time weather updates 🌦️** and **latest news 📰** for any city using natural language.

It uses **LLMs + APIs + tools** to act like a smart city companion.

--- 

## ✨ Features

* 🌦️ Get real-time weather data
* 📰 Fetch latest city news
* 🧠 AI-powered natural language understanding
* 🔐 Human approval before tool execution
* 🎨 Clean CLI interface with styled output

---

## 🛠️ Tech Stack

* Python
* LangChain
* Mistral AI
* Tavily API (news search)
* OpenWeather API
* Rich (CLI UI)
* PyFiglet (ASCII UI)

---

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/your-username/city-agent.git
cd city-agent
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Setup environment variables

Create a `.env` file:

```
OPENWEATHER_API_KEY=your_key
TAVILY_API_KEY=your_key
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 💡 Usage Examples

```
You: What's the weather in Bangalore?
You: Latest news in Delhi
```

---

## 🔒 Safety Feature

Before executing any tool:

```
Agent wants to call 'get_weather'. Approve? (y/n):
```

---

## 📌 Project Structure

```
main.py
.env
requirements.txt
```

---

## 🚀 Future Improvements

* Voice assistant integration
* GUI version
* Multi-city comparison
* Travel recommendations

---

## 👨‍💻 Author

Built as an AI + automation project using modern LLM tools.
