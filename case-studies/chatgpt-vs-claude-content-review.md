# ChatGPT vs Claude – AI Content Review Comparison

> **Project type:** Model comparison and prompt evaluation  
> **Content type:** SaaS landing page and interface copy  
> **Models tested:** ChatGPT and Claude  
> **Test date:** July 2026  
> **Status:** Completed  
> **Note:** Exact model versions were not recorded during the initial test.

## Objective
The purpose of this case study is to compare how two generative AI models respond to the same structured content-review prompt.

The test evaluates whether each model can:
- identify unsupported marketing claims,
- distinguish factual risks from stylistic issues,
- assess UX writing and call-to-action clarity,
- avoid inventing product information,
- prepare a safer and more trustworthy version of the copy,
- follow a structured editorial output format.

The goal is not to select a universally better model. It is to understand how the outputs differ and where human editorial judgment remains necessary.

## Test methodology
Both models received:
- the same prompt,
- the same context,
- the same content to review,
- no source materials,
- no follow-up instructions,
- no manual corrections before comparison.

The outputs were assessed against the following criteria:
1. Identification of unsupported claims
2. Factual caution
3. Quality of editorial recommendations
4. UX writing analysis
5. Call-to-action accuracy
6. Compliance with the prompt
7. Quality of the improved copy
8. Practical usefulness for a human editor

## Test context
**Content type:** SaaS landing page and interface copy  
**Target audience:** Small-business owners and freelancers with limited technical experience  
**Communication channel:** Website landing page  
**Content objective:** Encourage users to start creating a website  
**Preferred tone of voice:** Clear, supportive, practical and trustworthy  
**Brand guidelines:** Avoid unsupported superlatives, guarantees and misleading claims  
**User journey:** Landing page → account creation → website setup  
**Character limitations:** Concise headline and call to action  
**Source materials:** Not provided

## Original content
> Build the perfect website instantly with the world’s most revolutionary AI website builder.
>
> No skills are required, and everything is done automatically for you. Join millions of successful users and launch a professional website in just a few seconds.
>
> There is no risk, and you are guaranteed to get amazing results.
>
> **Button:** Continue

## High-level comparison
| Evaluation area | Claude | ChatGPT |
|---|---|---|
| Unsupported claims | Identified the main superlatives, guarantees and social-proof claims | Identified the same major risks and classified them clearly |
| Editorial depth | More detailed and explanatory | More concise and structured |
| UX writing analysis | Strong analysis of uncertainty, pressure language and informed decision-making | Clear focus on the immediate next step and CTA specificity |
| Improved copy | More persuasive, but introduced unconfirmed process details | More conservative and better aligned with the supplied user journey |
| Factual caution | Strong in the analysis, weaker in the rewrite | Stronger in the final rewrite |
| Checklist quality | Generally cautious and nuanced | Clear, but several areas were marked ready without enough supporting context |
| Overall usefulness | Strong diagnostic and editorial analysis | Stronger final copy and safer product assumptions |

## Claude output – strengths
Claude provided a detailed explanation of why the original copy was not suitable for publication.

It correctly identified:
- unsupported superlatives,
- unverifiable user numbers,
- unrealistic speed promises,
- absolute guarantees,
- vague interface language,
- pressure-based social proof,
- insufficient information about the consequences of clicking the CTA.

Its UX analysis was particularly useful because it explained how vague and unsupported wording could reduce trust among non-technical users.

Claude also clearly separated:
- factual and compliance-related concerns,
- stylistic recommendations,
- interface and usability issues.

## Claude output – limitations
The improved version introduced statements that were not confirmed by the supplied context:

> “Answer a few simple questions”

and:

> “No coding or design experience required”

These statements may be plausible, but they were not included in the confirmed product information or source materials.

The CTA:

> “Create my website”

also describes a broader outcome rather than the immediate next step, which was account creation.

This demonstrates that a model can correctly identify unsupported claims in the original copy while still introducing new assumptions during rewriting.

## ChatGPT output – strengths
ChatGPT produced a more conservative improved version:

> Create your website with AI

> Create an account to begin setting up your website.

> **Button: Create your account**

