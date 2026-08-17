AI Diary Agent

A personal diary assistant built on top of Hermes Agent.

I wanted a simple way to keep a diary without manually creating and organizing notes in Obsidian every day.

I deployed Hermes Agent on my VPS, connected it to DeepSeek and Telegram, and configured it to work with my Obsidian vault.

Now I can just send a message in Telegram and the agent can turn it into a diary entry, edit existing notes and create links between related events.

Demo

https://github.com/user-attachments/assets/c8d0a316-e64e-4821-8cb9-258bc43a6a19

How it works

Me
 ↓
Telegram
 ↓
Hermes Agent (VPS)
 ↓
DeepSeek API
 ↓
File tools
 ↓
Obsidian Vault
What it does
Receives my messages through Telegram
Creates diary entries in Obsidian
Edits existing Markdown notes
Connects related events with Obsidian links
Runs continuously on my VPS

For example, I can tell the agent about something that happened during the day.

Instead of manually opening Obsidian, creating a file and organizing it, I just send a Telegram message. The agent handles the note for me.

If a new event is related to something from an older note, it can add a link between them.

What I did

This project is not an AI agent built from scratch.

I used Hermes Agent as the agent framework and configured it for my own use case.

I:

deployed Hermes Agent on a VPS
connected DeepSeek as the LLM
set up Telegram as the interface
connected the agent to my Obsidian vault
configured how diary entries are created and edited
set up linking between related notes

The goal of this project was to get hands-on experience with AI agents and understand how LLMs, tools and external applications can work together.

Stack
Hermes Agent
DeepSeek API
Telegram
Obsidian
Markdown
Linux VPS
What's next

I'm currently learning how agent systems work internally.

My next step is to build a smaller agent from scratch in Python to better understand tool calling, agent loops and memory.
