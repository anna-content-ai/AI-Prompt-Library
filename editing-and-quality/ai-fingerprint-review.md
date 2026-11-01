# AI Fingerprint Review

> **Version:** 1.0
> **Last updated:** November 2026
> **Scope:** Editing AI-assisted drafts so they read as the author's own writing

## Purpose

Find the phrases and patterns that make a draft sound generic, such as stacked adjectives, empty openers, triple lists written out of habit, and closing lines that repeat the introduction. The prompt flags these patterns and proposes concrete edits, while keeping the meaning and the facts unchanged.

This is an editing workflow, not a detection tool. It does not claim to know whether a text was written by AI. Its only goal is to make the text clearer and more specific.

## Use case

Use this prompt when:
- a first draft is accurate but reads as generic,
- you are preparing a post or article that must sound like you,
- an editor needs a quick pass before human editing.

## Input requirements

- the draft text,
- two or three samples of your own writing that you consider typical,
- the words or phrases you never use,
- the audience and channel.

## Prompt

```text
You are a copy editor who makes drafts specific and natural. You do not change facts.

AUTHOR SAMPLES (the voice to match)
[Paste 2–3 short samples of the author's own writing.]

PHRASES THE AUTHOR NEVER USES
[List them, or write "none provided".]

CHANNEL AND AUDIENCE
[For example: LinkedIn post for content marketing managers.]

DRAFT TO REVIEW
[Paste the draft.]

TASK
1. List every instance of the following patterns, quoting the exact words:
   - empty openers ("In today's fast-paced world", "It's no secret that"),
   - vague intensifiers ("truly", "incredibly", "game-changing"),
   - lists of three that add no new meaning,
   - a closing sentence that repeats the opening,
   - phrases from the "never uses" list.
2. For each instance, propose a replacement that is more specific, using only information already in the draft.
3. Rewrite the draft in the author's voice, keeping every fact, number and claim unchanged.
4. Give a short list of anything you could not fix without new information, marked [NEEDS AUTHOR INPUT].

RULES
- Do not add facts, examples, statistics or quotes.
- Do not change a claim's strength (for example, "may" must not become "will").
- Keep the length within 10% of the original unless the author asked otherwise.
- Explain significant structural changes in one sentence each.
```

## Expected output

- a table of flagged phrases with proposed replacements,
- a rewritten draft,
- a list of items needing author input.

## Quality criteria

1. Every fact and claim in the rewrite exists in the original.
2. Replacements are specific, not just different words.
3. The rewrite sounds like the author's samples, not like a new generic voice.
4. The list of flagged items is complete for the categories above.

## Human review

- Compare the rewrite with the original line by line for facts and claim strength.
- Read it aloud. If a sentence still sounds like a template, rewrite it yourself.
- Remove any phrase you would not say in conversation, even if it is grammatically correct.

## Example (illustration)

Original: "In today's fast-paced digital landscape, content is truly king."
Flagged: empty opener, vague intensifier, cliché.
Proposed: "Most teams publish more than they can check." (Only if the draft already makes this point. Otherwise mark [NEEDS AUTHOR INPUT].)
