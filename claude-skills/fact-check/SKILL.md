---
name: fact-check
description: Source-based research and fact-checking with a claim-evidence register. Use when the user asks to verify claims, check sources, research a topic for publication, confirm statistics, dates or quotes, or says "sprawdź fakty", "zweryfikuj", "czy to prawda", "skąd ta liczba", "fact-check this", "find sources for".
---

# Fact-Check

Turn a topic or a draft into verifiable claims, check each one against the best available evidence and report what is confirmed, what is not and what is still unknown. The full workflow, with the source hierarchy and evidence statuses, is in `research-and-fact-checking/research-and-fact-checking-workflow.md`.

## Before you start

Confirm the research question, intended use, audience, market, time period and the research cut-off date. If the user provides a draft, extract the claims from it.

## Steps

1. Break the topic or draft into separate claims. One sentence can contain several.
2. For each claim, decide the preferred source type: official documentation, legal text, original research, financial filing, primary statement or reputable reporting.
3. Open and read each source in context. Do not rely on search snippets, headlines or AI summaries.
4. Record publisher, author, publication date and whether the source is primary or secondary.
5. Assign an evidence status: **Supported**, **Partially supported**, **Contradicted**, **Unverified**, **Outdated** or **Requires specialist review**. Add evidence strength: high, medium or low.
6. When reliable sources disagree, show the disagreement and explain it (dates, definitions, methods, geography, interests). Do not pick a side without evidence.
7. Write a short summary that uses only supported information and labels interpretations, inferences and open questions.

## Output

1. Research scope and limitations.
2. Key findings with their evidence status.
3. Claim-evidence register: ID, claim, status, source, source type, date, strength, notes.
4. Conflicting information.
5. Claims needing more verification, with what evidence is missing.
6. Source-based summary.
7. Human review checklist.

## Rules

- Never invent sources, authors, quotes, numbers or dates.
- Never cite a source you have not opened.
- Repeated information is not independent confirmation.
- Use quotation marks only for exact, verified wording.
- Mark unknowns as unknown instead of filling the gap.
- The output is a research draft that a human approves.
