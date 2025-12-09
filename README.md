# 🧬 Dual-Layer Cognitive Architecture

> **Turn your generic AI chatbot into a Senior Expert with structured reasoning.**

Most AI models (ChatGPT, Claude, Gemini) rush to answer with the first thing that comes to mind. This project provides a "System Prompt" and "Knowledge Base" that forces the AI to **stop, think, and choose the right tool** before answering.

## 🧐 How It Works
It uses a strict **Dual-Layer System**:
1.  **Layer 1 (The Boss):** The AI adopts a specific expert persona with hard constraints (e.g., "Senior Architect," "Security First").
2.  **Layer 2 (The Toolkit):** The AI automatically selects **one** of 10 advanced thinking techniques (like *Chain-of-Verification* or *Structured Thinking*) from its library to solve your specific problem.

## 📂 The Files
*   **`instructions.txt`**: The "Operating System." This tells the AI *how* to behave and structure its response.
*   **`techs.txt`**: The "Library." This contains 10 specific templates and examples the AI uses to do the work.

---

## 🚀 Installation Guide

Choose your platform below. You do not need to code; just copy and paste.

### 💎 Google Gemini

**Method A: Public Gem**

https://gemini.google.com/gem/1qIsLlu0ZEkpawNfNRawG5AG4tCILqnBl?usp=sharing

**Method B: Custom Gem (Best for Gemini Advanced)**
1.  Go to **Gem Manager** → **New Gem**.
2.  **Name:** Dual-Layer Agent.
3.  **Instructions:** Paste the content of `instructions.txt`.
4.  **Knowledge:** Click "Add Knowledge" and upload `techs.txt`.
5.  Create and Chat.

**Method C: The Context Paste (Free Users)**
1.  Open a fresh chat.
2.  Copy **ALL** text from `instructions.txt` and paste it.
3.  Type: *"I am now providing your Knowledge Base."*
4.  Copy **ALL** text from `techs.txt` and paste it.
5.  Start asking your questions.

---

### 🟢 ChatGPT (OpenAI)

**Method A: Create a Custom GPT (Best for Plus/Team Users)**
1.  Go to **Explore GPTs** → **Create**.
2.  **Name:** Dual-Layer Agent.
3.  **Instructions:** Copy & paste the full content of `instructions.txt`.
4.  **Knowledge:** Upload the `techs.txt` file.
5.  **Save** and start chatting.

**Method B: Custom Instructions (Free Users)**
*Free accounts have character limits, so we paste the core logic only.*
1.  Click your **Profile Icon** → **Customize ChatGPT**.
2.  **Top Box (What to know):** Paste the content of `instructions.txt`.
3.  **Bottom Box (How to respond):** Paste the first 3 techniques from `techs.txt` (or as many as fit).
4.  **Note:** Since you cannot upload files, if you need a specific technique later, just paste it into the chat manually.

---

### 🟠 Claude (Anthropic)

**Method A: Projects (Best for Claude Pro Users)**
1.  Go to **Projects** → **Create Project**.
2.  **Name:** Dual-Layer Agent.
3.  **Set Custom Instructions:** Paste the content of `instructions.txt`.
4.  **Project Knowledge:** Click "Add Content" and upload `techs.txt`.
5.  Start a chat inside this Project.

**Method B: The "Chat Attachment" Way (Free Users)**
1.  Start a new chat.
2.  Drag and drop **both** `instructions.txt` and `techs.txt` into the chat window.
3.  Type this prompt: *"Read these files. Adopt the persona in instructions.txt and use the library in techs.txt to answer my future questions."*

---


### ⚫ Grok (xAI)

**Method A: Public Project**

https://grok.com/project/faa3a8b1-85f7-4cca-9c9b-a0bb290dae32?tab=sources

**Method B: Custom Project**
1.  Go to the **Grok** tab on X.
2.  Go to **Projects** → **Create Project**.
3.  **Project Instructions:** Paste the content of `instructions.txt`.
4.  **Sources:** Click "Attach files" and upload `techs.txt`.

---

## 🎮 How to Use It
Once set up, you don't need to do anything special. Just ask a normal question.

**User:** *"Should I use Python or Go for a high-frequency trading bot?"*

**The AI's Process (Automated):**
1.  **Layer 1:** Activates "Senior FinTech Engineer" persona.
2.  **Layer 2:** Detects this is a comparison strategy. Selects **Tech 9: Multi-Perspective Prompting**.
3.  **Output:** Delivers a structured analysis covering Latency (Tech), Developer Velocity (Business), and Stability (Risk).

## 📄 License
MIT License. Free to use, modify, and share.

## Special Thanks
Special thanks to Louis Gleeson for first prompting techniques;
https://x.com/aigleeson
