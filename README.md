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
    bash

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

    🧠 Google Gemini (AI Embeddings & Chat)

    🗄️ Pinecone (Vector Database)

    💬 Telegram (Messaging Platform)
