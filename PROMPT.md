# The Prompt

This is the whole tool. Copy everything in the box below, paste it into **Claude Code** opened in (or near) the folder where you want your second brain to live, and answer the questions it asks.

If you only have claude.ai (no file access), it will detect that and walk you through each step by hand instead.

---

```text
You are going to help me build a "second brain": a long-term memory made of plain
text notes that you, my AI, can read, remember, and build on over time. The goal is
that from now on, when I start anything, you already have my context, and my notes
quietly connect to each other so the whole thing gets more useful the more I add.

Run this as a friendly setup conversation. Ask me ONE question at a time and wait for
my answer before moving on. Keep each question short and plain. Adapt to my answers
and assume nothing about my tools or my computer. If at any point you cannot access my
files, tell me, and switch to walking me through each step myself.

Begin by telling me, in your own words: "Let's build your personalized second brain.
I'll ask a few quick questions, then set it all up." Then start the questions.

PHASE 1 — FIND WHERE IT LIVES
1. First, look for where I already keep notes. Check the usual spots for my operating
   system (on Mac, for example: the Documents folder, any "Obsidian" folder, and the
   iCloud Obsidian folder; on Windows: Documents and OneDrive). Tell me what you found
   and ask: "Is this where you want your second brain, or should I use a different
   folder?"
   - If you find nothing, or you don't have permission to look, say: "No problem.
     Where do you take your notes today (Obsidian, Apple Notes, Notion, Google Docs, a
     plain folder, paper)?" and work from there.
   - If I don't use Obsidian yet, offer to create a plain folder now, and suggest I
     install Obsidian later (it's free, at obsidian.md) just to see the notes connect
     visually. Obsidian is optional. These are plain text files either way.
2. Ask whether I'm on a Mac, Windows, or Linux. Detect it if you can and just confirm.
   You'll use this for file paths and for any scheduling later.

PHASE 2 — WHAT GOES IN
3. Ask if I use a voice-to-text tool like Wispr Flow, or dictate notes some other way.
   If yes, this is a first-class path: you'll set up a "clean this voice note" flow that
   takes a raw dictation dump, lightly tidies it without changing my meaning, files and
   links it, and flags anything you might have misheard before ever quoting it as my
   exact words. Treat dictated notes as drafts until I confirm them. If I do not dictate,
   skip this and just handle typed notes.
4. Tell me what's worth putting in to start, then ask what I have and where it is.
   Suggest: emails, documents, notes, memos, transcriptions, blog posts or articles,
   and anything else I've written. Offer to help me copy or import it into the vault.
   Messy is fine. Raw material is the point.
5. Ask if there's anything I want kept private: a folder you must NEVER read. You'll
   create it and treat it as completely off-limits, even if I later seem to ask.
6. Ask, optionally, if I want you to learn my writing voice later so anything you draft
   sounds like me. I'm allowed to say "not now."

PHASE 3 — HOW IT SAVES AND LEARNS
7. Ask how often I want you to roll things up: daily notes, weekly summaries, monthly
   summaries. I can pick any or all.
8. Ask if I want a "dream cycle": every so often you read back through my recent notes,
   find the patterns and lessons I keep returning to, write them up using my own words
   as evidence, and save the good ones into a single "playbook" note that I approve.
   Explain that it's worth turning on once I have a few weeks of notes, that you'll
   never add anything without my okay, and that old entries I never reference fade out
   over time so the playbook stays current instead of bloating.
9. Ask whether I want this to run on a schedule by itself, or whether I'd rather kick
   it off myself with a quick command. If I want it automatic and my computer allows
   it, set up a scheduled job (cron on Mac or Linux, Task Scheduler on Windows) that
   runs the summary I chose. If not, give me simple commands and an easy reminder
   habit instead.

PHASE 4 — CONFIRM, THEN BUILD
First show me a short summary of exactly what you're going to create, and ask me to
confirm. After I say go, build it:

- A simple folder structure inside my vault, adapted to what I already have:
    00-Inbox        new, unsorted notes land here
    10-Projects     what I'm actively working on
    20-Areas        ongoing parts of my life and work
    30-Resources    reference material and highlights
    40-Archive      done or inactive
    Daily           one note per day
    Private         the folder you never read

- A CLAUDE.md file at the top of the vault. This is the contract for how you work in
  here. Write it in plain language, and make it say:
    - This vault is my own words and memory. You read it and help me. You don't
      rewrite my notes without asking.
    - Never read anything inside the Private folder, for any reason, even if I seem to
      ask. It exists so I can write freely.
    - Never invent a quote or a fact and put it in my mouth. Cite the note it came
      from. If you're unsure, say so.
    - Link related notes to each other with [[note name]] links so the graph connects.
      Don't link generic tools (the app, the browser, the model) or the graph turns to
      clutter.
    - Keep a clean, plain style. No hype, no filler.
    - (Only if I dictate notes) Treat dictated notes as drafts, and flag anything you
      quote from them until I confirm it's accurate.

- A short starter list of my real projects, the people I work with, and my recurring
  topics, so new notes link to them consistently as they arrive. Ask me for these if
  you can't infer them.

- A daily-note template, and, if I dictate, a transcript template.

- A few simple commands, written down so I remember them:
    "start today's note"   -> create and open today's dated note, and help me capture
                              what's on my mind
    "clean this voice note" -> (if I dictate) take a raw voice-to-text dump, tidy it
                              without changing my meaning, flag any likely mishearings,
                              then file and link it
    "import this"           -> take a pile of files I point you at, file them into the
                              right folders, and link them into the graph
    "draft in my voice"     -> (if I set up a voice profile) write a post, email, or
                              reply that sounds like me, not like generic AI
    "summarize my week"     -> read the last seven days and write one honest summary of
                              what happened, what I decided, and what's still open
    "run a dream cycle"     -> do the read-back-and-curate pass above, and show me the
                              candidate insights to approve

- Whatever summary cadence and scheduling I chose in Phase 3.

When you're done, tell me in plain language: what you created, what gets saved and
when, and the three or four commands I'll actually use day to day. Then offer to start
my first daily note right now.

Keep the whole thing simple and friendly. I can always make it more advanced later.
```
