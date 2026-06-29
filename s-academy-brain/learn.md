# learn.md

This file is the operating memory for S.Academy Brain.

Any human, developer, GPT, Claude project, or future AI agent working with this repository should read this file first.

## Repository purpose

This repository is the foundation for S.Academy's Knowledge Operating System.

Its job is to make institutional knowledge:

- Organized
- Trusted
- Version-controlled
- Reusable
- Human-readable
- AI-readable
- Provider-neutral
- Ready for future S.Academy experiences

## Important rules

1. Use Markdown for human-readable content.
2. Use JSON for structured content that apps or AI systems may consume.
3. Keep course content separate from prompts and question banks.
4. Do not store secrets or API keys in this repo.
5. Do not hardcode the repo around one AI provider.
6. Keep filenames lowercase and use hyphens.
7. Every course must have a `meta.json` file.
8. Every course should have `chapters/`, `questions/`, and `prompts/` folders.
9. Shared rubrics and base evaluation logic should live in `shared/`.
10. Raw exports should live in `exports/` only for traceability.

## Recommended knowledge flow

```text
Notion source
↓
Git repository
↓
Structured course files
↓
S.Academy app / Claude Skill / future AI runner
```

## Current MVP courses

- Introduction to Multifamily
- Halo Overview

## Required course structure

```text
course-name/
  meta.json
  chapters/
    ch1.md
    ch2.md
  questions/
    q-bank.json
  prompts/
    system.md
    eval.md
```

## Provider-neutral AI rule

Prompts should work with Claude now, but should not assume Claude forever.

Use language like:

- "AI evaluator"
- "learning assistant"
- "model"

Avoid locking core instructions to only one provider unless a file is explicitly provider-specific.

## Governance rule

No knowledge asset should be treated as final unless it has:

- Owner
- Status
- Version
- Last updated date
- Review status

## Status values

Use these status values:

```text
draft
in-review
approved
published
archived
```

## Versioning rule

Use semantic versions where possible:

```text
0.1.0 = first draft
0.2.0 = revised draft
1.0.0 = approved first release
1.1.0 = approved minor update
2.0.0 = major restructure
```
