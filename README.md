# 🤖 Wiki Discord Bot

A smart Discord bot that answers questions using a local FAQ file or an AI model via OpenRouter (like ChatGPT or Mistral).  
Ideal for FAQ-style help in channels like `#wiki-bot`.

## 🔧 Features

- ✅ Slash command `/help` for guidance
- 💬 Auto-responds to user messages in a specific channel
- 📁 Uses a local `faq_data.json` file
- 🧠 AI fallback via OpenRouter (e.g., Mistral)
- 🔒 Secure API key loading with `.env`
- ☁️ Hosted 24/7 on [Replit.com](https://replit.com)

## 📸 Demo
https://github.com/user-attachments/assets/892d9a8b-ed2d-4580-b8dc-965474873966

## 🗂 Folder Structure
📦 discord-wiki-bot/
├── main.py
├── faq_data.json
├── .env
├── requirements.txt
└── README.md

## 🚀 How to Run

2. Create a `.env` file:
   ```env
   DISCORD_BOT_TOKEN=your_token_here
   OPENROUTER_API_KEY=your_key_here


