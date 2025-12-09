# Specialized AI Agent: Dual-Layer Cognitive Architecture

This repository hosts the **DUAL-LAYER COGNITIVE ARCHITECTURE** for a specialized AI agent, designed to enhance reasoning through structured personas and prompting techniques. It makes the full instruction set (from `instructions.txt`) and knowledge base of 10 prompting techniques (from `techs.txt`) publicly available for developers, researchers, and AI enthusiasts.

## Overview
The architecture operates in two layers [Layer 1 and Layer 2 from instructions.txt]:

- **Layer 1: Identity Engine (Technique 1 - MANDATORY)**: Analyzes domain, adopts a persona (e.g., "Senior Domain Expert with 20+ Years experience"), and sets 3 immutable rules. This defines the "Operating System" for every interaction.
- **Layer 2: Logic Router**: Selects ONE secondary technique from a table of 9 options (Tech 2-10) based on user intent (e.g., Fact Checking → Tech 2: Chain-of-Verification).

Followed by an **Execution Loop** (Init → Select → Filter → Output) and a strict **OUTPUT FORMAT** with sections like Active Persona, Logic Applied, etc. [Full details in instructions.txt].

The knowledge base includes **10 Prompting Techniques** (Tech 1-10 from techs.txt), each with templates and examples for advanced AI interactions:
- Tech 1: Role-Based Constraint Prompting [Template and example in examples/tech1-role-based.md].
- Tech 2: Chain-of-Verification (CoVe) [Template and example in examples/tech2-cove.md].
- ... (Tech 3-10 similarly modularized for easy access).

## Why This Repo?
- **Public Accessibility**: Exact replicas of source materials for transparency.
- **Modularity**: Mirrors the architecture's layered design—fork and adapt for your AI agents.
- **Use Cases**: Integrate into LLMs for better outputs in domains like coding, strategy, or creative tasks [Derived from technique selection table in instructions.txt].

## Getting Started

1. Open `instructions.txt` for the custom instructions and `techs.txt` for the knowledge base.

2. Integrate into AI Platforms: Copy-paste key content from these files into each platform's custom instructions

   ### Google Gemini
   - Go to gemini.google.com > Explore Gems > New Gem
   - Name it "Dual-Layer Agent".
   - In instructions: Paste full content from instructions.txt and Upload the techs.txt to knowledge base section.
   - Save and chat with the Gem.

   ### ChatGPT (OpenAI)
   - Go to Settings > Personalization > Custom Instructions
   - Enable customization.
   - In "What would you like ChatGPT to know about you?": Paste the Layer 1 Identity Engine from instructions.txt.
   - In "How would you like ChatGPT to respond?": Paste the Layer 2 Logic Router table and Output Format from instructions.txt, plus Tech 1-10 from techs.txt (or top 5 if token-limited).
   - Save and test in a new chat.

   ### Claude AI (Anthropic)
   - Create a custom Skill: In Claude dashboard, go to Skills > New Skill<grok-card data-id="135d06" data-type="citation_card"></grok-card><grok-card data-id="101a6c" data-type="citation_card"></grok-card>.
   - Prepare a folder with `instructions.txt` and `techs.txt` as files; add a README.md summarizing the framework.
   - Zip the folder and upload via the interface.
   - Assign the Skill to a project or conversation for persistent use.


   ### Grok (xAI)
   - Visit grok.x.ai > Settings > Customize Grok<grok-card data-id="1725e1" data-type="citation_card"></grok-card><grok-card data-id="724dd0" data-type="citation_card"></grok-card>.
   - In custom fields: Add "What to know": Layer 1 from instructions.txt; "How to respond": Full framework and techniques from techs.txt (summarize if over limit).
   - Select Custom mode and save for all sessions.

3. Experiment: Ask a vague question like "Should I use Python or Go for my backend?"

Expected Result: It should adopt a "Backend Architect" persona (Layer 1) and automatically select Technique 9 (Multi-Perspective) or Technique 4 (Structured Thinking) to give you a nuanced answer.


## Contributing
- Suggest new techniques via Issues.
- Any suggestions are welcome.

## License
MIT—freely use, modify, and share.

Questions? Open an Issue!
