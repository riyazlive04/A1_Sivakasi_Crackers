# A1 Sivakasi Crackers – WhatsApp Payment Reminder Automation

This n8n workflow automates monthly WhatsApp payment reminders using Evolution API.

⚠️ Important: Evolution API is an **unofficial WhatsApp API**. It does **not use WhatsApp Cloud API** and has **no WhatsApp conversation charges**. Messages are sent via a linked WhatsApp device.

The workflow runs on the 1st of every month, reads customer payment status from Google Sheets, calculates monthly installment amounts, and sends scheduled reminder messages only to customers with pending payments.

## Requirements
- n8n (self-hosted or cloud)
- Evolution API (unofficial, device-based)
- Google Sheets (customer & payment data)
- WhatsApp account linked via Evolution API

## WhatsApp Device Setup (Required)
Link your WhatsApp device here:
https://message.sirahagents.com/manager/

## Features
- Monthly scheduled trigger
- Dynamic month detection
- Google Sheets integration
- Automatic installment calculation
- WhatsApp reminders with no conversation cost
- Delay control & batching
- Error handling and logging

## Usage
1. Import the JSON into n8n
2. Connect Google Sheets credentials
3. Link your WhatsApp device using Evolution API
4. Activate the workflow

Best suited for scheme-based, installment, and subscription businesses.
