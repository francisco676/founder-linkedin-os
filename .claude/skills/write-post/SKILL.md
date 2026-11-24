---
name: write-post
description: Write a full LinkedIn post draft in the founder's voice from an idea in workspace/ideas.md, and save it to workspace/posts/. Use when the user types "write post 07", "show me post 07", or asks to draft a post on any topic.
---

# Write a post

Read first: `workspace/voice.md` (the most important file here), `workspace/stories.md`, `workspace/profile.md`, the idea in `workspace/ideas.md`, then `knowledge/post-structure.md`, `knowledge/hooks.md` and `knowledge/formats.md`.

## Which post

- `write post 07` or `show me post 07`: find idea 07. If `workspace/posts/07-*.md` already exists, show it and ask whether they want a new version. Otherwise write it.
- A topic with no number ("write a post about our pricing change"): find the closest idea, or treat it as a new one and add it to `ideas.md`.
- If the idea has a `Needs:` line, ask for that fact first, in one question. If the user doesn't have it, write around it, never invent it.

## Write it

1. **Find the story.** Pull the exact story, win or belief named in the Proof line from `stories.md`. Use their details and their words. The more specific (a date, a number, what someone said), the better.
2. **Pick the shape** from `knowledge/post-structure.md` that fits the format. Their voice file can override it.
3. **Write the body first, the hook last.** Once you know what the post pays off, sharpen the idea's draft hook. Keep it to two short lines above the "see more" cut.
4. **Write like them.** Match `voice.md`: sentence length, how they open and close, words they use, words they never use, emoji and punctuation habits. Read the draft against their sample posts. If it sounds smoother or smarter than they do, roughen it.
5. **Make it scannable.** One idea per line or short paragraph, a blank line between them. Aim for roughly 1,000 to 2,000 characters. LinkedIn cuts off at 3,000.
6. **One ask at the end.** Match it to the funnel stage: top asks for a follow or a specific comment, middle asks for a save or a reply, bottom asks for a DM, a demo or a comment-for-resource. Never two asks.
7. **Check the house rules** in `knowledge/voice-guide.md` (no filler words, no fake numbers, no AI tells).

## Self-check

Before showing it, run the hard gates and the six scores from `knowledge/review-rubric.md` silently. If it would get Revise, fix it and check again, once. Don't show the scorecard unless asked.

## Save and show

Save to `workspace/posts/07-short-title.md` with this layout:

```
# 07 · Title
Pillar · Funnel · Format · Planned for: date or blank

## Post
(the post, exactly as it should be pasted into LinkedIn)

## Other hooks to try
1. ...
2. ...

## Visual
One line: what image to use and why (see knowledge/formats.md)

## Notes
Any [ask: ...] gaps, and anything you assumed
```

Update the idea's status in `ideas.md` to `drafted`.

Show the post in a code block so it's easy to copy, then the two other hooks and the visual line. End with:

> Want changes? Tell me what to fix, or type `review my draft` after you've edited it.

If the user rewrites the hook themselves, keep their hook word for word from then on.
