# TeamRAG — Multi-Platform RAG Bot for Slack, Discord & WhatsApp

> Built by **Lakshman Rajith Rongala** | University of New Haven | [LinkedIn](https://www.linkedin.com/in/lakshmanrajith) | [Portfolio](https://www.artfolio.tech/lakshmanrongala)

---

## 🚀 Overview

**TeamRAG** is an open-source RAG-powered knowledge bot deployed simultaneously across **Slack, Discord, and WhatsApp**. It enables teams to query internal knowledge bases in natural language with context-aware, thread-level responses. Built with agentic RAG mode and vector similarity search for intelligent multi-turn conversations.

---

## ✨ Features

- 💬 **Multi-Platform Deployment** — Runs on Slack, Discord, and WhatsApp simultaneously
- 🧠 **Agentic RAG Mode** — Vector similarity search over indexed knowledge corpora
- 🧵 **Thread-Level Context** — Stores message and thread IDs for multi-turn conversations
- 🔍 **Vectara Integration** — Enterprise-grade RAG with semantic search
- 🐳 **Dockerized** — Zero-downtime multi-platform deployment with Docker

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| RAG Engine | Vectara, FAISS |
| Platforms | Slack API, Discord API, Twilio (WhatsApp) |
| Database | Redis (session storage) |
| Infrastructure | Docker |

---

## 📁 Project Structure

```
teamrag/
├── main.py              # Entry point
├── slack_bot.py         # Slack integration
├── discord_bot.py       # Discord integration
├── whatsapp_bot.py      # WhatsApp integration
├── query_vectara.py     # RAG query engine
├── db.py                # Database handler
├── redis_client.py      # Session management
├── utils.py             # Shared utilities
├── Dockerfile
└── requirements.txt
```

---

## ⚙️ Setup & Installation

```bash
# Clone the repo
git clone https://github.com/rajith1612/teamrag.git
cd teamrag

# Install dependencies
pip install -r requirements.txt

# Set your API keys
cp .env.example .env
# Edit .env with Vectara, Slack, Discord, Twilio keys

# Run with Docker
docker build -t teamrag .
docker run teamrag

# Or run directly
python main.py
```

---

## 🎯 Use Cases

- Query internal documentation in natural language
- Get instant answers in Slack/Discord channels
- Share knowledge base across communication platforms
- Enable context-aware multi-turn conversations for teams

---

## 📬 Contact

**Lakshman Rajith Rongala**
- Email: lakshmanrajith777@gmail.com
- LinkedIn: [linkedin.com/in/lakshmanrajith](https://www.linkedin.com/in/lakshmanrajith)
- Portfolio: [artfolio.tech/lakshmanrongala](https://www.artfolio.tech/lakshmanrongala)
- GitHub: [github.com/rajith1612](https://github.com/rajith1612)
