---
name: review-draft
description: Score a LinkedIn post draft against the review rubric and return a verdict of Revise or Pass with specific line-level fixes. Use when the user types "review my draft", pastes a draft and asks for feedback, or asks to check a file in workspace/posts/.
---

# Review a draft

Read first: `knowledge/review-rubric.md`, `workspace/voice.md`, `workspace/profile.md`, `workspace/stories.md`.

## Get the draft

- If the user pasted a post, review that.
- If they named a number ("review post 07"), read `workspace/posts/07-*.md`.
- If they just typed `review my draft` with nothing else, ask them to paste it.

## Score it

1. Run the **hard gates** from the rubric. Any failure means the verdict is Revise, whatever the scores.
2. Score the **six dimensions** from 0 to 10, using the rubric's descriptions. Be honest. A score of 8 should mean something.
3. Check the hook on its own: read only what shows above "see more" (about two lines on a phone). Does it say who it's for, what it's about and what the reader gets?
4. Check against their voice: compare to the sample lines in `voice.md`. Flag any word from their "never" list.
5. Check every number and claim against `stories.md` and `profile.md`. Flag anything you can't trace to them: "Where's the 40% from? If it's real, keep it. If not, cut it."

## Verdict

- **Pass**: every hard gate passes, no dimension below 6, total 45 or more out of 60.
- **Revise**: anything else.

## Output

Use exactly this layout:

```
Verdict: Revise | Pass      Score: 42/60

Hard gates
✓ One clear point
✗ One ask (there are two: "follow me" and "book a call")
...

Scores
Hook            6/10
Voice           8/10
Clarity         7/10
Rhythm          5/10
Proof           9/10
Ask             7/10

Top fixes (max 3, most important first)
1. Line 4: "In today's fast-moving landscape..." is throat-clearing. Cut it and start with line 5.
2. ...

What's working
- ...
```

Every fix quotes the line it's about and says exactly what to do. "Make the hook stronger" is not a fix. "Swap line 1 for the number in line 9: '11 of our first 12 customers churned'" is.

Then ask: "Want me to apply these fixes?" If yes, rewrite only what the fixes cover. Keep their hook unless a fix is about the hook and they agree. If the draft came from `workspace/posts/`, save the new version there and keep the old one under a `## Previous version` heading.
