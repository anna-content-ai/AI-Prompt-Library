# AI-Generated Content and UX Writing Review

## Purpose
This workflow supports the editorial review of AI-generated marketing content and digital interface copy.
It helps identify issues related to factual accuracy, clarity, structure, tone of voice, audience relevance, usability and overall content quality.
The workflow is designed to support human editorial judgment rather than replace it.

## Use cases
This workflow can be used to review:
- blog articles,
- landing pages,
- newsletters,
- social media posts,
- product descriptions,
- campaign copy,
- AI-generated first drafts,
- website and application interface copy,
- onboarding messages,
- forms and error messages,
- buttons, labels and calls to action,
- navigation and help content.

## Input requirements
Before using the prompt, provide:
- the content to be reviewed,
- the target audience,
- the communication channel,
- the intended purpose,
- the preferred tone of voice,
- relevant brand guidelines,
- source materials, when available,
- the user journey or interface context,
- the action the user should complete,
- character or space limitations,
- accessibility and usability requirements.

## Review criteria
The content should be evaluated for:
1. Factual accuracy
2. Clarity and readability
3. Logical structure
4. Tone of voice consistency
5. Audience relevance
6. Repetition and unnecessary wording
7. Unsupported or misleading claims
8. Natural, human-sounding language
9. SEO and formatting, when relevant
10. Overall editorial quality
11. Information hierarchy and scannability
12. Clarity of calls to action
13. Consistency of interface terminology
14. User guidance and error prevention
15. Accessibility and inclusive language
16. Mobile readability and content length

## UX writing considerations
When reviewing interface content, the model should assess whether the copy:
- clearly explains what will happen after an action,
- uses consistent terminology across the interface,
- reduces uncertainty and cognitive load,
- helps users complete tasks efficiently,
- helps users understand and recover from errors,
- avoids vague calls to action such as “Click here” or “Continue” without sufficient context,
- remains understandable when viewed without surrounding visual elements,
- is concise enough for mobile interfaces,
- follows accessibility and inclusive-language principles,
- supports the intended user journey.

## Human review
AI-generated suggestions should be treated as recommendations rather than final editorial decisions.
The editor remains responsible for:

- verifying facts and sources,
- reviewing context,
- maintaining brand consistency,
- checking legal or sensitive claims,
- assessing whether the copy supports the intended user journey,
- confirming terminology consistency across the interface,
- reviewing accessibility and usability requirements,
- approving the final version.

## Expected output
The model should provide:
- a short overall assessment,
- the three most important issues,
- specific correction recommendations,
- a list of statements requiring verification,
- an improved version of the content,
- a final quality checklist,
- UX writing recommendations, when the content appears in a digital interface,
- shorter alternatives for buttons, labels and interface messages,
- identification of unclear, inconsistent or potentially misleading interface copy.

## Reusable prompt template

```text
You are a senior content editor and UX writer responsible for reviewing AI-generated content before publication.

Your task is to evaluate the content below, identify the most important quality issues and prepare an improved version.

CONTEXT

- Content type: [article / landing page / newsletter / social media post / interface copy]
- Target audience: [describe the audience]
- Communication channel: [website / application / email / social media]
- Content objective: [inform / educate / convert / guide the user]
- Preferred tone of voice: [describe the tone]
- Brand guidelines: [add guidelines or write "not provided"]
- User journey or interface context: [add context or write "not applicable"]
- Character or space limitations: [add limits or write "none"]
- Source materials: [add sources or write "not provided"]

CONTENT TO REVIEW

[Paste the content here]

REVIEW PROCESS

Evaluate the content for:

1. factual accuracy and unsupported claims,
2. clarity and readability,
3. logical structure and information hierarchy,
4. tone of voice and brand consistency,
5. relevance to the target audience,
6. unnecessary repetition and vague language,
7. natural, human-sounding language,
8. SEO and formatting, when relevant,
9. clarity of calls to action,
10. terminology consistency,
11. usability, accessibility and inclusive language,
12. suitability for mobile interfaces, when relevant.

OUTPUT FORMAT

### 1. Overall assessment

Provide a concise assessment of the content and its readiness for publication.

### 2. Priority issues

Present the three most important issues in a table with the following columns:

- Issue
- Why it matters
- Recommended correction
- Priority: high, medium or low

### 3. Claims requiring verification

List all factual, numerical, legal, medical, technical or potentially misleading claims that require human verification.

Do not confirm a claim unless it is supported by the provided source materials.

### 4. Editorial recommendations

Provide specific recommendations related to clarity, structure, tone, audience relevance and brand consistency.

### 5. UX writing recommendations

When the content appears in a digital interface:

- evaluate buttons, labels, error messages and calls to action,
- identify vague or inconsistent terminology,
- suggest concise alternatives,
- explain how the proposed wording supports the user journey.

If the content is not interface copy, write: "Not applicable."

### 6. Improved version

Rewrite the content while preserving its intended meaning, purpose and relevant brand terminology.

Do not add facts, promises, statistics or product features that are not present in the original content or source materials.

### 7. Final quality checklist

Mark each item as:

- Ready
- Requires review
- Not applicable

Checklist:

- factual accuracy,
- clarity,
- structure,
- tone of voice,
- audience relevance,
- brand consistency,
- accessibility,
- SEO,
- calls to action,
- final editorial approval.

IMPORTANT RULES

- Do not invent missing facts or sources.
- Clearly distinguish factual issues from stylistic recommendations.
- Preserve terminology that is required by the brand or product.
- Explain significant changes instead of rewriting the text without justification.
- Treat the final output as an editorial recommendation requiring human approval.
```

## How to use it

Replace all information in square brackets with the context of the task and paste the content requiring review.

For marketing content without an interface or user journey, enter:

```text
User journey or interface context: Not applicable
```

For reliable fact-checking, attach or paste the source materials used to create the original content.

## Limitations
This workflow focuses primarily on content quality and UX writing.

It does not replace:
- professional legal review,
- specialist accessibility testing,
- usability testing with real users,
- visual interface assessment,
- technical SEO audits,
- product design or UI design review.

Screenshots, prototypes or additional product context may be required to evaluate how the content works within the complete interface.

## Status

The complete prompt and practical example will be added in the next version.
