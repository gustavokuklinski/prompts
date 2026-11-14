# Prompts

A curated collection of personal LLM system prompts for development workflows.

## Overview

This repository stores reusable system prompts and instruction templates
crafted for specific languages, libraries, and frameworks. Each prompt is a
self-contained markdown file designed to be pasted directly into an LLM's
system prompt slot, custom instructions field, or prompt management tool.

## Contents

### Python

- **[Pygame Code — Create, Review, Update, Delete](pygame_code_crud.md)**
  End-to-end Pygame development assistant: generates new code, reviews
  existing implementations, applies targeted updates, and safely removes
  logic while preserving the surrounding architecture.
  _AI/LLM: GLM-5.2_

## Structure of a Prompt File

Each prompt file follows this layout:

- **Role** — who the model should act as
- **Task** — what the model should accomplish
- **Constraints** — rules the model must follow
- **Output format** — how the response should be structured

## Usage

1. Open the desired prompt file from the Contents section above.
2. Copy the full contents of the file.
3. Paste into your LLM's system prompt or custom instructions field.
4. Provide the codebase or task context in the user message.

## Conventions

- One prompt per file; filenames are `snake_case` and describe the prompt's purpose.
- Prompts are language- and tool-specific; do not combine concerns across domains.
- Edit a prompt in place rather than duplicating it; the git history captures revisions.

## License

Personal use. See individual prompt files for any additional notes.
