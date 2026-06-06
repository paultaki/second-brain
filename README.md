<div align="center">

# 🧠 Second Brain

### Give your AI a long-term memory.

A plain-text knowledge vault that **Claude Code** reads, connects, and builds on, so every project starts with your full context instead of a blank page.

[![License: MIT](https://img.shields.io/badge/License-MIT-7c6cf0.svg)](LICENSE)
[![Built for Claude Code](https://img.shields.io/badge/built%20for-Claude%20Code-d97757.svg)](https://www.anthropic.com/claude-code)
[![Works with Obsidian](https://img.shields.io/badge/works%20with-Obsidian-8b7cf6.svg)](https://obsidian.md)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-3fb950.svg)](CONTRIBUTING.md)

![Demo](assets/demo.gif)

**[▶ Watch the 90-second walkthrough](https://github.com/paultaki/second-brain/releases/latest)**

</div>

---

## What this is

A **second brain** is a folder of plain notes that an AI can read, remember, and build on. You write things down once. From then on Claude has your context: your projects, your decisions, your voice. New work starts from everything you already know.

This repo is one thing: **[a prompt](PROMPT.md)**. You paste it into Claude Code, it asks you a handful of questions about your setup, and then it builds the whole system for you, customized to you. No two are identical, but every one ends up as a working, self-organizing memory.

It works on **Mac, Windows, or Linux**, with **any note app** (or none yet), and **with or without** a voice-to-text tool.

## Quickstart

> The 60-second version.

1. **Get the tools.** Install [Claude Code](https://www.anthropic.com/claude-code). Optionally install [Obsidian](https://obsidian.md) (free) to *see* your notes connect, though it is just plain text either way.
2. **Open the prompt.** Copy everything inside the box in **[PROMPT.md](PROMPT.md)**.
3. **Paste it into Claude Code** (opened in the folder where you want your brain to live) and answer the questions.

That's it. The prompt handles the rest, the folders, the rules, the daily habit, and the connections.

## What you'll end up with

- **A self-organizing vault** in a simple [PARA](docs/how-it-works.md#the-shape-para) layout (Projects, Areas, Resources, Archive) plus a `Daily` folder and a `Private` folder Claude will never read.
- **An operating contract** (`CLAUDE.md`) that tells Claude exactly how to behave in your vault: what to link, what to never touch, never to invent a quote. See the [template](templates/CLAUDE.md).
- **Auto-linking.** New notes connect to your real projects, people, and topics with `[[wikilinks]]`, so the graph grows itself.
- **A save rhythm you choose:** daily notes, weekly summaries, monthly roll-ups, run on a schedule or on a one-word command.
- **An optional [dream cycle](docs/how-it-works.md#the-memory-the-dream-cycle):** Claude reads back through your notes, finds the patterns you keep circling, and saves the best ones (in your own words, with sources) into a playbook you approve. Unused insights fade over time so it stays current.

A few commands you'll actually use:

| Say this | Claude does this |
|---|---|
| `start today's note` | opens today's dated note and helps you capture what's on your mind |
| `import this` | files a pile of documents and links them into the graph |
| `summarize my week` | reads the last 7 days and writes one honest summary |
| `run a dream cycle` | surfaces the patterns worth keeping, for you to approve |

## How it works

The whole design is in **[docs/how-it-works.md](docs/how-it-works.md)**. The short version:

- **Plain text + wikilinks** make a graph. Open one note and Claude gets its whole neighborhood.
- **MOC / hub notes** act as connective tissue so context travels with any single file.
- **The `CLAUDE.md` contract** keeps the AI consistent, careful, and grounded.
- **The dream cycle** turns a pile of notes into curated, cited memory, and forgets what stops mattering.

New here? Start with the friendly **[setup walkthrough](docs/setup.md)**. Want more power later? See **[customize.md](docs/customize.md)** (voice profiles, scheduling, tuning).

## Privacy and safety

This is built privacy-first, and that is not an afterthought:

- **A `Private` folder Claude will never read**, for any reason, even if a later instruction seems to ask. It exists so you can write freely.
- **No invented quotes.** Claude cites the note a fact came from. If it is unsure, it says so.
- **Your machine, your files.** Everything is plain text on your own disk. Nothing here phones home. There is no server, no account, no telemetry.
- **Sensitive areas are opt-in.** Personal folders are off by default and only read when you explicitly include them.

## Customize it

You do not edit config files. **The prompt customizes itself by asking you.** Different note app, no voice tool, Windows instead of Mac, want monthly summaries but not weekly, want the dream cycle off for now, it adapts to every answer and builds accordingly. See [docs/customize.md](docs/customize.md) to go deeper after the basics feel useful.

## FAQ

**Do I need Obsidian?** No. The vault is plain text. Obsidian just gives you the graph view and a nice editor. Any folder works.

**Do I need to be technical?** No. You paste a prompt and answer questions in plain language.

**Does it send my notes anywhere?** No. It runs locally through Claude Code against files on your own machine.

**What if I already have notes?** Even better. Point the prompt at them and it organizes and links what you have.

**Is this only for Claude?** The prompt is written for Claude Code, which can read and write your files. The *ideas* (PARA, wikilinks, an operating contract, a dream cycle) work with any capable AI, but the turnkey setup assumes Claude Code.

## Why I built this

I talk more than I type, so I dictate. Over seven months that turned into thousands of notes and well over a million words. The problem was never capture, it was recall. This is how I made all of it usable by my AI: not a chatbot with amnesia, but a partner that remembers what I am building and picks up where I left off. I packaged it so anyone can have the same thing in an afternoon.

## Contributing

Ideas and improvements are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) and the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

[MIT](LICENSE). Use it, change it, share it.
