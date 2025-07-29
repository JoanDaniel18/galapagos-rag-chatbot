# Galápagos RAG Chatbot 🐢🤖

> Automating a RAG-based Telegram chatbot with n8n and AWS

This project demonstrates how to deploy an end-to-end **Retrieval-Augmented Generation (RAG)** chatbot to answer user questions about **Galápagos migratory procedures**. Built with **n8n**, deployed using **Docker** on an **AWS EC2** instance, and integrated with **Telegram**, it provides fast, semantic responses using **Cohere embeddings** and **Gemini LLM**.

---

## ✨ Features

- 📄 Parses PDF files from Dropbox
- 📌 Chunks and embeds content using Cohere
- 🧠 Queries vector database (Supabase + pgvector)
- 💬 Responds on Telegram via n8n workflow
- ☁️ Fully deployed with Docker on AWS EC2
- 🔒 HTTPS secured with Nginx and Certbot

---

## 📚 Architecture

![Architecture Diagram](architecture/architecture-diagram.png)

---

## 🚀 Getting Started

### Prerequisites
- AWS EC2 instance (Amazon Linux)
- Docker & Docker Compose
- Domain name for HTTPS (via Nginx + Certbot)
- Telegram Bot Token
- Supabase project + `pgvector` enabled
- Dropbox API token

### Setup

```bash
# Clone the repo
git clone https://github.com/tuusuario/galapagos-rag-chatbot.git
cd galapagos-rag-chatbot

# Setup Docker (inside your EC2)
cd docker
docker-compose up -d
