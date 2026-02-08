# Automation Workflow with n8n

Automated workflow built with n8n that fetches data from a REST API, generates dynamic email content using templates, and sends emails via Gmail OAuth2.

## Tech Stack
- Node.js
- n8n
- REST API
- Gmail API (OAuth2)

## Workflow
Manual Trigger → HTTP Request → Set (Dynamic Template) → Gmail (Send Message)

## Features
- API integration
- Dynamic email subject & body generation
- Secure Gmail OAuth2 authentication,
  
- ## Error Handling

- Includes basic error handling with IF branching.
- Sends a fallback error email when the API does not return valid data.

## How to Run (Local)

1. Install Node.js (LTS)
2. Install n8n globally:
   - npm install -g n8n
3. Start n8n:
   - n8n
4. Open n8n in the browser:
   - http://localhost:5678
5. Configure Gmail OAuth2 credentials.
6. Execute the workflow:
   - Manual Trigger → HTTP Request → Set → Gmail
