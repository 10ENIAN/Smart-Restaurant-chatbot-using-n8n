#Restaurant – AI Chatbot (n8n Workflow)

This project is an AI-powered restaurant chatbot built using n8n, LangChain, Google Gemini, and Google Sheets.
It automates food ordering, FAQ, stock checking, and order management for Kumari Restaurant in a simple WhatsApp-like chat style.

🚀 Features
1. Smart Chat-based Food Ordering

Welcomes users with a friendly message

Collects order details step-by-step

Checks inventory before confirming

Logs confirmed/rejected orders into Google Sheets

2. FAQ Support

Answers restaurant timing, delivery time, payment methods, etc.

3. Check Order / Check Stock

Retrieves order status from Google Sheets

Shows stock quantity from Inventory sheet

4. Memory-enabled Chat

Uses short-term memory for natural conversation

Handles returning users within the same session

5. Secure & Real-Time Data Storage

Orders, Inventory, and FAQ stored in Google Sheets

🔧 Credential Requirements
Required Credentials

Google Sheets OAuth2 (for Inventory, FAQ, Orders)

Google Gemini / PaLM API Key (for AI responses)



Easy to update without modifying workflow
