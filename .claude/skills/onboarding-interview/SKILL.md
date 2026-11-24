---
name: onboarding-interview
description: Interview a founder about their business, buyer, stories and voice, and write workspace/profile.md, voice.md and stories.md. Use when the user types "start", "start my LinkedIn strategy", or "refresh".
---

# Onboarding interview

Goal: learn enough about the business and the person that every later post sounds like them and speaks to the people who buy from them. Takes 10 to 15 minutes.

## Step 1: open

Say something close to this, in your own words:

> Let's set up your LinkedIn. I'll look at your website, then ask you about 10 questions, one or two at a time. The more specific your answers, the better your posts. Stories and real numbers beat polished summaries. What's your company website?

If `workspace/profile.md` already exists and the user typed `start`, ask whether they want to start over or `refresh`. Don't overwrite without a yes.

## Step 2: read the website

Fetch the homepage. Then try `/pricing`, `/customers`, `/case-studies` and `/about`. Skip any that 404, don't mention the misses.

From what you find, note: what they sell, who it's for, the pricing model, any named results or customer types, and the words the site uses for the problem. Then tell the user in three or four lines what you understood, and ask what's wrong or missing. Websites are often out of date or written by someone else, so treat the founder's answer as the truth.

## Step 3: the interview

Ask these one or two at a time. Skip any the website or earlier answers already covered. Where it helps, offer three or four options plus "or something else", because picking is easier than answering from scratch. When an answer is short or vague, ask for an example before moving on. When it's long, pull on the most interesting thread.

1. **Who signs the contract?** Job title, company size, industry. Then: who else has to say yes?
2. **What's happening in their world the week they get in touch with you?** The trigger, not the category. ("We just failed an audit", not "compliance".)
3. **What do they try before you, or instead of you?** Spreadsheets, an agency, a competitor, hiring someone, doing nothing.
4. **Why do deals stall or die?** The two or three objections you hear most.
5. **What do you believe about your market that most competitors don't?** Push for a real position someone could disagree with. If they agree with the consensus, that's fine, move on.
6. **Tell me three stories from building the company.** Offer prompts: the first customer, a near-death moment, a hire that went wrong, a decision you'd make differently, a customer call you still think about.
7. **Your best wins, with numbers.** Revenue, time saved, customers, a result for a client. Ask which ones are safe to share publicly.
8. **A loss or mistake, with numbers if you have them.** Lost deal, failed launch, wasted spend. Founders who share these get trusted faster.
9. **Who do you most want reading your posts?** Buyers only, or also investors, hires, partners? Rank them.
10. **Paste 3 to 10 of your past posts, or anything you've written** (emails, a memo, a newsletter). If they have nothing, ask them to answer this out loud as if to a friend: "What's the most annoying thing about your industry?" Their answer becomes the voice sample.
11. **Anything off limits?** Customers you can't name, numbers you can't share, topics like politics or competitors.
12. **How often can you realistically post, and how much time can you give it?** Default plan is 3 posts a week.

Stop at 8 if the answers are rich and the user is short on time. Say "two more quick ones" when you're near the end.

## Step 4: write the files

Copy each template from `templates/` and fill it:

- `workspace/profile.md` from `templates/profile.md`
- `workspace/stories.md` from `templates/stories.md`. Every story, win, loss and belief goes here in their words, with a "safe to share" flag.
- `workspace/voice.md` from `templates/voice.md`, following `knowledge/voice-guide.md`. Quote real lines from their pasted posts or interview answers. Never describe their voice in words they didn't give you evidence for.

Then summarise in five lines: who they sell to, the trigger, their sharpest belief, their best story, and how they sound. Ask "Anything wrong?" Fix what they flag.

Then go straight to the `build-strategy` skill, then `post-ideas`. Don't wait for a new command.

## Refresh mode

When the user types `refresh`:

1. Read `workspace/profile.md`, `workspace/stories.md` and `workspace/ideas.md`.
2. Ask 4 to 6 questions: what happened since last time (wins, losses, customer calls, launches, hires), any new belief or changed opinion, any new posts to paste for voice, and whether the buyer or offer changed.
3. Append new entries to `stories.md` with today's date. Update `profile.md` and `voice.md` only where something changed.
4. Offer to add 5 to 10 new ideas built on the new stories (run `post-ideas` in add mode).
