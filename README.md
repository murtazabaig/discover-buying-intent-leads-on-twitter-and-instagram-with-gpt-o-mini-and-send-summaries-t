

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Discover buying-intent leads on Twitter and Instagram with GPT-4o-mini and send summaries to Slack and Notion

Advanced n8n automation for Discover buying-intent leads on Twitter and Instagram with GPT-4o-mini and send summaries to Slack and Notion.

## Overview
- Category: AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Automate B2B lead discovery from Reddit with AI intent scoring, LinkedIn matching, RocketReach enrichment, and Google Sheets loggingevery 3 hours.

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.chat`
- `@n8n/n8n-nodes-langchain.chatTrigger`
- `@n8n/n8n-nodes-langchain.lmChatAzureOpenAi`
- `@n8n/n8n-nodes-langchain.mcpClientTool`
- `@n8n/n8n-nodes-langchain.memoryBufferWindow`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `n8n-nodes-base.errorTrigger`
- `n8n-nodes-base.gmail`
- `n8n-nodes-base.notion`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.stickyNote`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.