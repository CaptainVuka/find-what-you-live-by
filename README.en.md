<p align="right"><b>English</b> · <a href="README.md">中文</a></p>

# find-what-you-live-by

> A Claude Skill that helps you extract 1–3 personal principles from your own life experiences, inspired by Benjamin Franklin's 13 virtues method.

---

## What is this

**Find What You Live By** is a Claude Skill that runs a 30–60 minute structured conversation to help you extract 1–3 personal principles from your own life experiences.

It's not a chatbot, not a coach, not a therapist. It's closest to **a patient mirror** — helping you see what you already know but haven't articulated.

The conversation goes through four stages:

1. Collecting 2–3 recent moments that still sting
2. Letting you find the patterns yourself
3. Distilling those patterns into 1–3 principles in your own words
4. Checking for conspicuous absences, then helping you practice

## See it in action

To get a feel for what this conversation looks like, read a sample: [examples/sample-conversation.md](./examples/sample-conversation.md). The example is in Chinese — it's a 12-turn compressed version showing the core mechanics.

## Why

Most self-improvement tools fail the same way: **they push someone else's wisdom on you, then wonder why you quit in three weeks**.

Franklin's method (designed in his 20s) was different — he extracted 13 principles from his **own repeated mistakes**, each translated into specific, daily-checkable behaviors. He used it his whole life, admitted some he never mastered, but said: *"By the endeavour, I was a better and a happier man than I otherwise should have been."*

This Skill recreates that — not by giving you Franklin's thirteen, but by helping you find your own.

## Installation

### Option 1: Download the `.skill` file

1. Download [`find-what-you-live-by.skill`](./find-what-you-live-by.skill)
2. Install it in Claude.ai or Claude Code
3. Find a quiet 30–60 minutes and tell Claude: *"I want to find my own principles"* — or any similar expression

### Option 2: From source

Clone this repo and place `SKILL.md` in your Claude client's skills directory.

## When to use

This Skill is for you if any of these resonate:

- You want direction in life but can't articulate what
- You feel like you're drifting, no anchor
- You keep repeating the same mistakes and want to understand why
- You just went through something significant (breakup, layoff, career change) and want real reflection
- You want to do a year-end review but don't know where to start
- You know Franklin's 13 virtues method and want an AI-guided version

## What this Skill does NOT handle

For your safety, this conversation is **not appropriate** for:

- Acute mental health crises (self-harm, suicidal ideation, severe depression)
- Serious trauma (especially recent or ongoing)
- Active symptoms of mental illness
- Uncontrolled addiction

If you're experiencing any of these, **please seek professional support**.

## Design philosophy

- **Agency > tooling**: Claude doesn't decide your principles, it helps you articulate them.
- **Less > more**: Start with 1–3 principles, not 13.
- **Honest > polished**: A rough but true version beats a polished but fake one.
- **Extract from failure, not receive from wisdom**: Your principles come from your own repeated stumbles.
- **Record failure, not success**: Franklin's notebook tracked where he fell short — that's how he saw his patterns.

## About the author

Designed by **WokaCaptain (乌卡船长)** — a builder with a background in philosophy, committed to building better skills and ecosystems.

For collaboration, search **乌卡船长** on Xiaohongshu (Little Red Book) or WeChat Official Accounts.

## License

MIT License — see [LICENSE](./LICENSE).
