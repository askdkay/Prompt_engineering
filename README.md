# ⚡ Dkay PromptLab — AI Prompt Enhancer

Dkay PromptLab is a lightweight, single-file React application that turns your short, rough ideas into highly detailed, precision-engineered prompts using Google's Gemini AI. 

Instead of writing vague requests to LLMs, PromptForge uses the **RCTFC framework** (Role, Context, Task, Format, Constraints) to generate expert-level prompts that guarantee dramatically better AI outputs.

## ✨ Features

- **Zero Setup Required:** Entirely built in a single `index.html` file using CDN links for React, Babel, and Tailwind CSS. Just open and run!
- **RCTFC Framework Injection:** Automatically structures your idea into an advanced prompt.
- **Local Key Storage:** Your Gemini API key is saved securely in your browser's `localStorage` and never leaves your device.
- **Model Selection:** Choose between different Gemini models (e.g., Gemini 3 Flash, Gemini 2.5 Flash).
- **Keyboard Shortcuts:** Press `Ctrl/Cmd + Enter` to instantly enhance your prompt.
- **Beautiful UI:** Animated background grid, glowing orbs, smooth transitions, and skeleton loaders for a premium feel.
- **Quick Copy:** One-click copy button with visual feedback.
- **Output Analytics:** Displays word count, character count, and estimated token usage for the generated prompt.

## 🚀 How to Run

Since PromptForge is a frontend-only, single-file application, there is no build process or server to start.

1. **Clone or Download** this repository.
2. Open the `index.html` file directly in any modern web browser.
3. Done!

## 🔑 Getting your Gemini API Key

To use PromptForge, you need a free Gemini API key:
1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Sign in with your Google account.
3. Click on **Create API Key**.
4. Paste this key into the API Key field in the PromptForge app. 

*(Note: Ensure your Google Cloud project has billing enabled if you face quota errors, or stick to the free-tier models).*

## 🧠 How the RCTFC Framework Works

Behind the scenes, PromptForge instructs the Gemini API to expand your input into five strict sections:
* **🎭 ROLE:** Assigns a precise expert persona.
* **🌐 CONTEXT:** Adds specific context placeholders for you to fill in.
* **🎯 TASK:** Rewrites the idea as a clear, multi-part task.
* **📐 OUTPUT FORMAT:** Specifies exactly how the response should be structured.
* **⚙️ CONSTRAINTS:** Adds strict quality guardrails (no hallucinations, no filler words, etc.).

## 🛠️ Tech Stack

- **React 18** (via CDN)
- **Tailwind CSS** (via CDN)
- **Babel Standalone** (for in-browser JSX compilation)
- **Google Gemini API** (REST API)
- **Fonts:** DM Mono & Syne (Google Fonts)

## 📄 License

This project is open-source and available under the [DAKY](LICENSE).
