# How it works

A second brain is not magic and it is not a new app. It is four simple ideas stacked together. Understanding them helps you trust it, and lets you bend it to your own needs.

## The shape: PARA

Your vault is organized with [PARA](https://fortelabs.com/blog/para/), a simple, durable structure that works for almost anyone:

```
00-Inbox        new, unsorted notes land here
10-Projects     things you are actively working on
20-Areas        ongoing parts of your life and work
30-Resources    reference material and highlights
40-Archive      done or inactive
Daily           one note per day
Private         the folder Claude never reads
```

The numbers keep the folders in order. The point is not perfect filing, it is that everything has an obvious home, so capture stays frictionless and recall stays predictable.

## The connections: plain text and wikilinks

Every note is a plain text file. Notes link to each other with `[[wikilinks]]`, the same way Wikipedia pages link. Those links form a **graph**.

This is the part that makes it a brain instead of a drawer. When you open one note, the AI does not just see that file, it sees its neighborhood: the projects it touches, the people it mentions, the decisions it connects to. Context travels with any single note.

A few **hub notes** (sometimes called MOCs, "maps of content") sit on top and act as connective tissue, gathering everything that links back to a topic. Open the hub for a project and you have the whole thread.

The setup keeps the graph clean on purpose: real things (projects, people, topics) get linked; generic tools (the app, the browser, the model) do not, because linking everything to everything is the same as linking nothing.

## The rules: a `CLAUDE.md` contract

At the top of your vault is a `CLAUDE.md` file. It is a short, plain-language contract that tells Claude how to behave in your space. A good one says, in effect:

- This vault is my words and memory. Read it, help me, do not rewrite it without asking.
- Never read the `Private` folder, for any reason.
- Never invent a quote or a fact. Cite the note it came from. If unsure, say so.
- Link related notes. Keep the graph clean.
- Keep a plain, honest style.

This is what keeps the AI consistent and careful across hundreds of sessions. See the [template](../templates/CLAUDE.md) for a full example.

## The memory: the dream cycle

Capturing notes is easy. The hard part is turning a growing pile into something that stays useful. That is what the **dream cycle** does.

Every so often (you trigger it, or schedule it), Claude reads back through a slice of your recent notes and:

1. **Finds the patterns** you keep returning to, the ideas, decisions, and lessons that show up again and again.
2. **Writes them up in your own words**, with the source note quoted as evidence. No inventing.
3. **Shows you candidates to approve.** Nothing enters your curated memory without your okay.
4. **Forgets on purpose.** Insights you never reference again fade out over time, so the curated layer stays current instead of bloating.

The result is a small, high-signal **playbook** that sits on top of your raw notes: the distilled version of how you actually think and work. The name is a nod to how the design mirrors memory research on how minds consolidate during sleep.

## The inputs

Anything you have written is fuel:

- emails
- documents
- notes and memos
- voice transcriptions (if you dictate)
- blog posts and articles
- chat exports from Claude or ChatGPT

You drop them in, and Claude files and links them. The more you feed it, the more it knows about you, and the better its recall and its drafts become. It compounds.

## Why it stays trustworthy

- **It is plain text on your own disk.** No server, no account, no telemetry. You can read every file yourself, and leave any time by just keeping the folder.
- **It is grounded.** Curated insights cite their sources, so you can always trace a claim back to something you actually said.
- **It is bounded.** The `Private` folder and opt-in sensitive areas mean there are places the AI simply does not go.
