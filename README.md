1. Title : Smart FAQ Document Chatbot with RAG (n8n Workflow)
2. Description :
This n8n workflow creates an AI-powered Telegram chatbot that can answer questions from your documents. It automatically processes uploaded documents to learn their content and provides intelligent, context-aware answers. It eliminates manual information searching and provides instant, accurate support 24/7.
4. Features :

  Automated Document Processing: Ingests and splits uploaded documents for the AI to learn.

  Retrieval-Augmented Generation (RAG): Finds the most relevant information from your documents to answer user questions.

  AI-Powered Q&A: Uses Google Gemini to understand questions and generate human-like answers.

   Telegram Integration: Works entirely within the popular Telegram messenger app.

  Vector-Based Memory: Stores document knowledge in Pinecone for fast and accurate information retrieval.

4. Files Included :

    workflow.json → This is the exported n8n workflow file. It contains all the logic, node configurations, and connections. You can import this file directly into any n8n instance to recreate the entire automation.

5. How to Use It :

    Install n8n (locally or use a cloud instance).

    In your n8n dashboard, create a new workflow.

    Click the menu and select "Import from File".

    Select the provided workflow.json file.

    Set up the following credentials in n8n:

   Telegram Bot API Token (for the Telegram Trigger and Get a file nodes)

    Pinecone API Key (for the Pinecone Vector Store nodes)

   Google Gemini API Key (for the Embeddings and Chat Model nodes)

    Activate the workflow.

6. Tools Used :

    n8n (Workflow Automation Platform)

    Google Gemini (AI Embeddings & Chat Model)

    Pinecone (Vector Database for document memory)

    Telegram (User Interface & Trigger)






   1. Title

AI-Powered Customer Support Email Automation (n8n Workflow)
2. Description

This n8n workflow automatically reads incoming Gmail messages, classifies them as customer support requests, and uses AI to generate personalized responses based on your knowledge base. It reduces response time from hours to seconds and ensures consistent, accurate answers to common customer questions.
3. Features

    Smart Email Classification: Automatically identifies customer support emails vs. other messages

    AI-Powered Response Generation: Creates friendly, context-aware replies using Google Gemini

    Knowledge Base Integration: Searches your FAQ database in Pinecone for accurate information

    Automatic Email Replies: Sends instant responses to customer inquiries

    Intelligent Filtering: Only processes genuine support requests, ignores other emails

4. Files Included

    workflow.json → The complete n8n workflow export. This file contains all the automation logic and can be imported directly into any n8n instance to recreate the entire customer support system.

5. How to Use It

    Install n8n (locally or cloud version)

    Create a new workflow and click "Import from File"

    Select the provided workflow.json file

    Configure these credentials in n8n:

   Gmail OAuth2 (for reading and replying to emails)

    Google Gemini API (for AI classification and response generation)

    Pinecone API (for accessing your knowledge base/FAQ)

    Activate the workflow to start automating customer support

6. Tools Used

    n8n (Workflow Automation)

    Google Gemini (AI Classification & Chat)

    Pinecone (Vector Database for FAQ/Knowledge Base)

    Gmail (Email Trigger & Response)

Bonus: How This Workflow Works

Step-by-Step Process:

  Email Trigger

  Constantly checks your Gmail inbox for new messages
  Passes every new email to the classification system

  Smart Classification

  Uses AI to analyze each email content

  Determines if it's a "Customer Support" request or "Other"

  Customer Support emails → Go to AI Agent for response

  Other emails → Ignored (sent to "No Operation" node)

  AI Response Generation

  he AI Agent receives the customer's question

  Searches your Pinecone knowledge base for relevant FAQ information

  Generates a friendly, helpful response using emojis

  Signs off as "Mr. Helpful from Mello Techy"

    📤 Automatic Reply

        Sends the AI-generated response directly back to the customer

        Replies to the same email thread

        Customer gets instant, accurate support 24/7
