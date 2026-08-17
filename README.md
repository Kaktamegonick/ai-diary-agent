# AI Diary Agent

I built this agent because I wanted to keep a personal diary without manually organizing everything in Obsidian.

I just send a message to the agent in Telegram. It can create and edit notes in my Obsidian vault and connect related events with links.

The agent runs on my VPS, so I can use it from Telegram at any time.

## Demo



https://github.com/user-attachments/assets/c8d0a316-e64e-4821-8cb9-258bc43a6a19





## How it works

```text
Me
 ↓
Telegram
 ↓
AI Agent on VPS
 ↓
DeepSeek API
 ↓
Tools
 ├── Create notes
 ├── Edit notes
 └── Link related notes
 ↓
Obsidian
```

## What it can do

* Receive messages through Telegram
* Create diary entries in Obsidian
* Edit existing Markdown files
* Find connections between related events
* Add links between related notes
* Run continuously on a VPS

## Why I built it

I use Obsidian for my notes, but I didn't want to manually write and organize every diary entry.

So I built an agent that does this for me.

For example, I can send something like:

> Today I started learning about AI agents and tool calling.

The agent can turn it into a diary entry and connect it with related notes that already exist in my Obsidian vault.

Over time this creates a connected history instead of just a folder with separate diary files.

## Stack

* Python
* Telegram Bot
* DeepSeek API
* Obsidian / Markdown
* VPS

## Current status

The agent is running on my VPS and I use it through Telegram.

I'm still experimenting with the project and adding new functionality as I learn more about AI agents.

The source code is currently private. This repository is a small showcase of how the project works.
