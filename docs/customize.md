# Customize and go deeper

The basic build is deliberately simple. Once it feels useful, here is where to take it. None of this is required.

## Teach it your voice

If you want anything Claude drafts (posts, emails, replies) to sound like you and not like generic AI, give it a voice profile.

- Collect 10 to 30 things you have actually written: emails, posts, messages, essays.
- Put them in a folder like `30-Resources/Voice/`.
- Ask Claude: *"Read these and write me a short voice profile: how I open, how I close, sentence length, words I use and avoid, my register in different situations. Save it as `VOICE.md` and use it whenever you draft as me."*

From then on, ask it to "draft this in my voice" and it will pull from the profile.

## Run it on a schedule

If you want summaries to happen without you remembering, schedule the command.

- **Mac / Linux (cron):** ask Claude to add a cron entry that runs your weekly summary, for example every Sunday evening. It can write the crontab line for you.
- **Windows (Task Scheduler):** ask Claude to create a scheduled task that runs the same command on your chosen day.

If you would rather stay in control, skip scheduling and just keep the one-word commands. Many people prefer triggering the dream cycle by hand, because they have a good sense of when curation is due.

## Tune the dream cycle

The default dream cycle is conservative on purpose. You can adjust it by editing your `CLAUDE.md`:

- **Scope:** run it over the last week, a single topic, or one folder, not the whole vault at once. Smaller slices give sharper results.
- **The bar:** raise or lower what counts as worth keeping. A higher bar means a smaller, denser playbook.
- **Forgetting:** change how long an unreferenced insight survives before it fades to an archive. Forgetting is a feature, it keeps the playbook current.
- **Sensitive folders:** keep personal areas opt-in, so they are only ever read when you explicitly include them.

## Add more inputs

The system gets better with more raw material. Common additions:

- **Read-later highlights** (Readwise, Reader, Kindle) synced into `30-Resources/`. Treat synced files as read-only and make derived notes that link to them.
- **Meeting notes and transcripts** dropped into `Daily/`.
- **Chat exports** from Claude or ChatGPT, so your thinking-out-loud becomes searchable memory.

## Keep transcripts honest

If you dictate, voice-to-text will occasionally mishear you, especially on silence, music, or unclear audio. The setup treats dictated notes as drafts. A simple habit keeps your memory trustworthy: when Claude wants to quote a dictated note as your exact words, it flags it, and you confirm the line is accurate before it becomes a cited quote.

## Make it yours

The whole system is plain text and one `CLAUDE.md` contract. There is nothing to break. Read the contract, change a rule, add a folder, rename a command. It is your brain. Shape it.
