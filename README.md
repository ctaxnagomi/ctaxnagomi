
<img src="./profile-pic-rikayuwilzam.webp" width="25%" align="right" />

## 👋 Hi, I’m Rikayu Wilzam (Wan Mohd Azizi)


💻 Fullstack Developer | AI Integrator | Open-Source Builder
🌏 Based in Sarawak, Malaysia
⚙️ Currently working on Sarawak Native Language LLM Prototype (via Ollama + Cloud)
🧠 Passionate about AI tools, web systems, and language model integration

---

⚙️ Current Work Environment

I’m currently developing a localized AI model for Sarawak’s native language using Hugging Face datasets, Ollama CLI, and OpenRouter cloud LLMs.
My workflow includes WSL Ubuntu with KDE Plasma and Codex CLI for rapid prototyping.
| Stack / Tool                   | Description                                                                                                                                                                                                                        |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🧠 **OpenAI Codex CLI**        | Core environment setup for code reasoning and AI workflow                                                                                                                                                                          |
| 💬 **Ollama CLI + Cloud**      | Prototype of Sarawak Native Language LLM                                                                                                                                                                                           |
| ☁️ **OpenRouter Cloud Models** | Multi-model selection without affecting local RAM: <br>• `deepseek-v3.1:671b-cloud` <br>• `gpt-oss:20b-cloud` <br>• `gpt-oss:120b-cloud` <br>• `kimi-k2:1t-cloud` <br>• `qwen3-coder:480b-cloud` <br>• `glm-4.6:cloud`             |
|| 🐧 **WSL Ubuntu + KDE Plasma** | Development base with UI customization                                                                                                                                                                                             |
|| ⚡ **Warp (Agent Mode)**       | Terminal + agentic development environment with project-scoped WARP.md, codebase indexing, and multi-file edits                                                                                                                    |
|| 🤗 **Hugging Face CLI**        | Fine-tuning datasets and LLM training pipeline                                                                                                                                                                                     |
|| 🧩 **Dataset Methods**         | 4 data types:<br>1️⃣ English → Native<br>2️⃣ Malay → Native<br>3️⃣ (English/Malay) → Native (Audio Transcription, ≤7s)<br>4️⃣ 2–5s Audio + Context: transcript snippet paired with surrounding context (speaker role, domain/topic, locale, intent, entities) to improve alignment efficiency in fine-tuning<br>Temperature-controlled by response style: Logic / Creativity / Analytic / Casual / Professional / Custom |

---


🔨 **Ongoing Projects**

*(Follows same format as sample {A} – included for completeness if needed; no ongoing listed in B-2, so omitted unless required.)*
Device Class,Recommended Quant,Typical VRAM/RAM,Example Use,Notes
High-end,FP16 / GGUF Q8_0 / Q5_K_M,≥32–64GB RAM or ≥16–24GB VRAM,13B–70B (quantized),Larger context (4k–32k); set num_ctx≈4096–8192; f16_kv=true
Mid-end,"GGUF Q4_K_M / Q5_K_M, GPTQ 4-bit",16–32GB RAM or 8–12GB VRAM,7B–13B,Balance perf/quality; num_ctx≈2048–4096
Low-end,"GGUF Q3_K_M / Q4_0, AWQ/GPTQ 4-bit",8–16GB RAM or iGPU,3B–7B,Keep num_ctx≈1024–2048; prefer smaller vocab/rank

💡 Programming Language Proficiency

| Language                        | Framework / Tool               | Familiarity |
| ------------------------------- | ------------------------------ | ----------- |
| **HTML5**                       | Pug, Tailwind CSS, Live Server | ⭐⭐⭐⭐        |
| **CSS3**                        | Tailwind CSS                   | ⭐⭐⭐⭐        |
| **JavaScript (ES6+)**           | React.js, Express.js           | ⭐⭐⭐⭐        |
| **Python**                      | Flask                          | ⭐⭐⭐⭐        |
| **PHP**                         | Miniconda Local Env            | ⭐⭐⭐         |
| **Node.js**                     | REST API, JSON                 | ⭐⭐⭐⭐        |
| **YAML / JSON**                 | Config & API integration       | ⭐⭐⭐⭐        |
| **AI / LLM Prompt Engineering** | Hugging Face, Ollama, OpenAI   | ⭐⭐⭐⭐        |

