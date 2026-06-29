# Notion to GitHub Workflow

## Purpose

This document explains how knowledge assets move from Notion into the S.Academy Brain repository.

## Workflow

```text
Notion page or database
↓
Export or API extraction
↓
Clean and structure content
↓
Create Markdown and JSON files
↓
Add metadata
↓
Review content
↓
Commit to GitHub
↓
Use in S.Academy or AI workflows
```

## Step 1: Identify source asset

Examples:

- Introduction to Multifamily
- Halo Overview
- System prompt
- Client signal

## Step 2: Choose asset type

Possible asset types:

- Course
- Knowledge asset
- Prompt
- Assessment bank
- Client intelligence signal

## Step 3: Use the right template

- Course: `templates/course-template/`
- Knowledge asset: `templates/knowledge-asset-template.md`
- Client intelligence: `templates/client-intelligence-template.md`

## Step 4: Preserve traceability

Every migrated asset should include:

- Source name
- Source type
- Migration date
- Owner
- Version

## Step 5: Review before publishing

No migrated asset should be marked `published` until reviewed.
