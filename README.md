# AI-Personal-Assistant-Multi-Agent-System-
An AI-powered multi-agent personal assistant built with n8n that manages Gmail, Google Calendar, Google Tasks, and web research through a Telegram chat interface.
# AI Personal Assistant (Multi-Agent System)

## Overview

This project is an AI-powered multi-agent personal assistant built with n8n. It enables users to interact with multiple productivity services through a single Telegram chat interface using natural language. Instead of relying on one AI agent to perform every task, the system uses an orchestrator agent that understands the user's request and delegates it to the appropriate specialized agent.

The assistant can manage Gmail, Google Calendar, Google Tasks, and perform web research when external information is required. This modular architecture makes the system scalable, easier to maintain, and simple to extend with additional agents in the future.

## Features

* Multi-agent AI architecture
* AI orchestrator for intelligent task routing
* Telegram-based conversational interface
* Gmail integration for email management
* Google Calendar integration for scheduling and event management
* Google Tasks integration for task creation and management
* AI-powered web research
* Natural language command processing
* Workflow automation using n8n
* API-based integrations with Google Workspace services

## How It Works

A user sends a request through Telegram. The orchestrator agent analyzes the request, determines the user's intent, and routes it to the appropriate specialized agent. The selected agent executes the requested action, retrieves any necessary information from the connected service, and returns the result to the user through Telegram.

## Technologies Used

* n8n
* OpenAI/Gemini
* Telegram Bot API
* Gmail API
* Google Calendar API
* Google Tasks API
* REST APIs
* HTTP Requests
* JSON

## Example Commands

* Schedule a meeting with John tomorrow at 3 PM.
* Show me my meetings for today.
* Create a task to finish my GitHub portfolio.
* Summarize my unread emails.
* Research the latest AI automation trends.

## Repository Contents

* `workflow.json` – Complete n8n workflow.
* `screenshots/` – Images of the workflow and example executions.
* `README.md` – Project documentation.

## Future Improvements

* Voice command support
* WhatsApp integration
* Long-term memory
* Additional specialized agents
* Support for more productivity platforms

## About

This project was built as part of my AI automation portfolio to demonstrate the design and implementation of production-style multi-agent systems using n8n, AI models, APIs, and workflow automation. It showcases how multiple AI agents can collaborate to automate real-world productivity tasks through a single conversational interface.
