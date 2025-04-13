# 🐤 DuckTyper.ai

**Welcome to [DuckTyper.ai](https://ducktyper.ai) — the official GitHub home of the QuackVerse.**  
We build open-source tools that make AI education productive, practical, and fun for developers.

---

## 🧠 What is DuckTyper?

DuckTyper is a terminal-based AI tutor and command-line companion designed to help developers learn, explore, and build with generative AI tools.

Think of it as your friendly CLI duck:  
- 🧑‍🏫 It **teaches** you new skills through gamified tutorials and inline quizzes.  
- 🛠️ It **runs** developer tools like `QuackPrompt`, `QuackMetadata`, and `QuackTokenScope`.  
- 🔌 It plugs into **QuackCore**, the modular backend infrastructure powering all logic and integrations.

Whether you're analyzing tokenization, upgrading your prompt engineering, or learning how LangGraph works — DuckTyper walks (or waddles) you through it.

---

## 🧰 What is the QuackVerse?

The **QuackVerse** is our ecosystem of lightweight, focused tools — called **QuackTools** — that help developers:
- Learn by building
- Analyze AI behavior
- Automate tedious tasks
- Ship prototypes faster

All QuackTools follow a unified plugin architecture designed to work standalone and inside DuckTyper.  
They’re built to stay under ~600 LOC to remain teachable, testable, and extendable.

Explore the tools:
- [`quacktool-template`](https://github.com/ducktyper-ai/quacktool-template) – The base template for building your tools.
- [`quackprompt`](https://github.com/ducktyper-ai/quackprompt) – Prompt engineering playground.
- [`quacktokenscope`](https://github.com/ducktyper-ai/quacktokenscope) – Tokenizer comparison tool.
- [`quackmetadata`](https://github.com/ducktyper-ai/quackmetadata) – AI metadata extractor for text docs.
- ... and more coming soon!

---

## 🧩 QuackCore

At the heart of everything is [`quackcore`](https://github.com/ducktyper-ai/quackcore):  
A headless, service-oriented backend that handles integrations, CLI I/O, error handling, and LLM logic.

**Use QuackCore if you're:**
- Building your own QuackTool
- Contributing to DuckTyper
- Integrating with external APIs like OpenAI, HuggingFace, or Anthropic
- Working with teaching metadata, badges, or plugin registries

---

## 🧙‍♂️ Learn with Quackster

DuckTyper is more than a CLI — it’s a game-inspired AI education platform.

👾 **Learn by doing**: Every QuackTool is a quest.  
🏆 **Earn XP**: Complete chapters, unlock badges, track your progress.  
📦 **No browser required**: All learning happens in the terminal.

Whether you're a beginner or an AI native developer, DuckTyper helps you master tools by **shipping real code**.

---

## 🚀 Get Started

1. Clone DuckTyper:
   ```bash
   git clone https://github.com/ducktyper-ai/ducktyper
   cd ducktyper
   pip install -e .
