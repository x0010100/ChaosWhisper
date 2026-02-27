<div align="center">

```
▓▓▓▓▓█▓▓▓▓▓▓███▓██▓▓█▓▓▓█▓▓█▓██▓▓▓▓▓▓▓███▓▓▓█▓█▓█▓▓▓▓█▓▓▓▓█▓▓▓██▓▓▓█▓█▓██
```

# 🌀 ChaosWhisper `v1.0.0`

**The terminal AI interface built for people who refuse to leave the command line.**

[![Platform](https://img.shields.io/badge/platform-Linux%20x86__64-blue?style=flat-square)](https://github.com/x0010100/ChaosWhisper)
[![License](https://img.shields.io/badge/license-Commercial-red?style=flat-square)](https://github.com/x0010100/ChaosWhisper)
[![Release](https://img.shields.io/badge/release-v1.0.0-brightgreen?style=flat-square)](https://github.com/x0010100/ChaosWhisper/releases/tag/v1.0.0)
[![Binary](https://img.shields.io/badge/binary-standalone-orange?style=flat-square)](https://github.com/x0010100/ChaosWhisper/releases/tag/v1.0.0)

*No Python required. No browser. No distractions. Just you, the terminal, and the AI.*

</div>

---

## 🚀 What is ChaosWhisper?

ChaosWhisper is a fully-featured, terminal-native AI chat interface that goes far beyond simple Q&A. It's designed for developers who want **agent-powered automation**, **persistent sessions**, **multi-provider flexibility**, and **deep reasoning** — all without ever leaving the terminal.

Distributed as a single compiled binary. Drop it on your machine and run.

---

## ✨ Core Features

### 🤖 Agent Mode — Autonomous Task Execution
ChaosWhisper's agent isn't just a chatbot that suggests code — it **executes**. Give it a task and it will:
- Break it down into a structured step-by-step plan
- Write files, run shell commands, and iterate
- Detect errors and automatically fix them
- Resume mid-execution if interrupted

Supports both **Native** (direct shell) and **Docker** (sandboxed) execution modes.

---

### 🏗️ Project Builder — From Idea to Codebase
Describe what you want to build in plain English. ChaosWhisper will:
1. Generate a detailed, structured project plan
2. Present it for your review and approval
3. Execute each step autonomously until completion

> *"Build a FastAPI REST API with JWT auth and SQLite"* → Full project, ready to run.

Automatically enables strict mode and maximum detail for complex projects.

---

### 🧠 Session History & Persistence
Every conversation is saved. Every session is resumable.

- Full message history persisted to disk across restarts
- Smart **message compaction** — long conversations are summarized automatically to preserve context without hitting token limits
- Interrupted agent runs can be **resumed exactly where they left off**
- Browse, search, and continue any past session from the history menu

---

### 🔓 Jailbreak Mode
Built-in jailbreak profiles to unlock unrestricted model responses. Toggle on/off from the main menu — no config editing required.

---

### 💡 Ultra Deep Thinking — 5 Levels of Reasoning

| Level | Description |
|-------|-------------|
| `light` | Quick step-by-step reasoning |
| `medium` | Structured multi-step analysis |
| `deep` | Multi-perspective deep dive |
| `expert` | Exhaustive expert-grade analysis |
| `GOD MODE` | Maximum depth. No limits. |

Applies reasoning enhancement to every prompt before sending to the model.

---

### ⚙️ Full Feature List

| Feature | Details |
|---------|---------|
| **Multi-provider API** | Connect to OpenAI, Anthropic, or any OpenAI-compatible endpoint |
| **IDE-style code rendering** | Pygments syntax highlighting with line numbers inside panel borders |
| **Auto-Fixer** | Detects runtime errors and retries with fixes automatically (configurable attempts or unlimited) |
| **File Upload in Prompt** | Attach and inject file contents directly into your message with `/upload` |
| **Git Integration** | Built-in git utilities used by the agent for version-controlled project building |
| **Encrypted Prompts** | Protect sensitive system prompts with Fernet encryption |
| **Message Compaction** | AI-powered or fallback summarization when history grows too long |
| **Code Extraction** | Automatically extracts and saves code blocks from responses |
| **Export / Backup** | Export full conversation logs to file |
| **Dependency Detection** | Automatically detects and installs missing Python packages for generated code |
| **Multi-line Input** | Full multi-line editor with history search powered by `prompt_toolkit` |
| **Interrupt Handler** | Safely interrupt long operations with `Ctrl+C` without losing state |
| **License System** | Request-limited licensing with per-day limits and expiry dates |
| **Compiled Binary** | Single standalone `.bin` — no Python, no venv, no install |

---

## 📦 Installation

### 1. Download
Grab `chaosWhisper.bin` from the **Assets** section below.

### 2. Make executable
```bash
chmod +x chaosWhisper.bin
```

### 3. Activate license
```bash
./chaosWhisper.bin --license YOUR_LICENSE_KEY
```

### 4. Run
```bash
./chaosWhisper.bin
```

### Optional: Add to PATH
```bash
sudo mv chaosWhisper.bin /usr/local/bin/chaoswhisper
chaoswhisper
```

---

## 🖥️ System Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Linux x86_64 |
| **Python** | Not required (standalone binary) |
| **Clipboard** | `wl-clipboard` (Wayland) or `xclip` (X11) — optional |

**Install clipboard support:**
```bash
# Wayland (most modern distros)
sudo pacman -S wl-clipboard   # Arch
sudo apt install wl-clipboard # Debian/Ubuntu

# X11
sudo pacman -S xclip
sudo apt install xclip
```

---

## 🔑 Licensing

ChaosWhisper is distributed under a **commercial license** with a personalized key-based activation system.

- Each license is **unique per user** — keys are non-transferable
- Includes a **daily request limit** and an **expiry date** configured per license
- Your System ID is tied to the license — works only on your machine
- To check your System ID: `./chaosWhisper.bin --system-id`

### 📬 How to Get a License

1. Run `./chaosWhisper.bin --system-id` and copy your System ID
2. Contact via Telegram and send your System ID
3. Receive your personal license key
4. Activate it:
```bash
./chaosWhisper.bin --license YOUR_LICENSE_KEY
```

> 💬 **Telegram:** [@0x0010100]

---

<div align="center">

**Built by [x0010100](https://github.com/x0010100)**

*If you find ChaosWhisper useful, leave a ⭐*

</div>
