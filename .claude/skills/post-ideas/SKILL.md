---
name: post-ideas
description: Write numbered LinkedIn post ideas into workspace/ideas.md, each with pillar, funnel stage, format, a draft hook and the story or proof it uses. Runs after build-strategy (20 ideas), or when the user asks for more ideas.
---

# Post ideas

Read first: `workspace/strategy.md`, `workspace/stories.md`, `workspace/profile.md`, `workspace/voice.md`, `knowledge/hooks.md`, `knowledge/formats.md`.

## First run: 20 ideas

Write `workspace/ideas.md` from `templates/ideas.md` with 20 ideas numbered 01 to 20.

## Add mode

If `ideas.md` already exists, keep every idea as it is and append new ones, continuing the numbering. Default to 10 new ideas unless the user asked for a number.

## Rules for every idea

1. **Built on something real.** Every idea uses a specific story, win, loss, belief or customer trigger from `stories.md` or `profile.md`. Name it in the Proof line. If you can't point to one, drop the idea.
2. **One idea, one point.** If the hook needs "and", it's two posts.
3. **Spread the mix.** Match the funnel mix in `strategy.md` across the 20. Every pillar gets at least 4 ideas. No more than 3 ideas in a row from the same pillar or format.
4. **Mix the formats** from `knowledge/formats.md`: story and lesson, contrarian take, framework, list, before and after, customer result, behind the scenes, objection answered.
5. **Mix the hook types** from `knowledge/hooks.md`. Don't use the same type more than 5 times in 20.
6. **The hook is a draft.** Write it in their voice, under about 60 characters for the first line, and check it answers: who is this for, what's it about, what do I get. It will get sharpened in `write-post`.
7. **Mark gaps.** If an idea is strong but missing a number, write it in and flag it: `Needs: the exact churn number`.

## Format of each idea

```
## 07 · Short working title
- Pillar: name
- Funnel: Top | Middle | Bottom
- Format: format name
- Hook: "First line of the post"
- Proof: which story, win or belief it uses, in a few words
- Status: idea
```

Status moves through `idea`, `planned`, `drafted`, `posted`. Other skills update it.

## Finish

Show the 20 titles as a numbered list with their funnel stage, then say:

> Your 20 ideas are in `workspace/ideas.md`. Type `write post 01` to draft one, or `plan my next month` to turn them into a calendar.

Point out the 3 ideas you'd post first and why (usually: the strongest story, the sharpest belief, and one bottom of funnel post).
