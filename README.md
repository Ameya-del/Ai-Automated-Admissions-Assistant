# Ai-Automated-Admissions-Assistant
AI-powered automation system for university admissions — classifies and responds to inquiries via email and chat using GPT, n8n workflows, and a centralized knowledge base.That automates email triage, updates knowledge bases, and provides real-time chat support for applicants using GPT, n8n, Pinecone, and Supabase.
## Table of Contents
1. [Overview](#overview)
2. [Architecture](#architecture)
3. [Installation & Setup](#installation--setup)
4. [Usage](#usage)
5. [Technology Stack](#technology-stack)
6. [Features](#features)
7. [Future Improvements](#future-improvements)
8. [Contributors](#contributors)
9. [License](#license)
    
***[Overview]****
The AI Admissions Agent is a smart automation system designed to handle the overwhelming number of inquiries faced by university admissions offices.  
It classifies incoming emails, retrieves accurate information from a centralized knowledge base, and responds instantly via email or chat — reducing manual workload, improving accuracy, and enhancing applicant experience.

***[Architecture]***
The system is built on **three core pillars**:

1. **AI Triage Agent (Email Workflow)**  
   - Classifies incoming emails into over 20 intent categories  
   - Sends AI-generated replies for general queries or drafts for high-priority ones  
   - Logs all activity into Supabase for analytics  

2. **Automated Knowledge Pipeline (The Brain)**  
   - Monitors a Google Drive folder for updates  
   - Converts documents into vector embeddings using OpenAI models  
   - Stores embeddings in Pinecone for fast semantic search  

3. **Interactive AI Agent (Conversational Interface)**  
   - Real-time web chat interface for applicants  
   - Uses Retrieval-Augmented Generation (RAG) to provide precise answers  
   - Maintains conversation memory for natural dialogue

***[Installation & Setup]***
### Prerequisites
- Python 3.9+ or Node.js (depending on your implementation)
- n8n installed locally or deployed in the cloud
- Accounts & API keys for:
  - OpenAI
  - Pinecone
  - Supabase
  - Google Drive API
  - Gmail API

### Clone the Repository
```bash
git clone https://github.com/yourusername/ai-admissions-agent.git
cd ai-admissions-agent

***[Technology Stack]***
- **n8n** – Workflow automation & orchestration
- **OpenAI GPT-4o** – Language understanding & response generation
- **LangChain** – Agent orchestration & RAG implementation
- **Pinecone** – Vector database for semantic retrieval
- **Supabase** – Logging & analytics database
- **Google Drive API** – Document ingestion
- **Gmail API** – Email reading & sending

***[Features]***
--AI-powered Email Triage** – Classifies and responds to emails automatically
--Automated Knowledge Updates** – Keeps answers consistent & up-to-date
--Real-time Chat Support** – Web-based conversational interface
--Analytics & Logging** – Tracks inquiries and AI performance
--24/7 Availability** – Always online for applicants

***[Future Improvements]***
- Full unification of email and chat systems
- Advanced analytics dashboards for admin insights
- Multimodal input (voice, images, documents)
- Multilingual support for international applicants

***[Contributors]***
- **Ayush Kadam** 
- **Ameya Yadav**
- **Yash Choudhary**
- **Sanket Salve**

***[License]***
MIT License




