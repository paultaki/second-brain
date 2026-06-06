<div align="center">

# 🧠 Second Brain

### Give your AI a long-term memory. Built for people who talk more than they type.

You dictate, paste, or drop in whatever you've got. **Claude Code** cleans it, links it, and files it into a plain-text vault you own, so every project starts with your full context, not a blank page. No plugin, no install, no forty commands to learn. One prompt and a two-minute conversation.

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

## Why this one?

There are great second-brain projects out there, most are powerful plugins with dozens of commands. This one is built around a different bet:

- **Voice-first.** It is made for people who dictate. It takes a raw voice-to-text dump, cleans it, flags anything it might have misheard before treating it as your words, and links it in. Talk, do not type.
- **Dead simple.** One prompt, no install, no command list. If you can paste and answer a few questions, you can run it. Your non-technical friend can too.
- **It writes back in your voice.** Most second brains are about recall. This one closes the loop: it can learn how you write and draft as you, not as generic AI.
- **It forgets on purpose.** The memory prunes insights you stop referencing, so it stays sharp instead of bloating into a junk drawer.
- **Yours, in plain text.** No server, no account, no lock-in. Keep the folder and you keep everything.

## Quickstart

> The 60-second version.

1. **Get the tools.** Install [Claude Code](https://www.anthropic.com/claude-code). Optionally install [Obsidian](https://obsidian.md) (free) to *see* your notes connect, though it is just plain text either way.
2. **Open the prompt.** Copy everything inside the box in **[PROMPT.md](PROMPT.md)**.
3. **Paste it into Claude Code** (opened in the folder where you want your brain to live) and answer the questions.

That's it. The prompt handles the rest, the folders, the rules, the daily habit, and the connections.

## What you'll end up with

- **Voice capture.** Dump a raw voice-to-text note and Claude cleans it, flags anything it might have misheard before quoting you, and files it. Built for [Wispr Flow](https://wisprflow.ai) and any dictation tool.
- **A self-organizing vault** in a simple [PARA](docs/how-it-works.md#the-shape-para) layout (Projects, Areas, Resources, Archive) plus a `Daily` folder and a `Private` folder Claude will never read.
- **An operating contract** (`CLAUDE.md`) that tells Claude exactly how to behave in your vault: what to link, what to never touch, never to invent a quote. See the [template](templates/CLAUDE.md).
- **Auto-linking.** New notes connect to your real projects, people, and topics with `[[wikilinks]]`, so the graph grows itself.
- **Drafts in your voice.** Optionally teach it how you write, then have it draft posts, emails, and replies that sound like you, not like AI.
- **A save rhythm you choose:** daily notes, weekly summaries, monthly roll-ups, run on a schedule or on a one-word command.
- **A [dream cycle](docs/how-it-works.md#the-memory-the-dream-cycle) that forgets on purpose:** Claude reads back through your notes, finds the patterns you keep circling, saves the best ones (in your own words, with sources) into a playbook you approve, and lets unused insights fade so it stays sharp.

A few commands you'll actually use:

| Say this | Claude does this |
|---|---|
| `start today's note` | opens today's dated note and helps you capture what's on your mind |
| `clean this voice note` | takes a raw dictation dump, tidies it, flags possible mishearings, files and links it |
| `import this` | files a pile of documents and links them into the graph |
| `draft in my voice` | writes a post, email, or reply that sounds like you (after it learns your voice) |
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

---

<div align="center">

If this helped, a ⭐ makes it easier for the next person to find.

</div>
