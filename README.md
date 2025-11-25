# Homebrew Tap for AIask

This is the official Homebrew tap for [AIask](https://github.com/Hermithic/aiask), an AI-powered command line assistant that turns plain English into shell commands.

## Installation

```bash
brew tap Hermithic/aiask
brew install aiask
```

## Quick Start

After installation, configure your LLM provider:

```bash
aiask config
```

Then use it:

```bash
aiask "list all files larger than 100MB"
```

## Features (v2.0)

- 🗣️ **Natural Language** — Describe what you want in plain English
- 🔍 **Explain Mode** — Understand what any command does: `aiask explain "tar -xzvf file.tar.gz"`
- 📜 **History** — Track and search command history: `aiask history`
- 📝 **Templates** — Save and reuse prompts: `aiask save my-cmd "do something"`
- 💬 **REPL Mode** — Continuous conversation: `aiask interactive`
- 🛡️ **Safety** — Warnings for dangerous commands
- 📥 **Stdin** — Pipe output for analysis: `cat log | aiask --stdin "what's wrong?"`

## Supported Providers

- Grok (xAI)
- OpenAI (GPT-4o)
- Anthropic (Claude)
- Google Gemini
- Ollama (100% local)

## Shell Completions

Completions are automatically installed for Bash, Zsh, and Fish.

## More Information

See the [main repository](https://github.com/Hermithic/aiask) for full documentation.

## License

MIT
