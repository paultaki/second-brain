# What a built vault looks like

After you run the prompt, your folder ends up something like this. Yours will differ based on your answers, this is just to make it concrete.

```
my-second-brain/
├── CLAUDE.md                      the operating contract (how the AI behaves here)
├── 00-Inbox/                      capture target, usually empty
├── 10-Projects/
│   ├── Home Renovation.md         a hub note for the project
│   ├── Book Draft.md
│   └── Side Business.md
├── 20-Areas/
│   ├── Health.md
│   ├── Finances.md
│   └── Family.md
├── 30-Resources/
│   ├── Voice/                     (optional) writing samples for your voice profile
│   ├── Highlights/                synced read-later highlights
│   └── entities.md                the auto-link registry
├── 40-Archive/                    finished or inactive notes
├── Daily/
│   ├── 2026-06-01.md
│   ├── 2026-06-02.md
│   └── 2026-06-03.md
├── Weekly/
│   └── 2026-W23.md                "summarize my week" output
├── Playbook.md                    curated insights from the dream cycle (you approve each one)
└── Private/                       the AI never reads this
```

## How it reads day to day

A **daily note** is where raw thinking lands:

```markdown
---
date: 2026-06-02
projects: [Home Renovation]
tags: [daily]
---

# Tuesday, June 2, 2026

## On my mind
Got three contractor quotes back. The middle one is the only one who
actually understood the load-bearing wall question.

## Decisions
- Going with [[Alex Rivera]] for the [[Home Renovation]]. Their quote was
  fair and they answered the structural question without dodging.
```

Because `[[Alex Rivera]]` and `[[Home Renovation]]` are links, opening either hub note later shows this decision in context. That is the graph doing its job.

A **playbook entry** (from the dream cycle) is distilled and cited:

```markdown
## Pick the vendor who engages the hard question

When choosing between vendors, I consistently trust the one who engages
the difficult detail head-on rather than the cheapest bid.

> "The middle one is the only one who actually understood the load-bearing
>  wall question."
> — [[Daily/2026-06-02]]
```

Small, grounded, and yours. That is the whole idea.
