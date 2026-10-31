# VibeCode - Local AI Mockup Generator

![Status](https://img.shields.io/badge/Status-In%20Development-brightgreen)
![Tech](https://img.shields.io/badge/Stack-Node.js%20%7C%20Ollama%20%7C%20Vanilla%20JS-blue)
![Purpose](https://img.shields.io/badge/Purpose-Local%20AI-lightgrey)

> *Built for French and Zorg.*

VibeCode is a local, private AI web application that generates HTML and CSS mockups based on text descriptions. 

Instead of opening ChatGPT and copy-pasting code back and forth, VibeCode runs entirely on your own machine using [Ollama](https://ollama.com/). It takes your prompt, feeds it to a local LLM, extracts the raw HTML/CSS, and renders it in a live preview window instantly.

## Features

- **100% Local and Private:** No API keys, no OpenAI bills, no data leaving your computer.
- **Live Preview:** Renders the generated HTML and CSS in a sandboxed iframe instantly.
- **One-Click Copy:** Cleanly strips markdown artifacts from the AI output and lets you copy the raw code to your clipboard.
- **Split-Screen UI:** A clean, dark-themed workspace inspired by classic web dev tools.

## Prerequisites

Because this app uses a local LLM, you must have **Ollama** installed and running.

1. Download and install [Ollama](https://ollama.com/download).
2. Open your terminal and pull a model. We recommend `llama3` for good HTML/CSS generation, or `codellama`:
   ```bash
   ollama run llama3
