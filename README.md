Here is the updated `README.md`. I have rewritten it to align with the new **Tri-Layer Architecture** (Identity, Logic, Action) defined in `instructions.txt` and integrated the new `tools.txt` library into the installation steps.

***

# 🧬 Cognitive Architecture

> **Turn your generic AI chatbot into a Senior Expert with structured reasoning and tool execution.**

Most AI models (ChatGPT, Claude, Gemini) rush to answer with the first thing that comes to mind. This project provides a **System Prompt** and **Knowledge Base** that forces the AI to **stop, think, filter, and act** using a sophisticated cognitive architecture.

## 🧐 How It Works
It uses a strict **Tri-Layer System** (Identity -> Logic -> Action) followed by a feasibility filter:

1.  **Layer 1: Identity Engine (The Boss)**
    *   **Role:** The AI analyzes your request (including images/docs) and becomes a "Super Squad" of experts.
    *   **Multimodal:** It actively analyzes visual attachments to extract data before forming an opinion.
2.  **Layer 2: Logic Router (The Strategy)**
    *   **Role:** The AI selects a specific **Cognitive Tech** (from `techs.txt`) to draft a plan.
    *   **The Library:** Includes 10 mental models like *Chain-of-Verification* and *Structured Thinking*.
3.  **The Feasibility Filter**
    *   **Role:** An internal step where the AI cuts 50% of the "theoretical fluff" from Layer 2 to ensure the output is actionable.
4.  **Layer 3: Action Engine (The Execution)**
    *   **Role:** If external tools are needed, the AI selects a **Tool** (from `tools.txt`) to finalize the result.
    *   **Toolkit:** Includes Image Generation, Video Creation, Web Search, and Code Interpretation.

## 📂 The Files
*   **`instructions.txt`**: The "Operating System." Defines the 3-layer architecture and the internal execution loop.
*   **`techs.txt`**: The "Strategy Library." Contains 10 specific mental models for Layer 2.
*   **`tools.txt`**: The "Action Library." Contains protocols for triggering external tools for Layer 3.

---

## 🚀 Installation Guide

Choose your platform below. You do not need to code; just copy and paste.

### 💎 Google Gemini

**Method A: Public Gem**

https://gemini.google.com/gem/1qIsLlu0ZEkpawNfNRawG5AG4tCILqnBl?usp=sharing

**Method B: Custom Gem (Best for Gemini Advanced)**
1.  Go to **Gem Manager** → **New Gem**.
2.  **Name:** Cognitive Architect.
3.  **Instructions:** Paste the content of `instructions.txt`.
4.  **Knowledge:** Click "Add Knowledge" and upload **both** `techs.txt` and `tools.txt`.
5.  Create and Chat.

**Method C: The Context Paste (Free Users)**
1.  Open a fresh chat.
2.  Copy **ALL** text from `instructions.txt` and paste it.
3.  Type: *"I am now providing your Knowledge Base."*
4.  Copy **ALL** text from `techs.txt` and `tools.txt` and paste them.
5.  Start asking your questions.

---

### 🟢 ChatGPT (OpenAI)

**Method A: Create a Custom GPT (Best for Plus/Team Users)**
1.  Go to **Explore GPTs** → **Create**.
2.  **Name:** Cognitive Architect.
3.  **Instructions:** Copy & paste the full content of `instructions.txt`.
4.  **Knowledge:** Upload **both** `techs.txt` and `tools.txt`.
5.  **Capabilities:** Enable "Web Browsing," "DALL-E," and "Code Interpreter."
6.  **Save** and start chatting.

**Method B: Custom Instructions (Free Users)**
*Free accounts have character limits.*
1.  Click your **Profile Icon** → **Customize ChatGPT**.
2.  **Top Box (What to know):** Paste the content of `instructions.txt`.
3.  **Bottom Box (How to respond):** Paste the first 3 techniques from `techs.txt` and the tool definitions from `tools.txt` (or as much as fits).

---

### 🟠 Claude (Anthropic)

**Method A: Projects (Best for Claude Pro Users)**
1.  Go to **Projects** → **Create Project**.
2.  **Name:** Cognitive Architect.
3.  **Set Custom Instructions:** Paste the content of `instructions.txt`.
4.  **Project Knowledge:** Click "Add Content" and upload **both** `techs.txt` and `tools.txt`.
5.  Start a chat inside this Project.

**Method B: The "Chat Attachment" Way (Free Users)**
1.  Start a new chat.
2.  Drag and drop **all three files** (`instructions.txt`, `techs.txt`, `tools.txt`) into the chat window.
3.  Type this prompt: *"Read these files. Adopt the architecture in instructions.txt and use the libraries in techs.txt and tools.txt to answer my future questions."*

---

### ⚫ Grok (xAI)

**Method A: Public Project**

https://grok.com/project/faa3a8b1-85f7-4cca-9c9b-a0bb290dae32?tab=sources

**Method B: Custom Project**
1.  Go to the **Grok** tab on X.
2.  Go to **Projects** → **Create Project**.
3.  **Project Instructions:** Paste the content of `instructions.txt`.
4.  **Sources:** Click "Attach files" and upload **both** `techs.txt` and `tools.txt`.

---

## 🎮 How to Use It
Once set up, you don't need to do anything special. Just ask a normal question.

**User:** *"Analyze this attached PDF of Q3 sales and visualize the trend."*

**The AI's Process (Automated):**
1.  **[INIT] Identity:** Activates "Senior Data Analyst" persona. Reads the PDF.
2.  **[THINK] Logic:** Selects **Tech 4: Structured Thinking** to plan the data extraction.
3.  **[FILTER] Feasibility:** Removes fluff, focuses on the data points.
4.  **[ACT] Action:** Triggers **Tool 4: Code Interpreter** to execute Python code that plots the graph.

## 📄 License
MIT License. Free to use, modify, and share.

---

## Special Thanks
* Louis Gleeson for first prompting techniques;
https://x.com/aigleeson

* Emily for inspirations for the instructions;
https://x.com/IamEmily2050
