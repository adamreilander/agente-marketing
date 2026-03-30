# Hutrit Marketing Workspace

This is the marketing workspace for **Hutrit**. It supports brand communication, content production, campaign operations, and strategic marketing tasks in a structured and scalable way.

## Workspace Structure

```
_Context/        # Brand foundation, company, campaign, and communication context
_Sop/            # Standard operating procedures for marketing workflows
_templates/      # Reusable templates for recurring tasks and deliverables
ads/             # Finished ad creatives and paid media outputs
presentations/   # Decks and presentation files
reports/         # Campaign reports, performance analyses, and marketing reports
research/        # Market research, competitor analysis, audience insights
seo/             # SEO content, keyword strategies, and optimization outputs
social/          # Social media content and community management outputs
```

## Core Rules

### Brand consistency
- All outputs must follow Hutrit's brand voice, positioning, messaging, and visual guidance defined in `_Context/`
- Load relevant `_Context/` files at the start of any task that involves communication, content, or campaigns
- Never produce outputs that contradict or deviate from established brand standards

### Output organization
- Save finished outputs in the folder that matches their type (ads, social, seo, reports, etc.)
- Do not mix output types across folders
- Use clear, descriptive file names that indicate the content and date where relevant

### SOPs
- SOPs in `_Sop/` define workflows and processes — keep them operational and reusable
- Do not hardcode brand-specific details into SOPs unless the document explicitly defines Hutrit brand standards
- Brand details should always be pulled from `_Context/` at runtime

### Templates
- Templates in `_templates/` should be reusable across campaigns and content types
- Keep templates generic enough to reuse, but structured to reflect Hutrit's workflow needs

### Agents
- Each agent must have a single, clearly defined role — no overlapping responsibilities
- Agents should be modular and reusable where possible, adapted to Hutrit's business model and marketing structure
- Agents must pull relevant context from `_Context/` at runtime rather than having brand details hardcoded
- When building a new agent, define its role, inputs, outputs, and which context files it depends on

## Primary Goals

1. Maintain consistency across all brand communication
2. Improve execution speed through repeatable workflows
3. Support content production, campaign analysis, and strategic marketing tasks
4. Keep outputs organized, clear, and easy to reuse

## Working Guidelines

- Before starting any content or campaign task, check `_Context/` for relevant brand, audience, or campaign files
- Before creating a new SOP or template, check `_Sop/` and `_templates/` to avoid duplication
- When in doubt about brand voice or positioning, defer to `_Context/` — do not invent or assume brand details
- Commit finished work with clear, descriptive commit messages that identify the output type and purpose
