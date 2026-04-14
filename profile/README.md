# FreJun

**Real-time voice infrastructure for AI agents and business calling.**

---

## What is FreJun

FreJun is the real-time voice infrastructure company. We help business teams automate calling workflows and enable developers to connect AI bots and agents to voice infrastructure — all in one platform.

FreJun has two products: **Teler** for developers building AI voice applications, and **Dialer** for business teams running sales and support operations.

---

## Teler — Voice calling infra for developers

Teler is a global programmable voice API and telephony infrastructure for developers building AI voice agents, real-time conversation AI, and custom voice applications.

It handles carriers, audio streaming, and call control so you can focus on your product.

**How it works:**
```
Caller → Teler Number → WebSocket → Your Server
                                        ↓
                               STT → LLM → TTS
                                        ↓
                         Audio injected back into live call
```

**Core capabilities:**
- Real-time bidirectional audio streaming via WebSocket (<250ms latency)
- Global phone number provisioning in 50+ countries via API
- SIP trunking with TCP/TLS transport
- Call recording, webhooks, and call flow control
- Model-agnostic — works with OpenAI, ElevenLabs, Deepgram, Gemini, VAPI, Devnagri, or any custom model

**What developers build:**
- AI voice agents (support, sales, scheduling, receptionist)
- Intelligent IVR with natural language understanding
- Automated outbound campaigns
- Voice-enabled SaaS features (click-to-call, transcription, recording)

---

## Dialer — Business calling platform

FreJun Dialer is a cloud telephony platform for sales and support teams.
It provides IVR, call recording, autodial, and CRM integration — with a
full REST API for Calling, Number Management, User Management, and Webhooks.

→ [frejun.com](https://frejun.com) · [API docs](https://frejun.com/docs)

---

## When to use what

| I want to... | Use |
|---|---|
| Build an AI voice agent or bot | **Teler** |
| Add phone calls to my application | **Teler** |
| Stream real-time audio to my AI model | **Teler** |
| Connect existing SIP platforms to carrier | **Teler** (SIP Trunking) |
| Give my sales/support team a calling tool | **Dialer** |
| Set up IVR, call recording, CRM sync | **Dialer** |
| Embed calling into a mobile app | **Dialer** (Mobile SDK) |

---

## Repositories

**Teler SDKs**
| Repo | Language | Description |
|---|---|---|
| [teler-py](https://github.com/frejun-tech/teler-py) | Python | Lightweight abstraction over the Teler API |
| [teler-node](https://github.com/frejun-tech/teler-node) | Node.js | Teler API SDK for Node.js |

**Teler integration bridges**
| Repo | Description |
|---|---|
| [teler-openai-bridge](https://github.com/frejun-tech/teler-openai-bridge) | Teler + OpenAI Realtime API via WebSocket |
| [teler-vapi-bridge](https://github.com/frejun-tech/teler-vapi-bridge) | Teler + VAPI |
| [teler-gemini-bridge](https://github.com/frejun-tech/teler-gemini-bridge) | Teler + Gemini Live API |
| [teler-elevenlabs-bridge](https://github.com/frejun-tech/teler-elevenlabs-bridge) | Teler + ElevenLabs |
| [teler-devnagri-bridge](https://github.com/frejun-tech/teler-devnagri-bridge) | Teler + Devnagri |

**Dialer SDKs**
| Repo | Platform | Description |
|---|---|---|
| [react-native-softphone-sdk](https://github.com/frejun-tech/react-native-softphone-sdk) | React Native | Embed FreJun calling into mobile apps |

---

## Get started

**Teler (developers)**
1. Sign up → [platform.frejun.ai](https://platform.frejun.ai/signup)
2. Provision a number via the API
3. Pick a repo above that matches your AI provider or language
4. Run the example and connect your model

**Dialer (business teams)**
1. Sign up → [product.frejun.com](https://product.frejun.com/signup)
2. Set up your team, numbers, and CRM integration
3. Start calling

---

## Links

| | Teler | Dialer |
|---|---|---|
| Website | [frejun.ai](https://frejun.ai) | [frejun.com](https://frejun.com) |
| Docs | [frejun.ai/docs](https://www.frejun.ai/docs/) | [frejun.com/docs](https://frejun.com/docs/) |
| Sign up | [platform.frejun.ai/signup](https://platform.frejun.ai/signup) | [product.frejun.com/signup](https://product.frejun.com/signup) |
