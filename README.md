<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:6366f1&height=190&section=header&text=Maddali%20Suhas%20Choudary&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=I%20build%20agentic%20AI%20systems%20%E2%80%94%20and%20measure%20them%20honestly&descSize=16&descAlignY=58" alt="header" width="100%" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1200&color=6366F1&center=true&vCenter=true&width=640&lines=Final-year+CSE+%40+IIIT+Senapati%2C+Manipur;Agent+guardrails+%C2%B7+LangGraph+%C2%B7+MCP;Full-stack+products+that+actually+ship;Every+metric+comes+with+its+caveats)](https://github.com/Suhas-123-cell)

[![Portfolio](https://img.shields.io/badge/Portfolio-6366f1?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-eight-green-l7jbjfvx8g.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suhas-choudhary)
[![Email](https://img.shields.io/badge/Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:suhaschowdary25@gmail.com)

</div>

---

## About

I'm a final-year Computer Science student who likes the unglamorous half of AI engineering: **making agents safe, bounded and measurable**. My projects ship with test suites, CI, offline demos, and a *limitations* section — because a number without its caveats isn't evidence.

- Currently working on **guardrails for AI agents** that call real tools over MCP
- Comfortable end to end: ML/evals → Python APIs → web and mobile front-ends → Docker + CI
- Looking for **AI / ML engineering and full-stack roles** — open to internships and full-time

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [IntentShield](https://github.com/Suhas-123-cell/IntentShield)
Offline-first guardrail that sits between an AI agent and its MCP tools. Every proposed call is normalised, policy-checked, audited, and answered **ALLOW / REVIEW / BLOCK** before any side effect.

**Result, on 220 held-out MSB cases (qwen2.5:7b):** harmful actions executed fell from **58.5% → 0.0%**. The repo is upfront that a hold-everything baseline also hits 0.0%, so it reports what IntentShield does *differently* (no harmful call reaches the review queue) and what it costs (9–14 pts task completion).

`Python` `MCP` `Policy engine` `uv`

</td>
<td width="50%" valign="top">

### [FabGuard AI](https://github.com/Suhas-123-cell/FabGuard-AI)
Bearing-fault detection from vibration + audio. A small local detector flags abnormal windows; a **bounded LangGraph agent** (≤2 retrievals, ≤2 LLM calls) drafts a cited inspection report that **only an authenticated human can approve**.

**Result: 0.955 ± 0.079** balanced accuracy (fusion Isolation Forest, leave-one-bearing-out over 15 held-out bearings), with the weaker cross-rig transfer reported too.

`Python` `LangGraph` `FastAPI` `scikit-learn`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AutoReply](https://github.com/Suhas-123-cell/AutoReply)
Comment-to-DM automation for Instagram and Telegram with a native **React Native operator app**. Per-account rate limiting keeps it under Meta's documented 750 private replies/hour cap. CI runs typecheck, lint, tests and build.

`Next.js 16` `React Native` `Prisma` `BullMQ` `Redis` `PostgreSQL`

</td>
<td width="50%" valign="top">

### [Text-to-SQL on a laptop](https://github.com/Suhas-123-cell/sql-generation)
QLoRA-style fine-tune of Qwen2.5-1.5B (4-bit) trained locally on an Apple M5 with MLX; base vs fine-tuned compared on 200 held-out examples under identical decoding.

`MLX` `LoRA` `Python`

</td>
</tr>
</table>

### More work

| Project | What it is | Stack |
|---|---|---|
| [**Purplle Store Intelligence**](https://github.com/Suhas-123-cell/purplle) | CCTV analytics for a retail store: visitor detection, zone dwell, POS correlation, live dashboard | YOLOv8 · FastAPI · SQLite · Docker |
| [**Indic Benchmark Suite**](https://github.com/Suhas-123-cell/lang-benchmark) | Sarvam-2B vs Gemma-2B on Hindi / Bengali / Tamil reading, math and code-mixed QA, run locally on MPS | PyTorch · HF |
| [**Multilingual Document Intelligence**](https://github.com/Suhas-123-cell/Multi-lingual-document-intelligence-) | Structured extraction from scanned Indian govt. records in regional scripts, with a field-accuracy / CER harness | Sarvam Vision · Tesseract · Gradio |
| [**Remote Terminal**](https://github.com/Suhas-123-cell/Terminal-control) | Phone app that becomes a full remote terminal + screen for your laptop | Node · WebSocket · PTY · RN |

---

## Tech stack

| Area | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4eaa25?style=flat-square&logo=gnubash&logoColor=white) |
| **ML and evaluation** | ![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-ffd21e?style=flat-square&logo=huggingface&logoColor=black) ![PEFT / LoRA](https://img.shields.io/badge/PEFT_/_LoRA-6366f1?style=flat-square) ![MLX](https://img.shields.io/badge/MLX-000000?style=flat-square&logo=apple&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-f7931e?style=flat-square&logo=scikitlearn&logoColor=white) ![YOLOv8](https://img.shields.io/badge/YOLOv8-00ffff?style=flat-square) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) |
| **Agents and LLM apps** | ![LangGraph](https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square&logo=langchain&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-6366f1?style=flat-square) ![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8e75b2?style=flat-square&logo=googlegemini&logoColor=white) ![Prompt and eval harnesses](https://img.shields.io/badge/Prompt_and_eval_harnesses-0f172a?style=flat-square) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Next.js API routes](https://img.shields.io/badge/Next.js_API_routes-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2d3748?style=flat-square&logo=prisma&logoColor=white) ![BullMQ](https://img.shields.io/badge/BullMQ-dc382d?style=flat-square) ![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square) ![Pydantic](https://img.shields.io/badge/Pydantic-e92063?style=flat-square&logo=pydantic&logoColor=white) |
| **Frontend and mobile** | ![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61dafb) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-20232a?style=flat-square&logo=react&logoColor=61dafb) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06b6d4?style=flat-square&logo=tailwindcss&logoColor=white) ![Gradio](https://img.shields.io/badge/Gradio-f97316?style=flat-square&logo=gradio&logoColor=white) |
| **Data stores** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-dc382d?style=flat-square&logo=redis&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003b57?style=flat-square&logo=sqlite&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ecf8e?style=flat-square&logo=supabase&logoColor=white) |
| **DevOps and quality** | ![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![uv](https://img.shields.io/badge/uv-de5fe9?style=flat-square&logo=uv&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0a9edc?style=flat-square&logo=pytest&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6e9f18?style=flat-square&logo=vitest&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-c21325?style=flat-square&logo=jest&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4b32c3?style=flat-square&logo=eslint&logoColor=white) |

---

## GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Suhas-123-cell&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f172a" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Suhas-123-cell&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f172a" alt="top languages" />

</div>

---

<div align="center">

*If you're hiring for AI / ML or full-stack work, I'd love to talk — [suhaschowdary25@gmail.com](mailto:suhaschowdary25@gmail.com)*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:0f172a&height=100&section=footer" width="100%" alt="footer" />

</div>
