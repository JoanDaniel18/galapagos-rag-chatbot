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


![imagen_2 (1)](https://github.com/user-attachments/assets/9987d635-ca7e-43dc-81e1-1bda3785a4d3)
![imagen_1 (1)](https://github.com/user-attachments/assets/c8448d41-6295-4dc1-9026-97facad0048f)
![imagen_4 (1)](https://github.com/user-attachments/assets/59bc7430-f435-47be-a1f8-f07bc52fab1d)
<img width="1357" height="525" alt="imagenes_3 (1)" src="https://github.com/user-attachments/assets/cb004ae3-982a-462e-9563-715725d10735" />



---

## 🚀 Getting Started

### Prerequisites
- AWS EC2 instance (Amazon Linux)
- Docker & Docker Compose
- Domain name for HTTPS (via Nginx + Certbot)
- Telegram Bot Token
- Supabase project + `pgvector` enabled
- Dropbox API token

