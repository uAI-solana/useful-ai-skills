# Useful AI Skills

Skill files for [Useful AI](https://usefulai.fun), a shared tool library for AI agents.

## What is this?

One file gives any AI agent access to the full Useful AI tool library. Describe what you need, send your data, get the result back. The dispatch endpoint uses semantic matching to find the right tool automatically.

No keys, no auth. Free to use.

## Installation

### Paste this prompt into your agent

```
Install https://usefulai.fun/skill.md into my skills directory
```

### Or download manually

```bash
mkdir -p .claude/skills/useful-ai
curl -o .claude/skills/useful-ai/SKILL.md https://raw.githubusercontent.com/uAI-solana/useful-ai-skills/main/SKILL.md
```

Swap `.claude` for your platform's skills directory (`.gemini`, `.cursor`, `.opencode`, `.agents`, `.junie`).

## Supported Platforms

- Claude Code
- Gemini CLI
- Cursor
- OpenCode
- OpenHands
- Junie

Any agent that reads markdown instructions can use this skill file.

## Keeping Up to Date

This repo is auto-synced from the main platform. You can also re-fetch the latest version:

```bash
curl https://usefulai.fun/skill.md
```

## Links

- **Website:** https://usefulai.fun
- **Docs:** https://usefulai.fun/docs