This version:
- follows the provided user journey,
- describes the immediate next step,
- avoids adding detailed product features,
- removes guarantees and unsupported statistics,
- uses concise and accessible language,
- creates a clearer relationship between the landing page and account creation.

Its distinction between factual corrections and stylistic recommendations was also useful for editorial work.

## ChatGPT output – limitations
The final checklist was sometimes too confident.

For example, it marked areas such as:

- brand consistency,
- accessibility,
- terminology consistency,
- user guidance

as ready, even though full brand guidelines, interface designs and accessibility testing were not provided.

The output also contained an irrelevant note about no GitHub repository or pull request being supplied. This was unrelated to the content-review task and reduced the precision of the response.

## Comparison of the improved versions

### Claude

**Headline:**  
Build your website with AI — no design skills needed

**Supporting copy:**  
Answer a few simple questions, and our AI will help you create a professional website. No coding or design experience required.

**CTA:**  
Create my website

### ChatGPT

**Headline:**  
Create your website with AI

**Supporting copy:**  
Create an account to begin setting up your website.

**CTA:**  
Create your account

## Editorial assessment

Claude produced the stronger diagnosis. Its analysis was more detailed, especially in relation to trust, pressure language and informed user decision-making.

ChatGPT produced the safer final rewrite. It relied more closely on the supplied context and did not introduce as many unconfirmed product details.

The strongest editorial result would combine:

- Claude’s detailed risk and UX analysis,
- ChatGPT’s caution when rewriting product copy,
- human verification of the actual product flow,
- confirmed product information,
- final editorial and legal approval.

## Evaluation summary
| Criterion | Claude | ChatGPT |
|---|---:|---:|
| Detection of unsupported claims | 9/10 | 9/10 |
| Editorial analysis | 9/10 | 8/10 |
| UX writing analysis | 9/10 | 8/10 |
| Factual caution in rewritten copy | 7/10 | 9/10 |
| CTA alignment with the user journey | 7/10 | 9/10 |
| Output structure | 9/10 | 9/10 |
| Practical editorial usefulness | 8.5/10 | 8.5/10 |

These scores reflect this single test only and should not be treated as a general benchmark of either model.

## Human editorial decision
The preferred final direction is:

### Headline

Create your website with AI

### Supporting copy

Create an account to begin setting up your website.

### Call to action

**Create your account**

This version is preferred because it:
- avoids unsupported product promises,
- reflects the supplied user journey,
- explains the immediate next step,
- remains concise for mobile interfaces,
- does not introduce unverified functionality.

The final wording would still require confirmation against the actual account-creation process, brand terminology and product documentation.

## Prompt improvement after testing
The comparison revealed that the original prompt did not provide enough control over product assumptions.

The following context fields were therefore added:

```text
- Immediate action after the CTA: [describe exactly what happens after the user selects the CTA]
- Confirmed product facts: [list only verified product features, conditions and process details]
```

The following rule was also added:
```text
Do not infer product features, account requirements or interaction steps that are not explicitly listed in the confirmed product facts, user journey or source materials.
```

These changes are intended to reduce the risk of models introducing plausible but unverified product details.

## Key lessons
1. A detailed analysis does not guarantee a factually safer rewrite.
2. Models may introduce new assumptions even after correctly identifying unsupported claims.
3. CTA recommendations require precise information about the immediate next step.
4. Quality checklists can create false confidence when the model lacks full context.
5. A structured prompt improves consistency but does not remove the need for human review.
6. Comparing model outputs can reveal weaknesses that are not visible when testing only one model.
7. Prompt testing should lead to documented improvements rather than simply selecting a preferred output.

## Limitations
This comparison is based on:
- one content sample,
- one response from each model,
- no repeated runs,
- no source materials,
- model versions that were not recorded,
- qualitative editorial assessment rather than a formal benchmark.

The results should therefore be treated as a practical portfolio experiment, not a universal performance evaluation.

## Conclusion
Both models identified the central problems in the original content.

Claude was stronger at explaining the editorial and UX risks. ChatGPT was stronger at producing a cautious final version aligned with the immediate user journey.

The test confirms that the most reliable workflow is:

**Structured prompt → Multiple model outputs → Editorial comparison → Product verification → Human decision → Final approval**
