# Index Second Brain — Claude Instructions

Read this at the start of every session in this folder.

## Before you do anything

1. Read `about-company.md` so you know who and what you're working for.
2. If the task involves writing anything in the company's voice, read `voice-and-brand.md` first.

## First-run check

This brain ships blank. Before your first real task in a new session, check whether the foundation files are filled in.

Open `about-company.md` and look for this marker at the top:

```
<!-- ONBOARDING:UNFILLED -->
```

- If the marker is still there, setup isn't done. Say: *"This brain hasn't been set up yet. Want me to run a quick onboarding so I actually know your company? Just say yes."* Don't start until they agree. Don't nag more than once per session.
- If the user says **"run onboarding"** or **"set up the brain"** at any time, follow `ONBOARDING.md` from the top.
- Once both files are filled and the marker is gone, never mention onboarding again.

## How to behave

- Answer first, explain second. No filler.
- Follow the tone and rules in `about-company.md` and `voice-and-brand.md`.
- If unsure what the user wants, ask one clear question instead of guessing.

## When ideas land in 01-ideas/

Don't act on them unless the user asks. When the user says **"process the inbox"**, read everything in `01-ideas/inbox.md`, group related notes, clean each one up, and file them into the right folder:

- `04-wiki/` — evergreen knowledge the team looks things up in
- `02-projects/` — anything tied to active work with a finish line
- `03-decisions/` — key decisions worth recording with their reasoning
- `05-resources/` — reference material being collected

Tell the user what you're about to move and where before you do it. Wait for the go-ahead.

After processing, clear `01-ideas/inbox.md` back to its default state — just the header and instructions, no old notes.

## When saving a decision

File it in `03-decisions/` with a clear, dated filename — for example `2026-06-29-chose-stripe-over-paddle.md`. Include:
- What was decided
- Why (the reasoning, tradeoffs considered)
- Who was involved
- Date

Decisions are the most valuable thing in the brain. Never delete them — archive instead.

## When a project finishes or pauses

Move it from `02-projects/` to `06-archive/`. Confirm what you moved. Never delete — archive.

## When something new is saved in 02-projects/

Use a clear, dated filename — for example `2026-06-29-new-onboarding-flow.md`.

## When something about the company changes

If the user tells you something new — new hire, new product, pivot, rebrand — update `about-company.md` or `voice-and-brand.md` directly. Confirm what you changed.

## The safety rule

Before you move, overwrite, or delete any file, show the plan and wait for the go-ahead. Always. No exceptions.
