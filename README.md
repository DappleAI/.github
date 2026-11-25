# **DappleAI**

**The adaptive orchestration layer between people and large language models.**

Most people and teams can't turn an LLM into something they can rely on: results depend on how the question is asked, context gets lost, and every model needs a different approach. DappleAI closes that gap. A short guided interview captures what the user knows, packages it as structured context, and runs a repeatable workflow on whichever model fits the job. We built it over two years with input from 100+ customer interviews, and open-sourced the core.

- **Guided, not prompted.** Users pick a playbook and answer a short survey. They never have to write a prompt.
- **Model-agnostic.** The same workflow runs on Claude, a local Mistral model, or a self-hosted model, by changing one configuration.
- **Built on two patent-pending methods.** Dual Phase Context Injection (DPCI) and Domain Directed Execution and Task Packet Creation (DDE).
- **Auditable by design.** Append-only, versioned playbooks, so every change and every run can be traced.

## **Research**

Index of papers and reports: `research`

- [The DappleAI Litepaper - The Adaptive Orchestration Layer](https://drive.google.com/file/d/1ZCSckVl3HXk9MGz_Eq6oDzvK2SQ8D7mi/view?usp=sharing)
- [Technical Thesis - A Multilayer Technical Stack for AI 2.0](https://drive.google.com/file/d/1gHs3BaBVtd7B7O_lyAbFQ4cGW4KgQppM/view?usp=sharing)
- [Friction by Design: A Structural Analysis of AI’s Usability Crisis](https://drive.google.com/file/d/1b39S7Zpx2QXuShHl6llQYkXiUg6v0hg8/view?usp=sharing)
- [The Imperfect, Fast-Growing Artificial Intelligence Market: An Analysis of the Current Waves](https://drive.google.com/file/d/1vrIJpnHKfXDfhKIY4LPWu384_QnSmFEX/view?usp=sharing)
- [Context Engineering for the Database Layer: Structuring SQL for Planners, Piplines and LLMS](https://drive.google.com/file/d/1nuw5_KklklKRt5YzBa4mW0w4vwaY6GY5/view?usp=sharing)

## **Core methods (patent pending)**

- **Dual Phase Context Injection (DPCI):** the process of selecting, scoring, and strategically delivering only the most pertinent information to an LLM based on the task at hand, the user’s role, and the evolving needs of the interaction.
- **Domain Directed Execution and Task Packet Creation (DDE):** DDE is a careful packager, it gathers the right ingredients, packs them into a neat Task Packet, and passes that packet to a different system (DPCI) 

Inventors: Ebony Belhumeur[, other inventors exactly as on the filings]. How they're implemented: dapple-core › Core methods

## **Open source**

- `dapple-core`: Rust engine for structured, model-agnostic LLM workflows (Postgres, Axum, OpenAPI 3.1, sandboxed Nushell execution). Apache-2.0.
- `research`: the papers and reports above, with summaries

## **Try it**

- **Quick start:** run dapple-core locally in minutes: setup guide
- **Contribute:** good first issues · Discussions
- If it's useful, a ⭐ on dapple-core helps others find it.

## **Team**

Ebony Belhumeur, Operations Lead & Co-Founder · [Name], [Title] · [Name], [Title] Radical Ventures Founders Program · NVIDIA Inception [confirm wording]
