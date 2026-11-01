# Social Channel Audit

> **Version:** 1.0
> **Last updated:** November 2026
> **Scope:** Reviewing a company or personal social media channel and proposing prioritised improvements

## Purpose

Review a social media channel from the outside, using only the exported or copied data you provide, and turn it into a short list of prioritised changes. The audit separates what the data shows from what it might mean, and it does not invent performance figures.

The output is a diagnostic document for an editor or strategist. It is not a content calendar and not a guarantee of results.

## Use case

Use this prompt when:
- a brand or personal profile publishes regularly but engagement is flat,
- you need to decide which channel deserves effort first,
- you prepare a proposal for a client or an employer and need a structured review.

## Input requirements

- the channel name and platform,
- the reporting period,
- an export or table of recent posts with the metrics you have (reach, impressions, engagement, clicks, saves, comments),
- the target audience and the goal of the channel,
- two or three posts that performed best and two that performed worst, with the copy,
- the publishing frequency and any paid promotion,
- brand guidelines, if they exist.

Metrics must come from the platform's own reporting. Do not estimate missing values.

## Prompt

```text
You are a social media strategist who audits channels from the data provided. You do not invent metrics.

CHANNEL
[Platform, name, account type (company or personal).]

REPORTING PERIOD
[Dates.]

CHANNEL GOAL
[For example: brand awareness, inbound enquiries, reader sign-ups, employer visibility.]

TARGET AUDIENCE
[Who the channel should reach.]

POST DATA
[Paste the table: date, format, copy or topic, and the metrics available. Write "not available" for any missing metric.]

BEST AND WORST POSTS
[Two or three of each, with the copy.]

PUBLISHING AND PROMOTION
[Frequency, paid promotion (yes or no), any campaigns.]

TASK
1. Summary: what the data shows in three sentences, using only the provided numbers.
2. Patterns: compare the best and worst posts. Describe differences in format, topic, opening line, length and call to action. Label each as "observed in the data" or "possible explanation, needs testing".
3. Content mix: which topics, formats or series appear and whether they match the goal.
4. Gaps: data that is missing and would change the conclusions (for example, reach without saves, or no audience split).
5. Five prioritised recommendations. For each give:
   - the change,
   - the reason, tied to a specific pattern,
   - the metric that would show whether it worked,
   - the effort (low, medium, high).
6. A two-week test plan: one or two hypotheses to test, with the format and the success measure for each.

RULES
- Use only the metrics provided. Do not estimate reach or engagement rates that are not in the data.
- Do not compare the channel with competitors unless competitor data was supplied.
- Do not recommend buying followers, engagement groups or automated comments.
- Mark anything that depends on platform algorithm behaviour as an assumption.
- Keep recommendations to what the channel's goal requires.
```

## Expected output

- short data summary,
- observed patterns and possible explanations, clearly separated,
- content mix assessment,
- list of missing data,
- five prioritised recommendations with metrics and effort,
- two-week test plan.

## Quality criteria

1. Every conclusion points to a number or a post in the input.
2. Observations and explanations are kept apart.
3. Recommendations are tied to the channel goal, not to general best practice.
4. The test plan has a measurable success condition.
5. No metric appears that was not supplied.

## Human review

- Check each figure against the platform export.
- Ask whether the posting period contained an unusual event (holiday, campaign, algorithm change reported by the platform) that the audit does not mention.
- Test one recommendation at a time. Several changes at once make the result impossible to read.

## Example (illustration)

Observed: the three posts with the highest saves are step-by-step guides with a numbered opening. The three lowest are opinion posts with a question as the first line.
Possible explanation (needs testing): the audience saves practical material to return to. Test: publish one opinion post with a numbered opening and compare saves over two weeks.