┌─────────────────────────────────────┐
│ Rikayu's WakaTime Stats             │
├─────────────────────────────────────┤
│ Python   ████████  42%   15h 30m    │
│ JavaScript ██████  28%   10h 12m    │
│ HTML/CSS ████  18%    6h 45m        │
│ Others   ██   12%    4h 18m         │
└─────────────────────────────────────┘

Consistent workflow across full-stack development and AI integration. **Familiarity are based with tacit on hand durong "main-project & side- project developmet"**

💻 IDE & Extensions

| Tool            | Badge / Icon                                                                                               | Description                                      |
| --------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| **VS Code**     | ![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat\&logo=visual-studio-code\&logoColor=white) | Main code editor for full-stack + AI development |
| **GitHub**      | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat\&logo=github\&logoColor=white)             | Repository hosting & version control             |
| **Git Bash**    | 🌿                                                                                                         | Command-line shell for Git operations            |
| **Git Graph**   | 📊                                                                                                         | Visual commit and branch management              |
| **Kilocode**    | 🔧                                                                                                         | AI-assisted coding workspace                     |
| **Live Server** | 🔴                                                                                                         | Real-time frontend testing environment           |


🌐 Browsers
| Browser        | Icon | Use Case                                                |
| -------------- | ---- | ------------------------------------------------------- |
| **Perplexity** | 🔍   | AI-assisted research & analysis                         |
| **Chrome**     | 🌐   | Primary development browser                             |
| **Opera GX**   | 🎮   | Secondary test environment for performance benchmarking |

🖥️ Operating Systems

| OS                           | Badge / Icon                                                                                      | Role                                            |
| ---------------------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| **Windows**                  | ![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat\&logo=windows\&logoColor=white) | Core desktop environment                        |
| **Linux (KDE Plasma / WSL)** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat\&logo=linux\&logoColor=black)       | Native development + AI fine-tuning environment |

🧮 **Quantization Profiles (local inference)**

| Device Class | Recommended Quant              | Typical VRAM/RAM      | Example Use       | Notes                                           |
| ------------ | ------------------------------ | --------------------- | ----------------- | ----------------------------------------------- |
| High-end     | FP16 / GGUF Q8_0 / Q5_K_M      | ≥32–64GB RAM or ≥16–24GB VRAM | 13B–70B (quantized) | Larger context (4k–32k); set num_ctx≈4096–8192; f16_kv=true |
| Mid-end      | GGUF Q4_K_M / Q5_K_M, GPTQ 4-bit | 16–32GB RAM or 8–12GB VRAM | 7B–13B            | Balance perf/quality; num_ctx≈2048–4096         |
| Low-end      | GGUF Q3_K_M / Q4_0, AWQ/GPTQ 4-bit | 8–16GB RAM or iGPU   | 3B–7B             | Keep num_ctx≈1024–2048; prefer smaller vocab/rank |

---

🚀 **Projects Overview**

