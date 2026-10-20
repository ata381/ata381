## Hey, I'm Ata 👋

AI Engineer based in Tilburg, the Netherlands, and founder of [Generative Studio](https://generative-studio.nl/), an independent software and design studio. BSc in Cognitive Science & AI from Tilburg University.

I build things before anyone asks me to — RAG pipelines, LLM integrations, automated workflows, developer tools. Through the studio I take on product development, design systems, and technical consulting.

### What I've been building

🔍 **RAG Chatbot** — End-to-end retrieval system over ~377 scraped pages, built across two
iterations: a FAISS proof-of-concept, then a production rebuild on Qdrant with a curated
multilingual knowledge base, unified retrieval (vector + keyword + temporal + location-aware
ranking), and a policy-document labeling pipeline. 97% accuracy across 261 benchmark tests.
FastAPI backend, React widget embeddable via a single `<script>` tag, widget-key auth +
rate limiting, swappable LLM providers (OpenAI, Anthropic, Azure, Ollama). Containerised with Docker.

📰 **Municipality Policy Monitor** — Policy-intelligence platform that polls Dutch government
publications via the SRU protocol, scores them by semantic relevance (OpenAI embeddings, 0.38
cosine threshold) and labels them with GPT-4o, stored in Qdrant. Adds a three-stage Land Market
Intelligence funnel (housing demand → site feasibility → policy alignment) over PRIMOS/CBS/PDOK
data, TenderNed tender tracking, and a RAG Q&A endpoint (GPT-4.1). Dual-tab React SPA with a
D3 municipality map. FastAPI + Docker Compose.

🧭 **ApplyPilot** — A privacy-first Chrome extension (Manifest V3) that drafts job applications
locally. From the side panel you capture a job description, and a local FastAPI + LLM service
generates a tailored cover letter, screening-question answers, and a CV PDF — all grounded in
your own résumé corpus, kept on your machine. No scraping, no auto-submit: you review and paste.
Multi-provider LLM support (OpenAI / Anthropic / Google / Ollama). Inspired by
[eracle/OpenOutreach](https://github.com/eracle/OpenOutreach).

📧 **AI Email Triage** — Outlook add-in that classifies an inbox as ACTION / INFO / LOW in one
click. Full auth pipeline (Office SSO → Cloudflare Worker → Microsoft Graph API → GPT-4o-mini).
Replaced an Azure backend with a single Cloudflare Worker — near-zero infrastructure cost.

💡 **Founder Idea Analyzer** — Startup evaluation workbench where founders submit an idea and get
LLM-backed scoring plus a generated Lean Canvas. Tracks revisions over time so mentors can compare
snapshots and measure learning velocity. Node.js + Express, MongoDB, Ollama. [→ repo](https://github.com/ata381/founder-idea-analyzer)

### Tech I work with

`Python` `TypeScript` `JavaScript` `FastAPI` `Node.js` `SQL` `Docker` `FAISS` `Qdrant` `ChromaDB` `LangChain` `OpenAI API` `Anthropic API` `Gemini API` `Azure OpenAI` `Ollama` `n8n` `Git` `PyTorch` `React`
📫 **ataa2000@hotmail.com** · [LinkedIn](https://linkedin.com/in/ataakıllıoğlu) · [Generative Studio](https://generative-studio.nl/) · [Studio on LinkedIn](https://www.linkedin.com/company/generativestudio/)
