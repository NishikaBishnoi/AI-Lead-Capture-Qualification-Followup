# AI Lead Capture, Qualification & Follow-up Automation

An AI-powered lead management workflow built with n8n, Google Gemini, Google Sheets, and Gmail.

## Overview
This project automates the lead management process, from capturing incoming inquiries to AI-based qualification, CRM record creation, and email follow-up.

## Workflow Features
- **Lead Capture:** Receives lead details through a webhook.
- **AI Qualification:** Uses Google Gemini to summarize leads, identify their interests and urgency, and recommend follow-up actions.
- **CRM Integration:** Stores lead information and AI-generated insights in Google Sheets.
- **Automated Follow-up:** Sends email responses using Gmail.
- **Workflow Automation:** Connects multiple services into a single n8n workflow.

## Technology Stack
- n8n
- Google Gemini AI
- Webhooks and HTTP requests
- Google Sheets
- Gmail
- JSON

## Workflow Process
1. A lead submits their information.
2. The webhook receives the lead data.
3. The AI Agent analyzes and qualifies the lead.
4. The workflow saves the lead details and qualification results to Google Sheets.
5. Gmail sends the configured follow-up email.

## Setup Instructions
1. Download the workflow JSON from the `workflows` folder.
2. Import the JSON into your n8n instance.
3. Configure your own Google Gemini, Google Sheets, and Gmail credentials.
4. Review the webhook configuration and update any environment-specific settings.
5. Test the workflow with sample data before using real leads.

## Security
Never upload API keys, access tokens, passwords, private customer data, or confidential company information. Configure credentials securely inside n8n.

## Author
Nishika Bishnoi

AI Automation | Workflow Design | API Integration | CRM Automation
