# 🎙 Voice Tutor

A lightweight, browser-based voice learning tool that lets you ask questions out loud and get structured AI-powered answers in real time — no installation required.

## What it does

Voice Tutor listens to your spoken question, transcribes it using OpenAI Whisper, and returns a concise, structured answer using your AI provider of choice. It's designed for self-study, interview prep, and knowledge checks on any topic.

## Features

- 🎤 **Toggle-to-talk** — press `Space` once to start recording, press again to stop and get an answer
- 🌐 **Multi-provider support** — works with OpenAI, Anthropic (Claude), and Google Gemini
- 📄 **Doc Mode** — upload a PDF and get answers based strictly on its content; if the answer isn't in the document, the app will tell you
- 🗣 **Language selector** — force transcription in a specific language to avoid mis-detection
- 🔤 **Adjustable font size** — large, readable answers on any screen
- 🌙 **Light / Dark theme** — switch anytime during your session
- 📋 **Session history** — review previous Q&A pairs within the session
- 🔒 **Fully client-side** — your API key and documents never leave your browser

## How to use

1. Open the app in your browser
2. Select your AI provider and paste your API key
3. Choose your spoken language
4. Write a session context (e.g. *"Answer questions on QA topics for a Middle Manual QA Engineer"*)
5. Press **Start Session**
6. Press `Space` to ask a question — press `Space` again when done speaking
7. Read the answer on screen

## Doc Mode

Switch to **📄 Doc** mode in the header, upload a PDF, and the AI will only answer from its content. Useful for studying specific materials, documentation, or interview guides.

## Tech stack

- Vanilla HTML / CSS / JavaScript — no frameworks, no build tools
- [OpenAI Whisper](https://platform.openai.com/docs/guides/speech-to-text) for speech-to-text
- [PDF.js](https://mozilla.github.io/pdf.js/) for client-side PDF parsing
- OpenAI / Anthropic / Gemini APIs for answers

## Setup

No installation needed. Just open `index.html` in a browser — or host it on GitHub Pages.

> ⚠️ You need a valid API key from your chosen provider. Keys are stored in memory only and are never sent anywhere except the provider's API.
