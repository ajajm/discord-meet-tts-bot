# Sppechflow: Text-to-Speech Bot

A minimal Discord bot that converts text messages into speech and plays them in voice channels.

This project focuses on **clarity, predictability, and correctness** over feature bloat. It does one thing: take text and speak it—reliably.


## Features

* Joins a discord voice channel and google meet.
* Converts text messages to speech
* Plays audio with low latency
* Simple command surface
* Modular controller / route structure

Non-goals:

* Music playback
* Fancy UI dashboards
* Overengineered abstractions


## Requirements
* Node.js ≥ 18
* A Discord Bot Token
* A Discord server where you have permission to add bots

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/discord-tts-bot.git
cd Speechflow
```

Install dependencies:

```bash
npm install
```

## Configuration

Create a `.env` file in the project root:

```env
DISCORD_TOKEN=your_bot_token_here
```

If you don’t know what this token is, stop here and read the Discord developer documentation first.


## Running the Bot

```bash
npm start
```

For development:

```bash
npm run dev
```

If the bot doesn’t come online:

* Check your token
* Check gateway intents
* Check your logs before blaming the code


## Usage

Invite the bot to your server, join a voice channel, then issue a text command:

```text
!s Hello world
```

The bot will speak the message in the active voice channel.

Exact commands may vary depending on your configuration.

Silent failures are considered bugs.

## Contributing

Contributions are welcome, but keep them disciplined.

Rules:

* No unrelated features
* No sweeping refactors without justification
* Follow existing code style
* One logical change per commit

If your PR adds complexity without necessity, it will be rejected.
Use it, modify it, break it—just don’t pretend you wrote it.


Tell me which direction you want.
