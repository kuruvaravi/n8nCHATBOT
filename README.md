# 🤖 n8nCHATBOT

A chatbot built using the **n8n workflow automation platform**, integrated with AI models and external APIs.

---

## 📌 Project Overview

This project demonstrates how to build a chatbot inside n8n using:

- Trigger node for receiving chat input
- AI Agent for processing messages
- Google Gemini Chat Model for AI responses
- Simple Memory node for storing conversation context
- HTTP Request node for additional API calls (SerpAPI example)

The chatbot can respond to messages, maintain context, and interact with APIs to fetch information dynamically.

---

## 🛠️ Features

✔ Handles chat messages through workflow trigger  
✔ Uses Google Gemini / AI Agent for responses  
✔ Stores memory between messages  
✔ Supports API calls via HTTP Request node  
✔ Can be deployed and shared  

---

## 📂 Workflow Structure
When Chat Message Received
|
▼
AI Agent
|
|--- Simple Memory
|
|--- Google Gemini Chat Model
|
|--- HTTP Request (SerpAPI example)

## 🚀 How to Use

1. Install n8n locally or cloud
2. Import **Search Ai Agent.json** into the workflow editor
3. Configure environment variables:
   - Gemini API Key
   - SerpAPI Key (optional)
4. Activate workflow
5. Send chat messages


## 🔐 Required API Keys

- `GEMINI_API_KEY`
- `SERPAPI_KEY` (optional)

Store them in n8n Credentials securely.

## 🎥 Demo Video
Click below to watch the workflow demo:



