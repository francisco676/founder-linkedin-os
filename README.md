# Founder LinkedIn OS

A LinkedIn strategist that runs inside Claude Code. It interviews you about your business, learns how you talk and who you sell to, and writes your first 20 post ideas. Then it plans your month, drafts posts and reviews your drafts.

## Who it's for

Founders and B2B execs who want customers from LinkedIn, not just likes.

## Setup (2 minutes)

1. Install Claude Code: https://docs.claude.com/en/docs/claude-code/overview
2. Clone this repo and open it:

```
git clone <this repo's URL>
cd founder-linkedin-os
claude
```

3. Type `start`.

Claude asks for your website, reads it, then interviews you (about 10 questions, 10 to 15 minutes). Have a few of your past posts ready to paste if you have any.

## Commands

| Type | What happens |
| --- | --- |
| `start` | Reads your website, interviews you, builds your profile, voice, strategy and 20 post ideas |
| `ideas` | Adds more ideas to your list |
| `plan my next month` | A 4-week calendar, 3 posts a week, picked from your ideas |
| `write post 07` | A full draft of idea 07 in your voice |
| `review my draft` | Scores a draft and gives a verdict, Revise or Pass, with specific fixes |
| `refresh` | A short re-interview to add new stories and wins |

## What it creates

All in `workspace/`:

- `profile.md`: your company, offer, buyer and objections
- `voice.md`: how you actually talk, the words you use and never use
- `stories.md`: your stories, wins, losses and beliefs from the interview
- `strategy.md`: 3 to 4 content pillars, funnel mix, cadence, what to stop posting
- `ideas.md`: numbered post ideas with pillar, funnel stage, format, hook and proof
- `calendar.md`: your monthly plan
- `posts/`: one file per draft

## Privacy

Everything stays on your machine in `workspace/`, which is git-ignored, so your business details and drafts won't get committed by accident. The only web requests it makes are to read your own website. (Like any Claude Code project, your conversation is sent to Claude to generate replies.)

## Credit

Built by Francisco Gost, partner at RallyUp, from the playbook behind 21.3M+ impressions for B2B founders and execs. Weekly letter on organic growth: franciscogost.com

MIT licensed.
