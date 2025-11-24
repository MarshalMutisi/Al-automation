1. Title : Smart FAQ Document Chatbot with RAG (n8n Workflow)
2. Description
This n8n workflow creates an AI-powered Telegram chatbot that can answer questions from your documents. It automatically processes uploaded documents to learn their content and provides intelligent, context-aware answers. It eliminates manual information searching and provides instant, accurate support 24/7.
3. Features

  Automated Document Processing: Ingests and splits uploaded documents for the AI to learn.

  Retrieval-Augmented Generation (RAG): Finds the most relevant information from your documents to answer user questions.

  AI-Powered Q&A: Uses Google Gemini to understand questions and generate human-like answers.

   Telegram Integration: Works entirely within the popular Telegram messenger app.

  Vector-Based Memory: Stores document knowledge in Pinecone for fast and accurate information retrieval.

4. Files Included

    workflow.json → This is the exported n8n workflow file. It contains all the logic, node configurations, and connections. You can import this file directly into any n8n instance to recreate the entire automation.

5. How to Use It

    Install n8n (locally or use a cloud instance).

    In your n8n dashboard, create a new workflow.

    Click the menu and select "Import from File".

    Select the provided workflow.json file.

    Set up the following credentials in n8n:

   Telegram Bot API Token (for the Telegram Trigger and Get a file nodes)

    Pinecone API Key (for the Pinecone Vector Store nodes)

   Google Gemini API Key (for the Embeddings and Chat Model nodes)

    Activate the workflow.

6. Tools Used

    n8n (Workflow Automation Platform)

    Google Gemini (AI Embeddings & Chat Model)

    Pinecone (Vector Database for document memory)

    Telegram (User Interface & Trigger)
