# Website-RAG-Agent
Website RAG Agent is an advanced AI-powered chatbot connected to your website that provides accurate, document-based answers using retrieval-augmented generation (RAG) technology. It combines real-time data retrieval with smart language understanding, maintain chat history, and even connect users to human support when needed.

Website RAG Agent is an intelligent, document-aware chatbot powered by **Retrieval-Augmented Generation (RAG)**.  
It’s designed to give **accurate, real-time, and hallucination-free answers** by retrieving data directly from your uploaded documents.  

This project brings together **Supabase**, **Gemini Embedding Model**, and **Google Gemini Model** to deliver a powerful, context-aware chatbot for any website or platform.  

---

## 🚀 Overview  

Website RAG Agent processes your documents, stores them as vector embeddings, and responds to user queries with precise and contextually relevant answers.  
It also includes a **safe chat history system**, allowing seamless handover between AI and human agents whenever needed.  

---

## ⚙️ Workflow  

1. **Download File Node** – Downloads and processes files.  
2. **Document Loader** – Loads documents for embedding.  
3. **Gemini Embedding Model** – Converts content into vector embeddings.  
4. **Supabase Vector Store** – Stores the embeddings securely for retrieval.  
5. **RAG Agent (Webhook Connection)** – Receives user queries from the website.  
6. **Trigger Node** – Captures and vectorizes user queries.  
7. **Google Gemini Model** – Refines and enhances the generated response.  
8. **Postgres Chat Memory** – Keeps track of context for smooth conversations.  
9. **If Node** – Detects when a user requests human help.  
10. **Safe Chat History** – Saves complete chat logs per session ID.  
11. **Gmail Integration** – Sends an email with the subject *“Immediate Attention Required”* containing the full chat history for support agents.  

---

## 🌟 Features  

- 💬 **Accurate & Contextual Responses** – Retrieves exact answers from your uploaded documents.  
- 🧠 **No Hallucinations** – Responses are fact-based and reliable.  
- 🗂 **Postgres Chat Memory** – Maintains session flow and memory for better interactions.  
- 🧾 **Safe Chat History** – Saves and forwards all chat logs for human review.  
- 🤝 **Human Support Integration** – Seamless switch from AI to human when needed.  
- ⚡ **Customizable** – Easily adaptable for multiple use cases and industries.  
- 🔐 **Secure Data Handling** – Ensures user queries and chat histories remain private.  

---

## 🧩 Tech Stack  

- **Supabase Vector Store**  
- **Google Gemini Model**  
- **Gemini Embedding Model**  
- **Postgres Database**  
- **Gmail API (for chat forwarding)**  
- **Webhook Integration**  
