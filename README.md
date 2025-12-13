# 🧬 Cognitive Architecture (The "Super Squad" Protocol)

> **"Think first. Squad up. Get it done."**

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Type](https://img.shields.io/badge/Type-System%20Prompt-green) ![Model](https://img.shields.io/badge/Compatible%20with-Gemini%20%7C%20GPT--4%20%7C%20Claude-orange)

## 📖 Overview

This repository houses the **Dual Layer Cognitive Architecture**, a sophisticated system prompt designed to transform standard Large Language Models (LLMs) into a disciplined **"Super Squad" of experts**. 

Unlike standard prompts that encourage immediate answers, this architecture forces the AI to decouple **Reasoning** from **Generation**. It implements a strict 9-step protocol to ensure every response is analyzed, strategized, and fact-checked before a single word of the final answer is written.

## 🚀 Key Features

The core logic (found in `instructions.txt`) enforces the following behaviors:

### 1. 🎭 Dynamic Persona Adoption ("The Squad")
The AI does not act as a generic assistant. It analyzes the task and adopts the specific persona (or team of personas) required.
* *Coding task?* $\rightarrow$ **Senior Principal Engineer (20+ Years Exp)**
* *Design task?* $\rightarrow$ **Veteran UX/UI Designer**
* *Complex task?* $\rightarrow$ **A full "Super Squad" of cross-functional experts**

### 2. 🧠 Dual-Layer Reasoning
The architecture enforces a "Silent Thought" phase before the "Response" phase:
1.  **Analysis Layer:** Deconstructs the user's request, identifying implicit constraints and required proofs.
2.  **Strategy Layer:** Determines if the task needs sequential (A $\rightarrow$ B) or parallel (A + B $\rightarrow$ C) logic.
3.  **Execution Layer:** Only generates content after the reasoning is complete.

### 3. 🛠️ Tool-First Philosophy
* **Proactive Execution:** The model is instructed to *prefer* calling tools (Search, Code Execution) over asking the user for clarification.
* **Real Data > Hallucination:** It prioritizes real-time data fetching over imaginative gap-filling.

### 4. 🛡️ Intelligent Persistence
* **Resilience:** The agent is programmed to retry transient errors automatically.
* **Adaptability:** If a tool fails, it formulates a *new* strategy rather than repeating the same failed call.

## 📂 Repository Contents

* **`instructions.txt`**: The core System Prompt. This is the "source code" of the cognitive architecture.
* **`README.md`**: Documentation (You are here).

## ⚡ How to Use

This is a **System Instruction**, not a Python library. You "install" it by feeding it to your AI model's context.

### Option 1: API / Developer Usage
If you are building an app using OpenAI API, Anthropic API, or Google Gemini API, paste the content of `instructions.txt` into the `system` parameter.

```python
# Example pseudo-code for OpenAI/Gemini
messages = [
    {"role": "system", "content": open("instructions.txt").read()},
    {"role": "user", "content": "Analyze this stock market data."}
]
````

### Option 2: ChatGPT / Gemini Advanced

1.  Open **Custom Instructions** (ChatGPT) or **System Instructions** (AI Studio).
2.  Copy the raw text from `instructions.txt`.
3.  Paste it into the "How would you like ChatGPT to respond?" or "System Instructions" field.

## 📝 The 9-Step Protocol

The architecture strictly enforces these steps:

1.  **Adopt Personas** (Expert level)
2.  **Analyze Request** (Beyond literal words)
3.  **Prefer Tools** (Don't be lazy)
4.  **Identify Missing Info** (Stop and ask if critical)
5.  **Use Real Information** (No speculation)
6.  **Prefer Visualization** (Charts/Graphs \> Text)
7.  **Check Info Availability** (Policies, history, tools)
8.  **Persistence** (Intelligent retries)
9.  **Inhibit Final Response** (Reasoning phase first)

## 🤝 Contributing

Contributions are welcome\! If you have improvements for the prompting logic (e.g., better chain-of-thought triggers or stricter constraints), feel free to open a Pull Request.

## 📜 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

-----

*Inspired by the need for more reliable, agentic AI behavior.*

