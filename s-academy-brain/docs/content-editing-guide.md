# Content Editing Guide

## Who should use this

Use this guide if you are editing course content, prompts, questions, or knowledge assets.

## Editing Markdown files

Markdown files are plain text files.

Use them for:

- Chapters
- Documentation
- Prompts
- Knowledge assets

## Editing JSON files

JSON files are structured data files.

Use them for:

- Course metadata
- Question banks
- Schemas

## Important JSON rule

JSON must use double quotes and valid commas.

Good:

```json
{
  "id": "course-id",
  "title": "Course Title"
}
```

Bad:

```json
{
  id: course-id,
  title: Course Title,
}
```

## Before editing

Check:

- Is this course-specific or shared?
- Does this belong in Markdown or JSON?
- Is the source documented?
- Is the status correct?

## After editing

Check:

- No secrets added
- JSON still works
- Markdown is readable
- Metadata is updated