| Project                                         | Description                                                                                       | Stack / Tools                                      | Integration & Features                                                                 | Status     |
| ----------------------------------------------- | ------------------------------------------------------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------------------------------------------- | ---------- |
| 🎚️ **Colorblind Mode Toggle**                  | Accessible Light/Dark/Colorblind theme toggle for web and WordPress with colorblind subtypes and keyboard support; persists via localStorage. | HTML, CSS, JavaScript, WordPress                   | Classes: theme-light, theme-dark, theme-cb, cb-* · Persistence: a11y.theme, a11y.cbType · Demo: web/index.html | ✔️ Complete |
| 🗺️ **Lezy QRCode Map Generator**               | Full-stack QR code & map generation system specialized for small, home-based, and local shops. Designed for businesses seeking a self-managed delivery/order system, as an alternative to Foodpanda, Grab, or Gojek. | Python, HTML, CSS, JavaScript, Flask               | Use Case: Local shop map tagging + customer QR orders                                  | ✔️ Complete |
| 🧪 **Lezy Web Benchmark**                       | Website performance & analysis tool for front-end and back-end testing.                           | Python, HTML, CSS, JavaScript                      | Deployment: Netlify<br>Preview: Lezy Web Benchmark                                     | ✔️ Complete |
| 🔐 **Minimalistic Login/Signup System**         | Lightweight authentication framework using pure PHP & MySQL.                                      | PHP (Native), Apache, HTML, CSS, MySQL             | Integration: OAuth2.0 via Supabase<br>Providers: Facebook, GitHub, Google, Email<br>Optional: Local or Remote DB integration<br>Security: JWT-based token system | ✔️ Complete |
| 💫 **Dynamic .GIF & Video Autoplay Card**       | Dual-mode interactive card system featuring .GIF animation with dynamic video autoplay when viewed via camera (mobile/webcam). Designed for wedding invitations or as a Travel Digital Souvenir (autoplays video on supported devices). | HTML, CSS, JavaScript, Media API, Device Detection | Modes: Wedding Card / Travel Souvenir<br>Feature: Conditional autoplay for supported devices | ✔️ Complete |
| 🎟️ **Animated E-Ticket Product (Private)**     | End-to-end E-Ticket Management System featuring an admin dashboard, web/mobile accessibility, and animated ticket UI. Built with a clean, functional design emphasizing scalability, speed, and user experience. | React.js, Node.js, Express, MySQL, Tailwind CSS    | Feature: Role-based access, ticket animation, QR integration, dashboard analytics<br>Access: 🔒 Private Repository | ✔️ Complete |

---

🔨 **Ongoing Projects**

| Project                                         | Description                                                                                       | Stack / Tools                            | Status                                     |
| ----------------------------------------------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------- | ------------------------------------------ |
| 📺 **Wayang Seni Pujangga**                     | Website Streaming Provider                                                                        | HTML, CSS, JavaScript                    | 🚧 In Development                          |
| 💌 **iMomento**                                 | Virtual Live-feed Invitation Card                                                                 | HTML, CSS, JavaScript                    | 🚧 In Development                          |
| 📄 **Simply Me**                                | Document Report Generator                                                                         | Python, HTML                             | 🚧 In Development                          |
| 🧠 **Sarawak Native LLM Model**                 | Language model prototype for Sarawak native dialects                                              | Hugging Face, Ollama, OpenRouter, Python | ⚙️ Dataset Integration & Fine-tuning Phase |
| 🗃️ **Digital Video Repository (Remote/Local)** | Repository for hosting and managing videos with metadata tagging and user upload system           | Node.js, React.js, MongoDB               | ⚙️ Development                             |
| 🧭 **Landing Page 101**                         | Dynamic & customizable landing page template optimized for developer portfolios and startup pages | HTML, CSS, Tailwind, JavaScript          | ⚙️ Development                             |
| 🧾 **Portfolio 101**                            | Interactive developer portfolio site (React + Markdown + Animation effects)                       | React.js, Tailwind CSS, Framer Motion    | ⚙️ Development                             |
| 📊 **Simpli Report Generator API’s**            | Lightweight REST API for generating structured reports in PDF/Docx/CSV formats                    | Python (Flask/FastAPI), OpenAI API       | ⚙️ Development                             |
| 🔗 **MCP (Sarawak Native LLM Continuation)**    | API extension layer for integrating the Sarawak Native Model into web & app systems               | Hugging Face, FastAPI, Ollama Cloud      | ⚙️ Prototype Phase                         |
| 🌀 **QRGGIF: AR-integrated Animated QR Auth**   | Authentication system that scans **animated .GIF QR codes** to trigger **AR-based interactions**. Built for **event ticketing and interactive media**. Integrates camera sensors with **GIF decoding + AR overlay triggers**. | React Native, Tkinter, MySQL, AR Engine, Netlify, Supabase | ⚙️ AR Integration & Authentication Phase || 

  Project                                   | Description                                                                                                                                                                                                                                                                                     | Contact                                                                                                                                                                                      |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🌐 **Ultimate Event 3D Interactive Page** | Concept project exploring a **3D immersive event platform** that integrates ticketing, AR/VR-based venue navigation, and real-time social interaction. <br><br> Intended as a **next-gen event engagement experience**, combining 3D visuals, interactive maps, and virtual attendance systems. | 💌 **Interested in funding or collaboration?** <br> 📧 [wan.mohd.azizi.seggaf@gmail.com](mailto:wan.mohd.azizi.seggaf@gmail.com) <br> 📧 [ctaxnagomi@gmail.com](mailto:ctaxnagomi@gmail.com) |
