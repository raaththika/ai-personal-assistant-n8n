# 🤖 AI Personal Assistant (n8n + Telegram)

An AI-powered **personal assistant built with n8n** that interacts via **Telegram** and can:

- 💬 Chat intelligently using OpenAI
- 📧 Send emails via Gmail
- 📅 Create Google Calendar events
- 🧠 Maintain short-term conversational memory

This workflow demonstrates how to build a **tool-using AI agent** inside n8n using LangChain nodes.

---

## ✨ Features

- Telegram-based conversational interface
- AI Agent powered by OpenAI (GPT-4.1-mini or compatible)
- Email sending via Gmail
- Google Calendar event creation
- Automatic clarification when required details are missing
- Memory buffer for contextual conversations

---

## 🧩 Workflow Overview

**User → Telegram → AI Agent → Tools → Telegram**

1. User sends a message on Telegram  
2. AI Agent interprets intent  
3. Agent:
   - asks clarifying questions if needed
   - sends emails
   - creates calendar events
4. Agent confirms actions back to the user via Telegram

---

## 🛠️ Tech Stack

- **n8n**
- **Telegram Bot API**
- **OpenAI (Chat Model)**
- **Gmail API**
- **Google Calendar API**
- **LangChain (via n8n nodes)**

---

## 📦 Requirements

- n8n (Cloud or Self-Hosted)
- Telegram Bot
- OpenAI API Key
- Google account with:
  - Gmail API enabled
  - Google Calendar API enabled

---

## 📥 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/ai-personal-assistant-n8n.git
cd ai-personal-assistant-n8n
