# Founder Not The Blocker: Autonomous Queue Driving Protocol

> **An open-source AI engineering protocol from [We Build for Good](https://webuildforgood.com)**  
> *Stop being an exhausted ticket dispatcher. Let autonomous AI drive.*

---

## Overview

`founder-not-the-blocker` is an operational protocol for solo founders and small engineering teams working with autonomous AI agents (Claude Code, Cursor, Antigravity, OpenAI Codex).

It prevents the common trap where an AI pauses every ten minutes to ask for permission on trivial decisions, turning the human founder into an operational bottleneck.

---

## The Core Rule

1. **Reversible decisions** (code, CSS, refactoring, tests) are decided by default: the AI announces its course of action and proceeds unless told to stop.
2. **Consequential decisions** (money, external communications, credentials, legal text) are pre-computed into single-click decision packets.

---

## Installation

### For Claude Code
```bash
git clone https://github.com/We-Build-For-Good/skill-founder-not-the-blocker.git ~/.claude/skills/founder-not-the-blocker
```

### For Cursor
```bash
mkdir -p .cursor/skills
git clone https://github.com/We-Build-For-Good/skill-founder-not-the-blocker.git .cursor/skills/founder-not-the-blocker
```

### For Antigravity / Open Agent Skills
```bash
mkdir -p .agents/skills
git clone https://github.com/We-Build-For-Good/skill-founder-not-the-blocker.git .agents/skills/founder-not-the-blocker
```

---

## License

MIT License. Developed and maintained by [We Build for Good](https://webuildforgood.com).