| 🌀 **QRGGIF: AR-integrated Animated QR Auth System** | A hybrid **QR + AR** authentication project that fuses **animated .GIF QR codes** with **augmented reality triggers**. When scanned, the system verifies the GIF’s unique frame signature to **authenticate and project AR content**—ideal for event tickets, interactive media, and product experiences. | 💡 **Deployment:** Netlify <br> ⚙️ **Database:** Supabase + MySQL <br> 🧩 **Integration:** AR SDK + React Native Frontend |

💰 Donations & Contributions

I truly appreciate every contribution — it helps fund ongoing open-source and AI innovation like the Sarawak Native LLM, Lezy Solutions Projects, and future creative tools.
For project-based contributions or collaborations, please contact me directly at:
📧 wan.mohd.azizi.seggaf@gmail.com
📧 ctaxnagomi@gmail.com

🌍 Crypto Contributions
| Cryptocurrency     | Badge                                                                                                | Address                                                                                                   | QR Code                                                                                               |
| ------------------ | ---------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Bitcoin (BTC)**  | ![Bitcoin](https://img.shields.io/badge/Bitcoin-FF9900?style=flat\&logo=bitcoin\&logoColor=white)    | `bc1q65qjzvwyq2czumpy6tevtv2lgqvmvn3gh54ym7`                                                              | <details><summary>🟠 Show QR</summary><br><img src="./qrcode-btc.jpg" width="130"/><br></details>     |
| **Ethereum (ETH)** | ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat\&logo=ethereum\&logoColor=white) | `0xd5d0AF6c78F4E203C5121740a747E92F0E4C9e5f`                                                              | <details><summary>🟣 Show QR</summary><br><img src="./qrcode-eth.jpg" width="130"/><br></details>     |
| **XRP (Ripple)**   | ![XRP](https://img.shields.io/badge/XRP-25A768?style=flat\&logo=ripple\&logoColor=white)             | `rUYHZ71yXAS54ZQNvvooLX7rFtZydXjnP`                                                                       | <details><summary>💧 Show QR</summary><br><img src="./qrcode-xrp.jpg" width="130"/><br></details>     |
| **Solana (SOL)**   | ![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat\&logo=solana\&logoColor=white)       | `7hphP53qK9CVZUs2atFSDxmW6zD2PM7zLgryeCSPj9iH`                                                            | <details><summary>🌈 Show QR</summary><br><img src="./qrcode-solana.jpg" width="130"/><br></details>  |
| **Cardano (ADA)**  | ![Cardano](https://img.shields.io/badge/Cardano-0033AD?style=flat\&logo=cardano\&logoColor=white)    | `addr1qx6r76z06h4ynnsxavwla7jpzhn0wrjtg2wgx7mgm8xhhmwl5nvwe8r678glwy8wkv2tw6rdx624mhh4jhy2y6vd6hdqmc9l5a` | <details><summary>🔵 Show QR</summary><br><img src="./qrcode-cardano.jpg" width="130"/><br></details> |



💡 All donations directly support development, testing, and infrastructure for AI, automation, and creative tech projects.

💵 Local Support (Malaysia)
| Platform                       | Badge                                                                                                                                                            | Payment Link                                                                               | QR Codes                                                                                                                                                                                             |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Touch ‘n Go (TNG Business)** | [![TNG](https://img.shields.io/badge/Touch’nGo%20Business-009FE3?style=flat\&logo=tngdigital\&logoColor=white)](https://payment.tngdigital.com.my/sc/bDLnQhnx4s) | [payment.tngdigital.com.my/sc/bDLnQhnx4s](https://payment.tngdigital.com.my/sc/bDLnQhnx4s) | <details><summary>📲 Show QR Codes</summary><br>**Standard:** <br><img src="./qr-tng-standard.jpg" width="130"/><br><br>**DuitNow:** <br><img src="./qr-tng-duitnow.jpg" width="130"/><br></details> |




<div>



</div>
