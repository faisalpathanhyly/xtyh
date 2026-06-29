# S.Academy Brain

S.Academy Brain is the Git-based knowledge repository for S.Academy.

It is designed to become the single source of truth for:

- Course content
- Learning assets
- Question banks
- Evaluation prompts
- Rubrics
- Knowledge asset templates
- Future AI-agent-executable resources

## Why this repo exists

S.Academy knowledge currently lives across Notion, courses, documentation, and team knowledge. This repository makes that knowledge structured, version-controlled, reusable, and accessible to both humans and AI systems.

## Core principle

Knowledge should not be locked inside a course.

The intended flow is:

```text
Knowledge
↓
Learning Assets
↓
Courses
↓
S.Academy Experiences
```

Courses are outputs of the knowledge repository, not the source of truth.

## MVP scope

The first version focuses on:

1. Building the foundational Git repository structure
2. Creating reusable knowledge asset templates
3. Migrating the first two learning assets:
   - Introduction to Multifamily
   - Halo Overview
4. Defining governance, metadata, and review workflows
5. Preparing the repo for future AI-native and provider-neutral use

## Top-level structure

```text
s-academy-brain/
  courses/
  shared/
  templates/
  docs/
  client-intelligence/
  exports/
```

## Who this repo is for

- Knowledge Management team
- S.Academy owners
- Course creators
- Product enablement contributors
- Developers
- AI assistants and future agents

## What belongs here

- Approved or draft learning content
- Course metadata
- Question banks
- Evaluation rubrics
- Prompt instructions
- Reusable templates
- Governance documentation
- Source exports for traceability

## What does not belong here

- API keys
- Private credentials
- Render environment variables
- Raw sensitive customer data
- Temporary scratch work
- Unreviewed confidential client notes

## Current status

MVP foundation in progress.
