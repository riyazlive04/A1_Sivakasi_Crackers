# A1 Sivakasi Crackers – WhatsApp Payment Reminder Automation

This n8n workflow automates monthly WhatsApp payment reminders using Evolution API.

The automation runs on the 1st, 3rd, 5th, 7th, and 9th of every month, reads customer payment status from Google Sheets, calculates monthly installment amounts, and sends polite reminder messages only to customers with pending payments.

Messages are sent in a scheduled manner with delays to avoid spam and WhatsApp rate limits. The workflow supports primary and secondary phone numbers and handles errors gracefully.

## Requirements
- n8n (self-hosted or cloud)
- Evolution API
- Google Sheets (customer & payment data)
- WhatsApp device linked to Evolution API

## WhatsApp Device Setup (Required)
Before using this workflow, link your WhatsApp device here:
https://message.sirahagents.com/manager/

## Features
- Monthly scheduled trigger
- Dynamic month detection
- Google Sheets integration
- Automatic installment calculation
- WhatsApp reminders via Evolution API
- Delay control & batching
- Error handling and logging

## Usage
1. Import the JSON into n8n
2. Connect Google Sheets credentials
3. Link your WhatsApp device using Evolution API
4. Activate the workflow

This workflow is ideal for scheme-based, installment, or subscription businesses.
