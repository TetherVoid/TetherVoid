<h1 align="center">tether</h1>

<p align="center"><em>Software for the things you'd rather keep to yourself.</em></p>

<p align="center">
  I build at the point where technology, money and law meet.
</p>

---

## Now: Chaonance

Most finance apps tell you what you spent. **Chaonance asks what you decided, and whether you were right.**

It's a local-first personal-finance tool, currently in design. It has a balance sheet, cash-flow runway and stress tests, plus decision memos: write down a prediction and how confident you are, come back later, and get scored on how well calibrated you were. Money is stored as exact integer amounts, your data never leaves your device, and it will never give you investment advice.

## Shipped: [Mindful](https://github.com/TetherVoid/Mindful)

Students write down the hardest parts of their week, so Mindful is built on one rule: **what you write stays yours.** It's a live wellbeing journal for mood, habits and CBT-style thought records.

- row-level security on every table, with the access rules covered by database tests
- consent first: nothing is shared until you say so
- nothing a user writes ever reaches the AI, the logs or a URL

## How I build

AI agents write code fast, and mistakes ship just as fast. So mine work inside guardrails: hooks that block pushes and remote database calls, a verify step that must pass before any commit, and a written approval step before anything touches production.

I'd rather ship a small change I can trust than a big one I can't.

## Toolbox

`JavaScript` · `React` · `Vite` · `Supabase` · `Postgres + RLS` · `Vercel` · `Git`

## What pulls me in

Corporate law, M&A, private equity, valuation and deal structures, and the question of how people make decisions when the stakes are real.

## Say hello

Open an issue or discussion on [Mindful](https://github.com/TetherVoid/Mindful).
