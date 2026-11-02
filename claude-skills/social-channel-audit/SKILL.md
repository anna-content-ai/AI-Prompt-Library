---
name: social-channel-audit
description: Audits a social media channel from exported platform data and returns prioritised, testable recommendations. Use when the user shares Instagram, Facebook, LinkedIn, TikTok or YouTube statistics or exports and asks "przeanalizuj kanał", "dlaczego zasięgi spadają", "co poprawić w social mediach", "audit this channel", "what should we post more of".
---

# Social Channel Audit

Review a channel using only the data provided, separate what the data shows from possible explanations, and propose a short test plan. The full prompt and quality criteria are in `social-media/social-channel-audit.md`.

## Before you start

Confirm: platform and account, reporting period, channel goal, target audience, the post data with available metrics, the best and worst posts, publishing frequency and whether paid promotion was used. Metrics must come from the platform's own reporting.

## Steps

1. Summarise what the numbers show in three sentences, using only the data provided.
2. Compare the best and worst posts by format, topic, opening line, length and call to action. Label each finding **observed in the data** or **possible explanation, needs testing**.
3. Check whether the content mix matches the channel goal.
4. List missing data that would change the conclusions.
5. Give five prioritised recommendations, each with the reason, the metric that would show success and the effort (low, medium, high).
6. Propose a two-week test plan with one or two hypotheses and a success measure for each.

## Output

Summary, patterns, content mix, missing data, recommendations, test plan.

## Rules

- Do not estimate or invent metrics, reach or engagement rates.
- Do not compare with competitors unless their data was supplied.
- Mark anything that depends on platform algorithms as an assumption.
- Never recommend buying followers, engagement groups or automated comments.
- If the data belongs to an employer or client, remind the user to confirm what may be shared publicly.
