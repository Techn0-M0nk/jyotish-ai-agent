# Jyotish Chat – Vedic Astrology AI Agent 🧿

This project is a simple Vedic astrology chatbot I built using the Replit AI Agent.  
The bot collects basic birth details and returns information based on Indian astrology.

## ✨ What the app does

- Asks the user for:
  - First and last name
  - Date of birth
  - Place of birth
  - Time of birth
- Calculates and shows:
  - Indian Lunar Sign (Chandra Rashi)
  - Swami (ruling planet of that Rashi)
- Then asks:
  - “Do you want horoscope for **today**, **this week**, **this month**, or **this year**?”
- Displays a simple, friendly horoscope text for the user’s Rashi.

## 🧠 What I learned

- How to describe an idea in natural language to an AI agent and let it create the app structure for me.
- Basic concepts of Vedic astrology like **Chandra Rashi** and **Swami**.
- How a web app is organised into folders (client, server, configs) and how build/run commands work.
- How to publish an app on Replit and back it up / showcase it on GitHub.

## 🛠 Tech Stack

- Replit AI Agent
- Node.js + TypeScript
- Web UI (chat-like experience)
- Simple rule-based logic for Rashi, Swami, and horoscope

## ▶️ Running the app locally

> Requires Node.js and npm installed.

```bash
# Clone this repository
git clone https://github.com/Techn0-M0nk/jyotish-chat.git
cd jyotish-chat

# Install dependencies
npm install

# Build and run (adjust if your package.json uses different scripts)
npm run build
node ./dist/index.cjs
