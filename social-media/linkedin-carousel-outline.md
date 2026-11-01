# LinkedIn Carousel Outline

> **Version:** 1.0
> **Last updated:** November 2026
> **Scope:** Multi-slide PDF carousels for LinkedIn (and Instagram carousel copy)

## Purpose

Turn one verified idea into a carousel outline where every slide has one job. The output is a slide-by-slide plan with copy, not finished design. The designer or editor builds the visuals afterwards.

## Use case

Use this prompt when:
- a post contains several steps, comparisons or a framework,
- a single text post would be too dense to scan,
- you want a repeatable structure for educational content.

## Input requirements

- the central message in one sentence,
- the steps, criteria or examples to include (verified),
- the number of slides (typically 6–8 on LinkedIn),
- the target reader and the action you want (save, comment, book a call, read the newsletter).

## Prompt

```text
You are a content strategist who designs LinkedIn carousels for marketing professionals.

CENTRAL MESSAGE
[One sentence.]

CONTENT TO USE (verified only)
[Paste steps, criteria, examples. Do not add anything else.]

TARGET READER
[Role, seniority, the problem they recognise.]

NUMBER OF SLIDES
[6–8]

ACTION AT THE END
[Save the document / comment with a word / visit a link / book a call.]

TASK
Create the carousel outline:

1. Cover slide: a headline of at most 8 words that states the benefit or the problem. No emojis.
2. Slides 2 to N-1: one idea per slide. For each slide give:
   - headline (max 8 words),
   - body (max 25 words),
   - a note on what visual element fits (chart, list, before/after, single quote from the editor's own notes).
3. Final slide: a summary of the steps and the call to action from the list above.
4. Post caption: 2–3 short sentences that explain why the document is worth opening.

RULES
- One message per slide. If a slide needs two ideas, split it.
- Keep the progression logical: problem, method, example, takeaway.
- Do not invent statistics, sources or results.
- Mark any slide that depends on a claim the editor must verify with [VERIFY].
```

## Expected output

- cover slide copy,
- numbered slide plan with headline, body and visual note,
- closing slide and call to action,
- caption,
- a list of [VERIFY] markers.

## Quality criteria

1. Each slide makes sense on its own when swiped quickly.
2. The cover promises what the last slide delivers.
3. Text is short enough to read on a phone without zooming.
4. Every example and number is traceable to a source.
5. The action is specific ("save this checklist"), not generic ("let me know your thoughts").

## Human review

- Check every [VERIFY] marker before the design stage.
- Count the words on each slide. Cut anything that repeats the headline.
- Read the slides in order without the caption. The story should still work.

## Example (illustration)

Central message: "A repurposing workflow needs a fact-check step for every channel, not just the original article."

Slide 3 headline: "Check each version against the source"
Body: "Rewrites drift. Compare every LinkedIn, newsletter and video script with the original and flag any new claim."
Visual note: a simple three-column diagram, one column per channel.
