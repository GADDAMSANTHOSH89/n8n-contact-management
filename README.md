# n8n Contact Management Automation

## 📌 Overview
This project automates contact form submissions using **n8n**.

## 🚀 Workflow
Webhook → Validation → Google Sheets → Email → WhatsApp Alert

## 🧰 Tools Used
- n8n
- Google Sheets API
- Gmail API
- Twilio WhatsApp API
- Webhooks

## 🏗 Architecture

User → Webhook (n8n)  
→ Data Validation  
→ Google Sheets (Storage)  
→ Gmail (Email Alert)  


## 📥 Input Fields
- Name
- Email
- Phone
- Message

## 📤 Outputs
- Stores contact in Google Sheet
- Sends email alert
- Sends WhatsApp notification

## 📂 Files
- contact-management-workflow.json (n8n workflow export)

## 👤 Author
Santhosh Gaddam
