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
1. Clone: `git clone https://github.com/[your-username]/dual-layer-ai-agent.git`
2. Read core docs: Start with `docs/reasoning.txt` for the framework, then `docs/techs.txt` for techniques.
3. Experiment: Use examples/ folder to test prompts in your AI setup.

## Contributing
- Suggest new techniques via Issues (align with Layer 2 table).
- Ensure all PRs cite specific sections from CONTEXT [Per constraints in techs.txt examples].

## License
MIT—freely use, modify, and share.

Built from original uploads: instructions.txt (architecture) + techs.txt (techniques). Questions? Open an Issue!
