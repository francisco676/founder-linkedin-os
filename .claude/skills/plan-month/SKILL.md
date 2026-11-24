---
name: plan-month
description: Build a 4-week LinkedIn calendar with 3 posts a week from workspace/ideas.md and save it to workspace/calendar.md. Use when the user types "plan my next month" or asks for a content calendar.
---

# Plan the month

Read first: `workspace/strategy.md`, `workspace/ideas.md`, and `workspace/calendar.md` if one exists.

## Steps

1. **Pick the slots.** 4 weeks starting next Monday, using the cadence in `strategy.md` (default Tuesday, Wednesday, Thursday). Use real dates. If the user mentions a holiday, launch or event, plan around it.
2. **Pick 12 ideas** with status `idea`. If fewer than 12 are left, run `post-ideas` in add mode first and tell the user.
3. **Balance each week.** Every week gets posts from at least 2 pillars. Across the month, match the funnel mix in `strategy.md` (with the default mix, that's roughly 5 top, 5 middle, 2 bottom).
4. **Order within the week.** Open the week with the post most likely to travel (top of funnel, best story). Put bottom of funnel posts mid or late week, after a trust post on the same topic where you can, so the reader has a reason to believe the ask.
5. **Never back to back:** two posts of the same format, two contrarian takes, or two posts that use the same story.
6. **Tie to the calendar.** If the user mentioned a launch, event or season (end of quarter, budget season for their buyer), put a relevant idea near it.
7. **Flag gaps.** If a planned idea has a `Needs:` line, list it under "Before you write" so the user can find the number in advance.

## Output

Write `workspace/calendar.md` from `templates/calendar.md`. If a calendar already exists, ask whether to replace it or add the next month below it.

Update each chosen idea in `ideas.md` to `Status: planned`.

Then show the calendar as a compact table: date, idea number, title, pillar, funnel. End with:

> Type `write post 04` to draft the first one. Tip: draft a week at a time, on the Friday before.
