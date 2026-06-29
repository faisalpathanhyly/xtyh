# AI Provider-Neutral Strategy

## Purpose

S.Academy should be able to use different AI providers over time without rewriting the knowledge repository.

## Current direction

The repository should support:

- Claude-based workflows
- DeepSeek or OpenAI-compatible APIs
- Future AI assistants
- Thin web app runners
- Internal AI skills

## Repo implications

1. Store content as Markdown and JSON.
2. Keep prompts separate from content.
3. Avoid provider-specific assumptions in core schemas.
4. Keep model-specific instructions in separate files if needed.
5. Use consistent question and rubric formats.

## Good pattern

```text
content = provider-neutral
prompts = mostly provider-neutral
model adapters = app/infrastructure layer
```

## Avoid

- Hardcoding Claude-specific language into every file
- Embedding API keys
- Mixing app code with knowledge content
- Making one model the source of truth
