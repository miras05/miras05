### Hi, I'm Miras 👋

**AI Engineer · Full-Stack Engineer** based in Almaty, Kazakhstan. I build LLM systems that run in
production for real businesses: RAG assistants, document extraction, AI bots and integrations with
CRMs, ERPs and Google Workspace. 3+ years of commercial development. I own projects end to end —
from the brief and estimate to launch and support.

**AI:** LLM APIs (Claude, OpenAI, Gemini, Llama via Groq) · RAG (embeddings + BM25, RRF) · LLM evaluation · structured outputs
**Backend:** Python · FastAPI · Pydantic · PostgreSQL (pgvector) · SQLite · Node.js · Docker · GitHub Actions
**Frontend:** React · Next.js · TypeScript · Vite · Tauri
**Integrations:** Telegram Bot API · WhatsApp Cloud API · amoCRM / Bitrix24 REST · 1C:Enterprise ERP (OData, BSL) · Google APIs

---

#### 📌 Featured projects

| | Project | Highlights |
|---|---|---|
| ⚖️ | [**adal-kenesshi**](https://github.com/miras05/adal-kenesshi) | RAG assistant over Kazakhstan's 2026 Constitution and laws. Hybrid search (e5 + BM25 → RRF), refusal on low relevance instead of hallucination, `[n]` citations, RU/KZ, web + Telegram. **Eval on 47 questions: 98% pass, 100% refusal on trap questions**, 42 tests |
| 📄 | [**doc-recognition-1c**](https://github.com/miras05/doc-recognition-1c) | Invoice photo in Telegram → Gemini Vision → arithmetic validation → draft document in the ERP via OData. Mock ERP server on FastAPI, 21 tests |
| 💬 | [**whatsapp-booking-bot**](https://github.com/miras05/whatsapp-booking-bot) | WhatsApp booking bot that shares one phone number with the business owner (Coexistence). FastAPI, SQLite-backed queue, idempotent webhooks, retries with backoff, Docker, 24 tests |
| 🤖 | [**ai-leadbot-engine**](https://github.com/miras05/ai-leadbot-engine) | LLM bot that collects a lead in conversation and creates a deal in amoCRM. Niches via JSON configs, validated model output, 13 tests |
| 🗂 | [**branch-requests-hub**](https://github.com/miras05/branch-requests-hub) | Daily AI digest across 7 Telegram groups, email and Bitrix24; critical items become CRM tasks. PostgreSQL, integration tests in CI |
| 📊 | [**chat-audit**](https://github.com/miras05/chat-audit) | Audits customer chats and estimates hot leads and revenue lost to slow replies. Parsers, SLA, PII masking, HTML dashboard, zero dependencies |
| 💻 | [**max-web-chat**](https://github.com/miras05/max-web-chat) | Browser chat client for the MAX messenger via GREEN-API. React + TypeScript, long polling, delivery statuses, [live demo](https://miras05.github.io/max-web-chat/) |
| 🔐 | [**1c-google-sheets-jwt**](https://github.com/miras05/1c-google-sheets-jwt) | JWT RS256 signing written from scratch in the 1C language: SHA-256 and RSA on big-integer arithmetic, no OpenSSL. Runs in production as a nightly ERP → Google Sheets export |

Also: [**SyntaxCue**](https://syntaxcue.com) — my paid desktop app for interview prep (Tauri/Rust, local whisper.cpp, BYOK LLM).
Case studies of commercial projects with private code are in [**portfolio**](https://github.com/miras05/portfolio).

#### 🛠 What I do

- **RAG and AI assistants**: knowledge-base answers with citations, hybrid retrieval, refusal when unsure, measured with eval sets.
- **AI agents and chatbots**: WhatsApp, Telegram, web. Lead qualification, bookings, handoff to a human.
- **Document processing**: scans and PDFs → structured data by schema → validation → export into the accounting system.
- **Integrations**: CRMs (amoCRM, Bitrix24), ERPs (1C:Enterprise), Google Sheets, third-party REST APIs, webhooks.
- **Backend and deployment**: FastAPI, queues and retries, Docker / Compose, VPS, Fly.io, CI with GitHub Actions.
- **Web apps**: React / Next.js + TypeScript frontends, dashboards, desktop apps with Tauri.

📫 mirasauganbayev@gmail.com · [Telegram @miras_au](https://t.me/miras_au) · [LinkedIn](https://www.linkedin.com/in/miras-auganbayev-0a805a439) · Open to remote or relocation anywhere
