# Calling Agent

The Calling Agent is an AI-powered voice assistant that connects telephony and intelligence.  
It uses **Twilio** for voice call handling, **ngrok** for local server tunneling, and **DeepMind or AI APIs** for generating intelligent responses.

---

## Overview

This project allows users to make or receive automated phone calls where an AI agent can respond, speak, and interact dynamically.  
It is built to demonstrate real-time AI interaction over a voice channel.

---

## Features

- Real-time call handling using **Twilio Programmable Voice**
- Secure local testing through **ngrok**
- Intelligent responses generated via **DeepMind / AI model API**
- Customizable voice prompts using TwiML
- Modular Node.js backend for easy extension

---

## Tech Stack

- **Backend:** Node.js, Express.js  
- **Telephony:** Twilio Programmable Voice  
- **AI:** DeepMind API (or similar LLM endpoint)  
- **Tunneling:** ngrok  
- **Environment:** dotenv for API key management

---

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/pujanajmera/calling-agent.git
   cd calling-agent

2. start a server for ngrok
   - ngrok
   - ngrok http 5000

  
3. start server 2 for recieving msg
   -uv run .\main.py

// note you will have to link your api keys to this also need to buy a number for free from [twilio.](https://console.twilio.com/)
