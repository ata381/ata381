## Hey, I'm Ata 👋

AI Developer based in the Netherlands. BSc in Cognitive Science & AI from Tilburg University.

I build things before anyone asks me to — RAG pipelines, LLM integrations, automated workflows, developer tools.

### What I've been building

🔍 **RAG Chatbot** — End-to-end retrieval system for a Dutch construction company. Scraped 377 pages, FAISS vector store, hybrid retrieval (vector + keyword + temporal fallback), 97% accuracy across 261 benchmark tests. FastAPI backend, React widget embeddable via a single `<script>` tag, swappable LLM providers (OpenAI, Anthropic, Azure, Ollama). Containerised with Docker. Liked the architecture enough to build a second, more advanced version.

📰 **Municipality Policy Monitor** — Automated system that polls Dutch government publications, filters by semantic relevance (OpenAI embeddings, 0.65 cosine threshold), stores in Qdrant, and serves a RAG Q&A endpoint via FastAPI + GPT-4.1. Dockerised with Docker Compose.

📧 **AI Email Triage** — Outlook add-in that classifies an inbox as ACTION / INFO / LOW in one click. Full auth pipeline (Office SSO → Cloudflare Worker → Microsoft Graph API → GPT-4o-mini). Replaced an Azure backend with a single Cloudflare Worker — near-zero infrastructure cost.

🎯 **DevMatch** — AI-powered job matching platform for developers. Connects GitHub + LinkedIn, builds a developer profile with strength scoring, generates tailored CVs per job listing with match scores, and tracks applications on a kanban board. Built in TypeScript with Gemini API integration. [→ repo](https://github.com/ata381/DevMatch)

💡 **Founder Idea Analyzer** — Startup evaluation workbench where founders submit an idea and get LLM-backed scoring plus a generated Lean Canvas. Tracks revisions over time so mentors can compare snapshots and measure learning velocity. Node.js + Express, MongoDB, Ollama. [→ repo](https://github.com/ata381/founder-idea-analyzer)

🍳 *A couple more things cooking* — a full-stack recipe app with AI, a workflow automation layer with n8n, and an education-tech integration. All in various stages of "works on my machine."

### Tech I work with

`Python` `TypeScript` `JavaScript` `FastAPI` `Node.js` `SQL` `Docker` `FAISS` `Qdrant` `ChromaDB` `LangChain` `OpenAI API` `Anthropic API` `Gemini API` `Azure OpenAI` `Ollama` `n8n` `Git` `PyTorch` `React`
📫 **ataa2000@hotmail.com** · [LinkedIn](https://linkedin.com/in/ataakıllıoğlu)
