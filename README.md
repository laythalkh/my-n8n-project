# AI Restaurant Automation Agent 🍔

This project is an AI-powered automation system built using n8n.

## 🚀 What it does
- Receives customer orders via webhook
- Uses AI (Llama 3) to convert text into structured JSON
- Calculates preparation time automatically
- Stores orders in Google Sheets
- Sends real-time notifications via WhatsApp
- Returns a response to the customer

## 🧠 Tech Stack
- n8n (Automation)
- Ollama (Llama 3)
- Google Sheets
- Twilio WhatsApp API

## ⚙️ How to use
1. Import the workflow.json into n8n
2. Connect your credentials:
   - Google Sheets
   - Twilio
3. Replace placeholders:
   - ACCOUNT_SID
   - Phone numbers
   - Sheet ID
4. Run the workflow

## 📌 Notes
- This is a template project (no real credentials included)
- Designed as a real-world automation use case

## 💡 Use Case
Perfect for restaurants to automate:
- Order processing
- Kitchen notifications
- Customer responses