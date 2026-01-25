# 🦞 Clawdbot — Personal AI Assistant

**Clawdbot** is a personal AI assistant that runs locally on your devices. It unifies your communication into a single flow, answering you on the channels you already use.

### 🚀 From a Team of Enthusiasts: Our Mission

We are a community of enthusiasts who have taken the original project and significantly refined it. Our goal is to make a powerful personal assistant accessible to everyone **completely free of charge**, without the need to pay for expensive API subscriptions.

**❗ Critical Difference from the Original:**
We have fixed numerous critical bugs present in the original version. Most importantly, **the original model suffers from defects leading to colossal and unjustified token overconsumption.** We have eliminated this issue: our version is optimized, stable, and does not waste resources.

---

### Flexibility and Token Savings

Thanks to our optimizations, you have complete freedom of choice:

1. **Free (Our Recommendation):** You can use the bot without spending any of your own funds by utilizing our provided **Anthropic Pro/Max (100/200) tokens paired with Opus 4.5**. This ensures long-context performance and high resistance to prompt injection without hitting your wallet.
2. **Bring Your Own Keys:** If you prefer, you can connect **your own API keys** (Anthropic, OpenAI, etc.) if you have personal subscriptions or require specific models.

### Core Functionality

* **Multi-channel Inbox:** Supports WhatsApp, Telegram, Slack, Discord, Google Chat, Signal, iMessage, Microsoft Teams, BlueBubbles, Matrix, Zalo, and WebChat.
* **Local-first:** A single control plane (Gateway) for sessions, channels, and tools runs on your own hardware.
* **Voice Control:** **Voice Wake** and **Talk Mode** features allow you to speak with the assistant via voice (supports macOS, iOS, Android).
* **Live Canvas:** An agent-controlled visual workspace (capable of displaying content and UI).
* **Agent Tools:** The bot has access to browser control, local files, task scheduling (cron), camera, and screen captures.
* **Multi-agent Routing:** Capability to route inbound messages from different channels or accounts to isolated agents (separate workspaces and sessions).

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
