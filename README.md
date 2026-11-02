# AI Prompt Library

A curated collection of practical prompts and structured workflows for content creation, editing, research and quality assurance.

This project documents how I use generative AI to support marketing and editorial work while keeping human judgment, fact-checking and brand consistency at the centre of the process.

## Purpose

The library is designed to support:

- content research and planning,
- AI-assisted drafting,
- editorial review and quality control,
- social media content creation,
- SEO optimization,
- content repurposing,
- fact-checking and source verification,
- brand voice consistency.

## How the prompts are documented

Each prompt or workflow includes:

1. **Use case** – when and why it should be used.
2. **Input requirements** – the context and materials needed.
3. **Prompt structure** – the complete instruction for the model.
4. **Expected output** – the required format and level of detail.
5. **Quality criteria** – how the result should be evaluated.
6. **Human review** – what still requires editorial verification.
7. **Example** – a practical application of the workflow.

## Categories

### Content marketing

Prompts for articles, landing pages, newsletters, campaign concepts and editorial planning.

### Editing and quality assurance

Workflows for reviewing clarity, accuracy, structure, tone of voice and audience relevance.

### Research and fact-checking

Prompts for organizing source materials, identifying unsupported claims and preparing verification checklists.

### Social media

Prompts for LinkedIn, Instagram, Facebook, TikTok and YouTube content.

### SEO content

Prompts for content structure, headings, metadata, internal linking and on-page optimization.

### Content repurposing

Workflows for adapting one source material into multiple formats and communication channels.

## Prompt index

| Prompt or workflow | Category | Use it when |
|---|---|---|
| [LinkedIn Hook Workshop](social-media/linkedin-hook-workshop.md) | Social media | You have an insight and need six opening options to compare |
| [LinkedIn Carousel Outline](social-media/linkedin-carousel-outline.md) | Social media | A topic has several steps and needs one idea per slide |
| [Social Channel Audit](social-media/social-channel-audit.md) | Social media | A channel publishes regularly but results are flat and you need prioritised changes |
| [Search Intent Brief](seo-content/search-intent-brief.md) | SEO content | You plan a page around a query and need the intent checked first |
| [Personal Brand Positioning](content-marketing/personal-brand-positioning.md) | Content marketing | A portfolio or profile does not clearly say what you do |
| [AI Fingerprint Review](editing-and-quality/ai-fingerprint-review.md) | Editing and QA | A draft is accurate but reads as generic |
| [AI Content Review](editing-and-quality/ai-content-review.md) | Editing and QA | You need a full editorial and UX writing review |
| [Research and Fact-Checking Workflow](research-and-fact-checking/research-and-fact-checking-workflow.md) | Research | You need a verifiable source-based summary |
| [Content Repurposing Workflow](content-repurposing/content-repurposing-workflow.md) | Content repurposing | One approved source must become several channel formats |

## Claude Skills

Four of the workflows are also packaged as **Claude Skills**: folders with a `SKILL.md` file that Claude loads automatically when a request matches the skill's description. The prompt files above document the method; the skills make it reusable without copying prompts.

| # | Skill | Use it when | Example trigger phrases | File |
|---|---|---|---|---|
| 1 | Content Review | A draft, landing page or interface copy needs checking before publication | „sprawdź ten tekst”, „czy to można opublikować”, “review this copy” | [SKILL.md](claude-skills/content-review/SKILL.md) |
| 2 | Fact-Check | Claims, numbers, dates or quotes need sources | „sprawdź fakty”, „skąd ta liczba”, “fact-check this” | [SKILL.md](claude-skills/fact-check/SKILL.md) |
| 3 | Content Repurposing | One approved source must become posts, a carousel, a newsletter and a video script | „przerób to na posty”, “repurpose this” | [SKILL.md](claude-skills/content-repurposing/SKILL.md) |
| 4 | Social Channel Audit | Platform statistics need analysis and a test plan | „przeanalizuj kanał”, “audit this channel” | [SKILL.md](claude-skills/social-channel-audit/SKILL.md) |

**How to use them:** in Claude, add a skill folder through the skills settings (or place it in your Claude Code skills directory). Every skill keeps the same rule as the rest of this library: AI prepares the work, a human checks the facts and approves publication.

## Practical examples

- [AI Content Review – SaaS Landing Page and UX Writing](case-studies/ai-content-review-example.md)
- [ChatGPT vs Claude – AI Content Review Comparison](case-studies/chatgpt-vs-claude-content-review.md)
- [Newsletter Content Repurposing – AI Prościej](case-studies/newsletter-content-repurposing-example.md)
- [Airline Brand Impersonation Research – LOT Case Study](case-studies/airline-brand-impersonation-research-example.md)

## Editorial principles

AI-generated content should not be treated as a finished product.

Every output requires human review for:

- factual accuracy,
- relevance and context,
- tone and brand consistency,
- clarity and readability,
- unsupported or misleading claims,
- unnecessary repetition,
- audience fit,
- final editorial quality.

## Tools used in this project

| Area | Tools | Application |
|---|---|---|
| **AI content creation and editing** | ChatGPT, Claude | Prompt testing, drafting, rewriting, content review and output comparison |
| **Research and source analysis** | NotebookLM | Working with source materials, extracting insights and organizing research |
| **Language editing and translation** | DeepL | Translation, language refinement and clarity checks |
| **Documentation and project organization** | GitHub, Notion | Documenting prompts, workflows, examples and project development |
| **Visual content support** | Canva | Preparing simple diagrams, prompt cards and supporting visuals |

Tool selection depends on the task, source materials and required level of editorial control. AI-generated outputs are always reviewed and refined before publication.

## Repository structure

```text
AI-Prompt-Library/
├── claude-skills/
│   ├── content-review/SKILL.md
│   ├── content-repurposing/SKILL.md
│   ├── fact-check/SKILL.md
│   └── social-channel-audit/SKILL.md
├── content-marketing/
│   └── personal-brand-positioning.md
├── editing-and-quality/
│   ├── ai-content-review.md
│   └── ai-fingerprint-review.md
├── research-and-fact-checking/
│   └── research-and-fact-checking-workflow.md
├── social-media/
│   ├── linkedin-carousel-outline.md
│   ├── linkedin-hook-workshop.md
│   └── social-channel-audit.md
├── seo-content/
│   └── search-intent-brief.md
├── content-repurposing/
│   └── content-repurposing-workflow.md
├── case-studies/
└── README.md
```
