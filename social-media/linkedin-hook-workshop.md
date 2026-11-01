# LinkedIn Hook Workshop

> **Version:** 1.0
> **Last updated:** November 2026
> **Scope:** LinkedIn posts, carousel covers and short-form video openings

## Purpose

Generate and test several hooks for one LinkedIn post before choosing the draft. A hook is the first one or two lines a reader sees before the "see more" cut. Most of the post's value is lost if the hook is weak, so this prompt separates the hook decision from the rest of the writing.

The workshop does not write the full post. It produces hook options, explains the reasoning for each, and flags any claim that needs checking.

## Use case

Use this prompt when:
- you have a finished insight, example or data point and need a strong opening,
- the first draft opens with background instead of the point,
- you want to compare a question, a contrarian statement and a concrete observation.

## Input requirements

- the core insight in one or two sentences,
- the supporting facts or example (only verified information),
- the target reader (role, seniority, pain point),
- the desired tone,
- any words or claims that must not appear.

## Prompt

```text
You are an editor who writes LinkedIn openings for experienced marketing and content professionals.

CORE INSIGHT
[Write the insight in one or two sentences.]

SUPPORTING MATERIAL
[Paste verified facts, examples or data. Write "none provided" if there are none.]

TARGET READER
[Role, seniority, the problem they recognise.]

TONE
[For example: direct, calm, slightly provocative, warm.]

DO NOT USE
[List banned phrases, claims or topics. Write "none" if there are none.]

TASK
Write 6 hook options, two lines or fewer each, in 6 different styles:
1. A question the reader will want answered
2. A contrarian statement
3. A concrete observation from practice
4. A short, surprising fact (only if it appears in the supporting material)
5. A specific mistake the reader has probably made
6. A plain statement of the outcome

For each option give:
- the hook,
- the reason it should work for this reader,
- the risk (for example: sounds clickbait-like, makes an unverified claim, too vague).

Finally, recommend the strongest option and say why in three sentences or fewer.

RULES
- Do not invent facts, numbers, quotes or results.
- Do not use "Unpopular opinion", emojis or engagement bait such as "Comment YES below".
- Keep each hook readable on a phone without the "see more" click.
- The second line may add context or an invitation, but must not repeat the first.
```

## Expected output

- six labelled hook options with reasons and risks,
- one recommendation,
- a list of any hook that depends on a claim needing verification.

## Quality criteria

1. The hook makes the central point clear, or raises a question the post answers.
2. It fits within the first two lines on a phone screen.
3. It matches the audience's real problem, not a generic one.
4. It makes no claim the supporting material does not back up.
5. It sounds like a person, not a template.

## Human review

- Check every factual statement against your own source.
- Read the hook aloud. If it sounds like a slogan, rewrite it in your own words.
- Confirm the hook matches what the post actually delivers. A promise the body does not keep damages trust.

## Example (illustration)

Core insight: "AI drafts are fast, but the editor's job is now to verify, not to write."

A possible hook from option 2: "The best AI-assisted content I see is not written faster. It is checked more carefully."

Reason: it takes a stance, reflects a real editorial concern and invites the reader to continue. Risk: "the best ... I see" is a personal observation, so it should only be used if it reflects real experience.
