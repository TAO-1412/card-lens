# card-lens

A website for comparing debit and credit cards across banks in Vietnam — currently in the PMF validation stage, not yet built.

## The problem

Vietnamese banks frequently change card fee schedules ("biểu phí") and terms without clearly notifying cardholders, and most consumers rely on banker consultants, Facebook groups, or TikTok reviews to pick a card — often ending up with one that costs more than it's worth, or locked into a single bank's ecosystem without realizing better options exist elsewhere. Existing comparison sites don't cover all banks and aren't reliably up to date on fees/terms.

## Status

**Pre-build.** This repo currently holds research and planning docs, not product code. The immediate goal is validating which user pain point to lead the MVP with before writing a single line of the product itself.

## What's been validated so far

See [`rcgv-segment-research.md`](./rcgv-segment-research.md) for the full writeup. Short version: within the first target community (RCGV, a ~100k-member Vietnamese credit-card Facebook group), two demand segments exist —

1. **Fee-pain segment** — cardholders who resent unannounced fee/ToS changes
2. **Multi-card optimizer segment** — collectors tracking promo/cashback changes across cards they already hold

Research (post/comment engagement analysis + a competitive/legal check) points to leading the MVP with **segment 1**: a neutral fee/ToS-change watchdog. It's the smaller segment by raw engagement, but the cleaner signal, and it sits on a trust gap the main incumbent (sosanhthe.vn, ad-funded by the same banks) structurally can't close.

## Objective

Beyond the product itself, this is a learning project: vibe-coding a real product with Claude Code, designed to handle real concurrent user traffic (target: 200 simultaneous users without degrading the experience), with an explicit goal of learning product architecture, GTM, and funnel/analytics tracking end to end. If it works, it doubles as a portfolio piece for Growth / Product Marketing / GTM Engineer roles.

## Approach

Spec-driven development, using gstack + gbrain workflows, plus marketing psychology and UI/UX design passes as the product takes shape.

## Docs in this repo

- [`card-lens.md`](./card-lens.md) — original project brief: objective, initial idea, framework
- [`rcgv-segment-research.md`](./rcgv-segment-research.md) — segment/competitor research and the current MVP direction
- [`Autonomous apllication Q3.md`](./Autonomous%20apllication%20Q3.md) — unrelated: an AI-workflow sample for a separate exercise, kept in this repo but not part of the product
