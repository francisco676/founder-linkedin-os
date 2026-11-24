# Review rubric

Used by `review-draft` and as a silent self-check by `write-post`. A post passes when every hard gate passes, no dimension scores below 6, and the total is 45 or more out of 60.

## Hard gates

Pass or fail. One failure means Revise.

1. **One clear point.** You can say what the post argues or teaches in one sentence.
2. **Only you could post it.** Ask: could a competitor's founder publish this unchanged? If yes, it fails. It needs a story, number or belief that belongs to this person.
3. **No made-up facts.** Every number, result and quote traces back to the user. Anything that doesn't is flagged.
4. **Doesn't open on the company.** The first line isn't the company or product name, and the post doesn't read as an ad.
5. **One ask.** Zero or one call to action, never two.
6. **Length.** Under LinkedIn's 3,000 character limit. Under about 700 characters needs a reason (a deliberate one-liner).
7. **Nothing off limits.** No topic, name or number the user marked as off limits in `profile.md` or `stories.md`.

## Six dimensions (0 to 10 each)

### Hook
Does the text above "see more" earn the click?
- 9 to 10: specific, drops the reader into a moment or a claim, makes clear who it's for and what they get.
- 6 to 8: clear and relevant but a little general, or slow by a line.
- 3 to 5: names a topic instead of a moment. Could open a hundred other posts.
- 0 to 2: throat-clearing, a cliché, or an announcement.

### Voice
Does it sound like them, per `workspace/voice.md`?
- 9 to 10: sentence length, openers, closers, vocabulary and punctuation match their samples. Could pass as theirs to a colleague.
- 6 to 8: mostly them, one or two habits missing or one word they'd never use.
- 3 to 5: generic professional tone with a few of their words sprinkled in.
- 0 to 2: doesn't sound like them at all.

### Clarity
Does every sentence earn its place?
- 9 to 10: cut any line and something's lost. No filler, no hedging, no "it's important to note".
- 6 to 8: one or two lines could go.
- 3 to 5: a third of the post is setup or repetition.
- 0 to 2: the point takes most of the post to arrive.

### Rhythm
Is it easy to read on a phone?
- 9 to 10: short paragraphs with blank lines, sentence lengths vary, no wall of text, no run of choppy fragments.
- 6 to 8: mostly good, one dense block or one stretch that all sounds the same.
- 3 to 5: same-length paragraphs all the way down, or long blocks.
- 0 to 2: a wall of text, or nothing but fragments.

### Proof
Is the point backed by something real and specific?
- 9 to 10: a specific story, number, name (where safe), date or quote from the user.
- 6 to 8: real but a little vague ("a customer told us").
- 3 to 5: general claims, examples anyone could give.
- 0 to 2: no proof, or proof that looks invented.

### Ask
Does the ending fit the funnel stage and get a response?
- 9 to 10: one ask that fits the stage, or a sharp closing line. Any question is specific enough to answer in one sentence.
- 6 to 8: right kind of ask, slightly generic.
- 3 to 5: "What do you think?" or "Thoughts?"
- 0 to 2: no ending, or a pile of asks.

## AI tells to flag

These make a post read as machine-written. Flag each one you find, quote it, and give the fix.

- Throat-clearing openers: "In today's world", "Let's talk about", "Here's the thing"
- The "it's not X, it's Y" seesaw, unless it carries a specific number or moment
- Three short fragments in a row for drama ("No plan. No team. No money.")
- Lists of three where two would do, used in every paragraph
- Announcing the insight instead of stating it: "Here's what I learned", "The lesson?"
- Rhetorical questions the writer answers in the next line
- Words from the avoid list in `knowledge/voice-guide.md`
- Em dashes, unless `voice.md` shows the user uses them
- Emojis as bullet points on every line, unless that's their style
- Hashtag blocks at the end

## How to write a fix

Quote the line. Say what's wrong in a few words. Give the replacement or the exact action.

Bad: "Tighten the middle."
Good: "Lines 6 to 8 say the same thing three ways. Keep line 7, cut 6 and 8."
