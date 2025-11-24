📁 Workflow 1: Smart FAQ Document Chatbot with RAG
🌟 Overview

An AI-powered Telegram chatbot that processes documents and provides intelligent, context-aware answers using Retrieval-Augmented Generation (RAG). Perfect for creating instant, accurate document-based support systems.
✨ Features

    📄 Automated Document Processing - Ingests and splits uploaded documents for AI learning

    🔍 Retrieval-Augmented Generation (RAG) - Finds relevant information from documents to answer questions

    🤖 AI-Powered Q&A - Uses Google Gemini for intelligent, human-like responses

    📱 Telegram Integration - Complete chatbot experience within Telegram

    💾 Vector-Based Memory - Stores document knowledge in Pinecone for fast retrieval

🛠️ Installation & Setup
Prerequisites

    n8n instance (local or cloud)

    Telegram Bot Token

    Pinecone API Key

    Google Gemini API Key

Quick Start

    Import Workflow
    bash # In n8n dashboard:
    # Create new workflow → Import from File → Select workflow.json

# In n8n dashboard:
# Create new workflow → Import from File → Select workflow.json

    Configure Credentials

        Telegram Bot API Token - For Telegram Trigger and Get a file nodes

        Pinecone API Key - For Pinecone Vector Store nodes

        Google Gemini API Key - For Embeddings and Chat Model nodes

    Activate the workflow

🔧 Technical Details

Tools Used:

    🚀 n8n (Workflow Automation)


📧 Workflow 2: AI-Powered Customer Support Email Automation
🌟 Overview

Automatically processes incoming Gmail messages, classifies support requests, and generates instant, accurate responses using your knowledge base. Reduces response time from hours to seconds.
✨ Features

    📧 Smart Email Classification - Identifies customer support vs. other emails

    🤖 AI Response Generation - Creates friendly, context-aware replies

    📚 Knowledge Base Integration - Searches FAQ database for accurate information

    ⚡ Automatic Email Replies - Sends instant responses to customer inquiries

    🎯 Intelligent Filtering - Processes only genuine support requests

🛠️ Installation & Setup
Prerequisites

    n8n instance

    Gmail OAuth2 credentials

    Google Gemini API Key

    Pinecone API Key

Quick Start

    Import Workflow
    bash # Create new workflow → Import from File → Select workflow.json

# Create new workflow → Import from File → Select workflow.json

    Configure Credentials

        Gmail OAuth2 - For reading and replying to emails

        Google Gemini API - For AI classification and responses

        Pinecone API - For knowledge base access

    Activate the workflow

🔄 How It Works
Step-by-Step Process:

    📥 Email Trigger

        Constantly monitors Gmail inbox

        Passes new emails to classification system

    🤖 Smart Classification

        AI analyzes email content

        Routes "Customer Support" emails to AI Agent

        Ignores "Other" emails (sent to No Operation)

    🧠 AI Response Generation

        Searches Pinecone knowledge base

        Generates friendly responses with emojis

        Signs as "Mr. Helpful from Mello Techy"

    📤 Automatic Reply

        Sends AI-generated response

        Maintains email thread context

        Provides 24/7 instant support

🔧 Technical Details

Tools Used:

    🚀 n8n (Workflow Automation)

    🧠 Google Gemini (AI Classification & Chat)

    🗄️ Pinecone (Vector Database)

    📧 Gmail (Email Platform)

🎯 Key Benefits
For Both Workflows:

    ⚡ Instant Responses - Answers in seconds, not hours

    🎯 Accurate Information - Leverages your actual knowledge base

    👥 Consistent Quality - Maintains brand voice and guidelines

    🕒 24/7 Operation - Works around the clock

    📈 Scalable - Handles unlimited queries simultaneously

    🧠 Google Gemini (AI Embeddings & Chat)

    🗄️ Pinecone (Vector Database)

    💬 Telegram (Messaging Platform)
