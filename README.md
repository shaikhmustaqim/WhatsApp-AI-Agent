# WhatsApp-AI-Agent
AI-powered WhatsApp automation using n8n and ChakraHQ

# WhatsApp AI Agent Automation

## Project Overview
An AI-powered WhatsApp automation workflow built using n8n and ChakraHQ to process incoming messages and generate automated AI replies.

## Technologies Used
- n8n — Workflow automation
- ChakraHQ — WhatsApp integration
- AI Agent / LLM — Automated response generation
- Webhooks and HTTP Request nodes — Event handling and messaging

## Workflow
1. Receive an incoming WhatsApp message.
2. Validate the incoming message event.
3. Send the message to the AI Agent.
4. Generate an AI response.
5. Send the response back through WhatsApp.

## Setup
1. Import the sanitized workflow JSON into n8n.
2. Configure your own credentials and API connections.
3. Set the correct webhook URL.
4. Test with your own WhatsApp setup before activating the workflow.

## Security
Never commit API keys, access tokens, passwords, or private webhook URLs.

## Status
Project for learning and demonstrating AI-powered workflow automation.
