<div align="center">
<img src="https://wiki.mira.tg/logo.png" alt="Mira AI for Telegram" width="120" />

# Mira — AI for Telegram

AI in Telegram for chat, content creation, memory, integrations, and on-chain actions.

[![Telegram](https://img.shields.io/badge/Try%20Mira-%40mira-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/mira)
[![Stars](https://img.shields.io/github/stars/DariaYakovleva/mira-wiki?style=for-the-badge)](https://github.com/DariaYakovleva/mira-wiki/stargazers)
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](LICENSE)

[**Open Mira in Telegram →**](https://t.me/mira) · [**Documentation**](https://wiki.mira.tg) · [**Report Bug**](https://github.com/DariaYakovleva/mira-wiki/issues)

</div>

---

## What is Mira?

**Mira AI** (`@mira`) is an AI assistant built for Telegram.

It works inside Telegram chats and supports:

- chat and reasoning
- image, voice, and video workflows
- app integrations
- memory across conversations
- TON wallet actions

Mira can respond to requests, work with context from ongoing chats, and perform actions through connected tools.

> Type `@mira` in a Telegram chat to start using Mira.

---

## Quick Start

### 1. Open Mira in Telegram

👉 [**t.me/mira**](https://t.me/mira)

### 2. Send a message

You can start with a question, task, or prompt.

```text
Hey Mira, what can you do?
```

### 3. Connect tools

Mira can connect to external services through OAuth links sent in chat.

```text
Connect my Gmail
Connect GitHub
Connect Notion
```

---

## Core Capabilities

### Chat & Reasoning

Mira supports general chat, writing, research, coding help, translation, and analysis.

- GPT-4o is used in normal mode
- Qwen3-32B is used in private mode

**Examples:**
```text
Summarize this article and translate it to Spanish
Debug this Python function and explain what was wrong
Write a cold email to a VC investor for my fintech startup
```

### Image Generation & Editing

Mira can generate images from text, edit images, and analyze visual content in Telegram.

Supported aspect ratios: `9:16` · `16:9` · `1:1` · `4:5` · `3:2`

- Image generation costs **30 tokens**
- Image analysis is **free of charge**

**Examples:**
```text
Generate a portrait of a woman in Art Nouveau style, floral background
Make this photo anime style
What's in this photo?
```

### Voice & Audio

Mira supports voice messages, voice replies, music generation, and transcription.

| Voice Style | Description |
|-------------|-------------|
| `nova` | Energetic and bright (default) |
| `alloy` | Versatile and neutral |
| `onyx` | Deep and resonant |
| `shimmer` | Clear and melodic |
| `sage` | Authoritative and sharp |
| `coral` | Clear and bright |

**Examples:**
```text
Create a jazz song about coffee and Monday mornings
Read this article to me as a voice message
```

### Video Generation

Mira supports text-to-video, image animation, Instagram Reel downloads, and Telegram video note conversion.

- Video generation costs **100 tokens**

**Examples:**
```text
Generate a video of a sunset over the ocean with gentle waves
Animate this photo — make the hair flow in the wind
Convert this to a video note
```

---

## Integrations

Mira connects to **800+ apps** via [Composio](https://composio.dev).

| Integration | What Mira can do |
|-------------|-----------------|
| Gmail | Read, send, search emails |
| Google Calendar | View events, create meetings, set reminders |
| GitHub | Read repos, create issues, push files |
| Notion | Read and write pages and databases |
| Google Sheets | Read and update spreadsheets |
| Slack | Send messages to channels |
| + 800 more | Figma, Linear, Jira, HubSpot, Airtable… |

**Examples:**
```text
Create a GitHub issue: "Fix login bug"
Add a row to my Google Sheet with today's sales data
Connect my Gmail
```

---

## TON Wallet

Every Mira user gets a personal TON wallet created automatically.

**Examples:**
```text
What's my wallet balance?
Send 5 USDT to @username
Swap 2 TON to USDT
Show my recent transactions
```

> ⚠️ The wallet is currently running on **testnet**. Funds have no real monetary value.

---

## Memory

Mira includes both personal memory and group memory.

**Personal memory stores:**
- personal details and preferences
- ongoing projects

**Group memory stores:**
- shared decisions in group chats
- action items from team conversations

**Examples:**
```text
@mira what did we decide about the launch date?
@mira summarize the last 2 hours of this chat
@mira what are the open action items?
```

---

## Private Mode

For sensitive conversations, Mira routes requests to **Cocoon** — a confidential compute network.

| | Normal Mode | Private Mode |
|---|-------------|--------------|
| **Model** | GPT-4o (OpenAI) | Qwen3-32B (Cocoon) |
| **Data storage** | OpenAI infrastructure | Not stored |
| **Privacy** | Standard | Maximum (TEE) |
| **Speed** | Fast | Fast |

Requests in Private Mode are processed inside a **Trusted Execution Environment (TEE)**.

**Enable:** Mira mini-app → Discover → Private Mode

---

## Infrastructure

### Skills

Skills are scheduled automations with no code required.

**Examples:**
```text
Every Monday at 9am, pull my GitHub issues and summarize them
Remind me to review the deck 1 hour before every meeting
Check my inbox daily and flag anything urgent
```

### MCP Integrations

Mira supports MCP integrations to connect APIs and services.

### Model Flexibility

Mira can switch between **Claude**, **GPT-4o**, **Qwen**, and **Gemini** depending on the task.

### Agent-to-Agent

Mira supports chaining specialized agents for multi-step workflows.

---

## Example Use Cases

**In personal chats:**
- ask questions
- generate content
- summarize information
- create images, audio, or video
- check wallet activity

**In group chats:**
- summarize discussions
- track decisions
- extract action items
- answer questions based on recent conversation context

**With connected tools:**
- read and send email
- create calendar events
- create GitHub issues
- update Notion pages
- write to spreadsheets

---

## Comparison

| Feature | Mira | ChatGPT / Claude | Zapier / Make |
|---------|------|-----------------|---------------|
| Works in Telegram | ✅ | ❌ | ❌ |
| Group chat context | ✅ | ❌ | ❌ |
| Executes actions through tools | ✅ | Limited | ✅ |
| TON wallet support | ✅ | ❌ | ❌ |
| Private Mode | ✅ | ❌ | ❌ |

---

## Who Mira may be useful for

**Teams using Telegram:**
- summarize discussions
- extract action items
- coordinate meetings

**Power users:**
- use different models for different tasks
- enable Private Mode
- create scheduled automations

**Founders and operators:**
- prepare updates
- monitor news
- handle routine tasks inside Telegram

**SMB workflows:**
- customer communication through Telegram Business
- lead handling
- scheduling and follow-ups

---

## Roadmap

- [x] Chat & Reasoning
- [x] Image generation and editing
- [x] Voice messages and music generation
- [x] Video generation and processing
- [x] 500+ integrations via Composio
- [x] TON Wallet (testnet)
- [x] Personal & group memory
- [x] Private Mode
- [x] Skills & scheduling
- [ ] TON Wallet mainnet
- [ ] Expanded Agent-to-Agent marketplace
- [ ] Skills marketplace

---

## Links

| Resource | Link |
|----------|------|
| Website | [mira.tg](https://mira.tg/) |
| Telegram | [t.me/mira](https://t.me/mira) |
| Documentation | [wiki.mira.tg](https://wiki.mira.tg) |
| Issues | [GitHub Issues](https://github.com/DariaYakovleva/mira-wiki/issues) |

<div align="center">

[Use Mira in Telegram →](https://t.me/mira)

</div>




