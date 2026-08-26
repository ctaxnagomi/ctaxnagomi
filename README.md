# CTECX — AI Agent Ecosystem

**CTECX** is an agentic workflow ecosystem connecting reasoning AI, tool orchestration, and browser automation for Malaysian businesses.

## Architecture

```
┌──────────────────────────────────────┐
│         Big Pickle (LLM)             │
│   Reasoning · Token Reduction · API  │
├──────────────────────────────────────┤
│      DGUI Ecosystem (Tools)          │
│  Coordinator · CaaS · Seeds · KPI   │
│  Matchmaking · Audit · Dashboard     │
├──────────────────────────────────────┤
│        CTAX-Ai (Runtime)             │
│   Browser · Terminal · MCP Bridge    │
└──────────────────────────────────────┘
```

## Tech Stack

| Layer | Stack |
|-------|-------|
| Big Pickle | OpenAI-compatible API, token reduction via CaaS |
| DGUI Ecosystem | Node.js, SQLite, SSE, Coordinator Hub |
| CTAX-Ai | neo / puppeteer / playwright modes |

## Live Infrastructure

| Service | URL |
|---------|-----|
| Main Site | `https://deckergui.my` |
| KPI UI | `https://app.deckergui.my` |
| Coordinator Hub | `https://hub.deckergui.my` |
| Agent Server | `https://agent.deckergui.my` |
| CORPUSLIB | `https://corpuslib-ui.deckergui.my` |
| CTECX Portal | `https://ctecx.deckergui.my` |

## Key Features

- **30+ agent skills** for specialized tasks
- **CORPUSLIB** — Agentic corpus library (34 topics, HUB/INSTRUCT layers)
- **Factory Missions** — Multi-agent PR review & task delegation
- **Cross-platform CLI** — Go-based `dgui` CLI (bubbletea TUI, 25 tools, 4 LLM providers)
- **Hugging Face** — 7 datasets, 11 models, 1 Space

## Programming Languages

| Language | Framework / Tool | Familiarity |
| --- | --- | --- |
| **HTML5** | Pug, Tailwind CSS | ⭐⭐⭐⭐ |
| **CSS3** | Tailwind CSS | ⭐⭐⭐⭐ |
| **JavaScript (ES6+)** | React.js, Express.js | ⭐⭐⭐⭐ |
| **Python** | Flask, FastAPI | ⭐⭐⭐⭐ |
| **Go** | Cobra CLI, Bubbletea TUI | ⭐⭐⭐ |
| **Node.js** | REST API, SQLite | ⭐⭐⭐⭐ |
| **AI / LLM** | Hugging Face, Ollama, OpenAI | ⭐⭐⭐⭐ |

## Projects

| Project | Description | Status |
| --- | --- | --- |
| **CTECX Ecosystem** | AI agent ecosystem — three-layer architecture for enterprise automation | In Production |
| **Lezy QRCode Map** | QR code & map system for local shops | Complete |
| **Login/Signup System** | Auth with OAuth2.0 via Supabase | Complete |
| **Dynamic GIF Card** | Interactive card with GIF + video autoplay | Complete |
| **E-Ticket System** | E-Ticket management with admin dashboard | Complete |
| **Sarawak Native LLM** | Language model for Sarawak native dialects | Fine-tuning |
| **Simpli Report API** | REST API for PDF/Docx/CSV reports | In Development |

## Sarawak Native Language LLM

Prototype for Sarawak native language using Hugging Face datasets, Ollama CLI, and OpenRouter cloud LLMs.

### Dataset Methods

1. English to Native
2. Malay to Native
3. (English/Malay) to Native (Audio Transcription, less than 7s)
4. 2-5s Audio + Context: transcript snippet paired with surrounding context

## Quantization Profiles (Local Inference)

| Device | Quant | RAM | Model Size |
| --- | --- | --- | --- |
| High-end | FP16 / GGUF Q8_0 | 32GB+ | 13B-70B |
| Mid-end | GGUF Q4_K_M | 16-32GB | 7B-13B |
| Low-end | GGUF Q3_K_M | 8-16GB | 3B-7B |

## Contact

ctaxnagomi@gmail.com

## Crypto Donations

| Currency | Address |
| --- | --- |
| BTC | bc1q65qjzvwyq2czumpy6tevtv2lgqvmvn3gh54ym7 |
| ETH | 0xd5d0AF6c78F4E203C5121740a747E92F0E4C9e5f |
| SOL | 7hphP53qK9CVZUs2atFSDxmW6zD2PM7zLgryeCSPj9iH |
| XRP | rUYHZ71yXAS54ZQNvvooLX7rFtZydXjnP |

<details><summary>BTC QR</summary><img src="./qrcode-btc.jpg" width="130"/></details>
<details><summary>ETH QR</summary><img src="./qrcode-eth.jpg" width="130"/></details>
<details><summary>SOL QR</summary><img src="./qrcode-solana.jpg" width="130"/></details>

## Local Support

| Platform | Link |
| --- | --- |
| Touch n Go | payment.tngdigital.com.my/sc/bDLnQhnx4s |

<details><summary>TNG QR</summary><img src="./qr-tng-standard.jpg" width="130"/><br><img src="./qr-tng-duitnow.jpg" width="130"/></details>
