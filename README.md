# TetherVoid

I build software, and I'm drawn to the places where technology, money and law meet.

## What I'm working on

**Chaonance** is a local-first personal-finance tool, currently in design. Instead of another expense tracker, it focuses on decisions: a balance sheet, cash-flow runway, stress tests, and decision memos where you write down a prediction and a confidence level, then review it later and score how well calibrated you were. Money is stored as exact integer amounts, and your data stays on your device. It will never give investment advice.

## Shipped

**[Mindful](https://github.com/TetherVoid/Mindful)** is a live wellbeing journal for students, covering mood, habits and CBT-style thought records. The people who use it write sensitive things, so privacy is built in as a feature:

- row-level security on every table, with access rules covered by database tests
- explicit consent before anything is shared
- nothing a user writes ever reaches the AI, the logs or a URL

## How I build

I work with AI coding agents and put guardrails around them: hooks that block pushes and remote database calls, a verify step that has to pass before any commit, and a written approval step before anything touches production. I'd rather ship a small change I can trust than a big one I can't.

## Stack

JavaScript, React, Vite, Supabase (Postgres, RLS), Vercel, Git

## Interests

Corporate law, M&A, private equity, valuation and deal structures.

## Contact

The best way to reach me is to open an issue or discussion on [Mindful](https://github.com/TetherVoid/Mindful).
