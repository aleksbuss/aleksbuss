# Aleksejs Buss
**AI Engineer — Multi-Agent Systems · Hof (Saale), Germany**
*Open to opportunities · EU citizen (Latvia)*

I build multi-agent LLM systems and production AI on edge infrastructure.
Creator of **[Orchestra](https://github.com/aleksbuss/orchestra)** — an open-source Mixture-of-Agents platform.
**Focus:** agent orchestration that's verified by code (not vibes), low-latency pipelines, and API cost transparency.

### 🎼 Flagship: Orchestra

[![Orchestra](https://img.shields.io/badge/aleksbuss%2Forchestra-MIT-blue?logo=github)](https://github.com/aleksbuss/orchestra)
![Tests](https://img.shields.io/badge/tests-2602-brightgreen)
![Post-mortems](https://img.shields.io/badge/post--mortems-74%20documented-purple)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-blue?logo=typescript)

Self-hosted AI workspace with a real **Mixture-of-Agents pipeline** — a team of specialised agents, not just one model:

- **3–5 parallel expert proposers** per substantive turn, personas generated dynamically per prompt
- **Code-guaranteed Skeptic** — an adversarial critic enforced by code, not by prompt (weak models drop prompt instructions silently)
- **Embedding-based disagreement detection** — expert conflict is surfaced in the answer, never smoothed away
- **Reflection loop** (Generator → Critic → Revisor) + live per-chat cost telemetry (tokens + USD)
- BYOK or fully local via Ollama · **2,602 tests** (Vitest + Playwright) · **74 documented post-mortems** · CI

`TypeScript (strict)` `Next.js 15` `Vitest` `Playwright` `Docker` `MIT`

---

### 🚀 More production systems

| Project | What it does | Stack | Link |
| :--- | :--- | :--- | :--- |
| **AI Dictaphone** | Real-time voice transcription Mini App — custom PCM encoder, streaming audio | Cloudflare Workers, Groq Whisper, Web Audio API | [🟢 Live Bot](https://t.me/trancribatorv2_bot) |
| **Bez Paniki** | AI psychology support app — panic intervention, CBT exercises, sleep tracker | Gemini AI, Firebase, Cloudflare Workers, TTS | [🟢 Live Bot](https://t.me/aipanic_bot) |
| **AI Moderation Bot** | Intelligent Telegram group moderation with escalating violations | OpenRouter, Gemini, n8n, async SQLite | [🔒 Case study](https://aleksejs-portfolio.pages.dev/#projects) |
| **Termux Voice AI** | Fully local speech AI on Android — STT + TTS, no internet required | whisper.cpp, Piper TTS, Python | [📂 Source Code](https://github.com/aleksbuss/Termux-SelfHosted-STT---TTS) |
| **Text Vault** | Self-hosted text storage on Android via Termux — zero cloud dependency | FastAPI, async SQLite, Cloudflare Tunnels | [📂 Source Code](https://github.com/aleksbuss/Termux-Text-Vault) |

---

### 🛠 Core Competencies

**Agent Systems & LLM Engineering**
Mixture-of-Agents (MoA) orchestration · Dynamic persona generation · Disagreement detection (embeddings) · Reflection loops · Multi-model orchestration (GPT-4, Gemini 2.5, Groq, Ollama, OpenRouter) · Prompt & context engineering · JSON-structured outputs · **Cost & latency optimization across providers**

**Languages & Frameworks**
TypeScript (strict) · Next.js 15 / React · JavaScript (ES Modules, async, Web Audio API) · Python (FastAPI, async) · Bash · Telegram Bot API & Mini Apps

**Engineering Culture**
2,600+ automated tests in the flagship (Vitest + Playwright E2E) · GitHub Actions CI · Post-mortem-driven development (74 documented) · SSRF / path-traversal guards · Sandbox constraints

**Edge & Serverless**
Cloudflare Workers (production) · On-device AI via Termux/Android (whisper.cpp, Piper TTS, Ollama) · Cloudflare Tunnels · Firebase · VPS/Linux (systemd, Nginx, Docker)

**Automation & Workflows**
n8n (AI Agents, Webhooks, multi-step workflows) · CI/CD · AI-assisted development (Claude Code) · FFmpeg audio/video pipelines

**🎵 Audio Engineering — 20+ years**
Cubase · FL Studio · Professional audio interfaces · Signal processing fundamentals. *This background gives me a real edge in AI audio pipelines, Web Audio API streaming, and STT/TTS integrations.*

---

### 💡 What sets me apart

**I architect agent systems, not just call APIs.**
Most "AI apps" wrap a single LLM. Orchestra runs a panel of specialised experts with a critic that is guaranteed by code, measures their disagreement, and tells you exactly what every answer cost. The same engineering applies to everything I ship: failure modes designed up front, behaviour verified by tests, incidents documented in post-mortems.

**Hustle & Drive.**
Career path: Truck driver → Self-taught AI & Web Developer → 8 production systems shipped solo since 2025. I know how to learn fast, solve hard problems independently, and deliver working products.

I stay current with AI industry developments daily — new model releases, API changes, and emerging patterns in agent architectures and MCP integrations.

---

### 🔭 Currently exploring
`MCP (Model Context Protocol)` `Agent evals & benchmarks` `Claude Code / Agent SDK` `Local LLM optimization` `RadixAttention / prefix caching`

---

📫 **Get in touch:** aleksbuss@gmail.com · [GitHub](https://github.com/aleksbuss)
📄 **[Lebenslauf / CV (DE)](./aleksbussCV.pdf)** · 📄 [CV (EN)](https://aleksejs-portfolio.pages.dev/CV-EN.html) · 🌐 **[Portfolio](https://aleksejs-portfolio.pages.dev/)**
