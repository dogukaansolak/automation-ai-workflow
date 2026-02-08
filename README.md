# Automation & AI Workflow (n8n)

Automated workflow built with n8n that fetches data from a REST API and sends dynamic emails using Gmail OAuth2.

## Tech Stack
- Node.js
- n8n
- REST API
- Gmail API (OAuth2)

## Workflow
Manual Trigger → HTTP Request → Gmail (Send Message)

## What it does
- Fetches a JSON payload from an API
- Uses the response fields inside the email body dynamically
- Sends email automatically via Gmail OAuth2 integration
