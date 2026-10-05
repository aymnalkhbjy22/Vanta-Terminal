
# ⚡ WormGPT Web Interface — Advanced Multi-Model AI Workspace

[![GitHub stars](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Termux%20%7C%20Linux-blue.svg)]()
[![License](https://img.shields.io/badge/License-MIT-red.svg)]()
[![Developer](https://img.shields.io/badge/Developer-Ayman%20Al--Khabji-orange.svg)]()

> A lightweight, fully responsive, and highly customizable frontend interface engineered to interface seamlessly with modern Large Language Models (LLMs) via OpenRouter and unified API endpoints.

---

## 👨‍💻 Lead Developer & Architecture

* **Lead Developer:** **Ayman Al-Khabji** (أيمن الخبجي)
* **Domain:** Cybersecurity & Software Engineering

---

## 🌟 Key Capabilities & Features

* **Multi-LLM Integration:** Dynamic runtime switching between leading commercial and open-source models:
  * `DeepSeek-V3 / DeepSeek-R1`
  * `Meta Llama 3.3 70B Instruct`
  * `Qwen 2.5 72B`
  * `OpenAI GPT-4o mini`
  * `Google Gemini 1.5 Flash`
* **Client-Side API Security:** Secure in-browser token storage (`localStorage`) supporting customizable API keys without hardcoded exposure.
* **Low-Latency Streaming:** Real-time token streaming with integrated execution control (`AbortController` for stopping output mid-generation).
* **Technical Markdown & Syntax Engine:** Fully formatted output rendering via `marked.js` and `highlight.js` with instant code-copying utility.
* **Cyberpunk & Minimal Themes:** Built-in UI themes tailored for development and nighttime workflows (`Devil`, `Dark Matrix`, `Purple Synth`).
* **Multi-Format Export & Sharing:** Export active sessions to raw `TXT` or structured `JSON`, with encoded URL sharing (`#share=...`).

---

## 🚀 Deployment & Usage

### Method 1: Live Deployment (GitHub Pages)
Launch the application directly through GitHub Pages without installing local dependencies:
```text
https://<YOUR_GITHUB_USERNAME>.github.io/wormgpt-web/
