
# 🥛 The White Gold Agent
### AI-Powered Milk & Dairy Products Assistant

## Project Overview
The White Gold Agent is an AI-powered conversational assistant
built using n8n and OpenAI.

It helps users interact with milk and dairy product information,
check prices, manage inventory, and place orders through a
conversational AI interface.

## Technologies Used
- n8n – Workflow Automation
- OpenAI – AI Agent and Language Model
- RAG – Product Information Retrieval
- Simple Memory – Conversation Context
- HTTP/API Integration – External Data Access

## Key Features
1. AI-powered conversational assistant
2. Product price retrieval using RAG
3. Inventory checking
4. Inventory update
5. Order management
6. Conversational memory
7. Automated workflow execution

## Workflow Architecture

Chat Trigger
     ↓
   AI Agent
     ↓
 OpenAI Chat Model
     ↓
 Simple Memory
     ↓
 Connected Tools
     ├── Update Inventory
     ├── Add Order
     ├── Get Inventory
     └── Get Prices from RAG

## Project Structure

white-gold-ai-agent/
├── workflows/
├── screenshots/
├── documents/
├── sample-data/
├── README.md
├── .gitignore
└── LICENSE

## Setup Instructions
1. Install or access n8n.
2. Import the workflow JSON file.
3. Configure OpenAI credentials.
4. Configure the required inventory and order tools.
5. Connect the RAG data source.
6. Test the workflow using chat messages.

## Example Queries
- What is the price of milk?
- What is the price of ghee?
- Check available inventory.
- Update product inventory.
- Place a new order.

## Security
Never expose API keys, credentials, or real customer information.

## Disclaimer
This is a portfolio demonstration project.
Use sample data for testing.

## Author
Manish Verma
AI Engineer Aspirant
