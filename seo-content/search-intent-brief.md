# Search Intent Brief

> **Version:** 1.0
> **Last updated:** November 2026
> **Scope:** SEO content planning, article briefs and on-page structure

## Purpose

Create a content brief for one search query that starts from user intent, not from keyword volume. The brief defines what the reader is trying to do, what the page must answer, and how the structure should support that. It also includes the metadata and internal links that an editor needs to publish the page.

Keyword research tools and live search results must be checked by the editor. This prompt works from the query and the material you provide.

## Use case

Use this prompt when:
- you plan an article or landing page around a query,
- an existing page ranks for the wrong intent (for example, a guide where buyers want a product page),
- you need a consistent brief for a writer.

## Input requirements

- the target query and up to five related queries you have checked,
- the search results you reviewed (titles and page types only),
- the business goal of the page,
- the verified facts you can use,
- the target language and market.

## Prompt

```text
You are an SEO content strategist. You plan pages around search intent and do not invent data.

TARGET QUERY
[Main query]

RELATED QUERIES (checked by the editor)
[List up to five, or write "none provided".]

TOP RESULTS REVIEWED (title and page type only)
[For example: "Guide – blog post", "Tool page – landing page".]

BUSINESS GOAL
[For example: newsletter sign-up, consultation booking, reader trust.]

VERIFIED FACTS AVAILABLE
[List them, or write "none provided".]

LANGUAGE AND MARKET
[For example: Polish, Poland.]

TASK
Produce a brief with these sections:

1. Search intent: informational, commercial, navigational or transactional. Justify in two sentences using the reviewed results.
2. Reader question: the one question the page must answer first.
3. Required sections: an H2 outline (5–7 headings) that covers the questions the reader will ask next. Do not add sections that serve only keyword density.
4. Facts to include: only items from the verified list. Mark any gap as [NEEDS SOURCE].
5. Metadata:
   - title tag (max 60 characters),
   - meta description (max 155 characters),
   - URL slug suggestion.
6. Internal links: which types of existing pages should link here and why. Use placeholders if the site structure is unknown.
7. Content to avoid: intent mismatch, thin sections, duplicated headings.

RULES
- Do not invent search volumes, rankings or competitor data.
- Do not promise a ranking outcome.
- If the reviewed results suggest a different intent than the business goal, say so and recommend a choice.
```

## Expected output

- intent classification with justification,
- reader question,
- H2 outline,
- list of facts to include and gaps,
- title tag, meta description and slug,
- internal link suggestions,
- risks to avoid.

## Quality criteria

1. The intent classification matches the pages that already rank.
2. The H2 outline answers the reader's next questions in order.
3. Metadata lengths are within the limits.
4. No statistic or competitor claim appears without a source.

## Human review

- Check the search results yourself. The brief is only as good as the intent check.
- Verify each fact against its source.
- Confirm metadata lengths in the publishing tool, because character counting varies.

## Example (illustration)

Query: "how to fact-check AI content"
Likely intent: informational. The reviewed results are guides, not tools.
Reader question: "What steps do I follow to check a draft before publishing?"
Proposed H2s: checklist of claim types, source hierarchy, quote verification, date check, final human approval.
