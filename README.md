# Coral — AI Chat in Your Browser

A lightweight, single-file AI chatbot. Chat locally, customize freely, no backend required.

## Features

- **Customizable** — Pick colors, fonts, personality, reply length, response style
- **Memory system** — Coral remembers facts about you across conversations
- **Multi-chat sidebar** — Organize conversations, auto-titled
- **Edit & retry** — Fix your messages or resend for a different response
- **Dark/light/auto mode** — Follows your system preference
- **All local** — No data leaves your browser (except optional API calls)

## Getting Started

1. Download `index.html` and open it in your browser
2. (Optional) Go to settings (gear icon) → Advanced section and add a Gemini API key to enable responses
3. Get a free Gemini key at [aistudio.google.com](https://aistudio.google.com/app/apikey)
4. Start chatting

## Customization

- **Interface** — Theme colors (6 presets + custom picker), 15 fonts
- **Personality** — Your name, mood (creative/supportive/direct/playful/serious/custom)
- **Behavior** — Reply length (tiny to XL), response pace (fast/medium/thinking/research), emoji toggle
- **Advanced** — Gemini API key for responses, Deep Dive mode toggle
- **Memory** — Save facts, clear anytime, Coral refers to you naturally

All settings persist in browser localStorage. All of your data stays yours.

## How It Works

- Each chat saves its full conversation history locally
- AI-generated titles auto-update based on first exchange
- Keyboard shortcuts: `Ctrl+N` (new chat), `Ctrl+K` (search chats)
- Edit (✏️) or retry (🔄) your messages, copy (📋) bot responses

## API Keys

- **Gemini API** (optional) — Enables responses. Free tier available at [aistudio.google.com](https://aistudio.google.com/app/apikey)

Key stored only in your browser; never sent to external servers.

## No Backend, No Tracking

This is a static HTML file. No server, no accounts, no analytics. Open it locally or host it anywhere.

## Tips

- **Deep Dive mode** — Turn on in settings for thoughtful, thorough responses
- **Memory** — Coral learns about you gradually. Share relevant facts naturally
- **Edit messages** — Click ✏️ to load a message into the input, edit it, and resend
- **Retry** — Click 🔄 to resend a message and get a different response

## Building From Source

All code is in `index.html`. No build step needed. Modify anything!

---

Made with ❤️ | v0.9 | Single file, zero dependencies
