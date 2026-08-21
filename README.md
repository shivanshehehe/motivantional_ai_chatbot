# 🤖 AI Study & Motivation Assistant

An AI-powered study and motivation chatbot built with **Python, OpenAI API, and Jupyter Notebook**.

The assistant understands the user's mood and provides personalized motivational messages and practical study advice.

## ✨ Features

- 🤖 AI-powered conversational assistant
- 🧠 Basic mood detection
- 💬 Personalized motivational responses
- 📚 Study guidance and productivity advice
- 📝 Chat history storage
- 🖥️ Simple command-line interface
- 🔐 Secure API key handling using environment variables

## 🛠️ Technologies Used

- 🐍 Python
- 🤖 OpenAI API
- 📓 Jupyter Notebook
- 🔐 python-dotenv

## 🧠 How It Works

The chatbot first analyzes the user's message to detect a basic mood such as:

- 😊 Happy
- 😔 Sad
- 😰 Stressed
- 😴 Tired
- 😐 Normal

The detected mood is then included in the prompt sent to the AI model.

The AI generates a response focused on:

1. Understanding the user's emotion
2. Providing motivation
3. Giving practical study advice
4. Keeping the response simple and positive

## 📂 Project Structure

```text
motivantional_ai_chatbot/
│
├── chatbot_project.ipynb   # Main chatbot implementation
├── chat_history.txt        # Saved conversation history
├── .gitignore              # Protects environment files
└── README.md
