# Repository Guidelines

## Purpose

These guidelines define how S.Academy Brain should be organized, updated, reviewed, and maintained.

## Folder principles

- `courses/` contains course-ready learning assets.
- `shared/` contains reusable schemas, rubrics, base prompts, and standards.
- `templates/` contains reusable starting structures for future assets.
- `docs/` contains operating documentation and governance.
- `client-intelligence/` is reserved for future customer insight assets.
- `exports/` stores raw Notion/PDF/source exports for traceability.

## Naming rules

Use lowercase and hyphens.

Good:

```text
introduction-to-multifamily
halo-overview
q-bank.json
chapter-summary.md
```

Avoid:

```text
Introduction To Multifamily
Halo Overview Final Final
Question Bank Latest.json
```

## Metadata rules

Every course must include:

- id
- title
- description
- status
- version
- owner
- audience
- source
- tags
- chapters
- question_bank
- prompts

## Content rules

Markdown files should be easy to read without the app.

Each chapter should include:

- Chapter title
- Learning objective
- Key concepts
- Main content
- Summary
- Optional references

## Question bank rules

Questions should include:

- id
- question
- answer
- type
- chapter
- subchapter
- difficulty
- evaluation_criteria

## Prompt rules

Course prompts should be split into:

- `system.md` for learning assistant behavior
- `eval.md` for assessment/evaluation behavior

Shared prompt logic belongs in:

```text
shared/eval-base.md
```

## Review process

Recommended workflow:

```text
Draft
↓
Internal Review
↓
Approved
↓
Published
↓
Archived
```

## Security rules

Never commit:

- `.env`
- API keys
- private tokens
- database passwords
- customer PII
- private client data

Use `.env.example` only when environment variables need to be documented.
