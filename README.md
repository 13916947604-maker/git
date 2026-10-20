# Lecture Core Revision

A bilingual study-note Skill for turning university lecture slides and matching timestamped transcripts or captions into compact, source-grounded core revision notes. It uses the open `SKILL.md` Agent Skills format shared by Claude and Codex.

## What it does

- Reviews the supplied slide deck and matching transcript or captions, and reports missing sources or partial transcript coverage.
- Organises concepts by question and dependency while preserving original page references, verified timestamps, mechanisms, examples, values, conditions, and qualifications.
- Writes in approximately 60% English and 40% Chinese, with an abstract, numbered topics, and a compact bilingual vocabulary table.
- Keeps notes grounded in the supplied sources and flags caption errors or unresolved disagreements.
- Makes Notion saving optional and destination-specific; the public Skill contains no private page address or credentials.

## Use with Claude.ai

1. Download [lecture-core-revision-claude.zip](lecture-core-revision-claude.zip).
2. In Claude, open **Customize → Skills**, choose **Create skill → Upload a skill**, and select the ZIP file.
3. Enable the Skill, start a chat, and provide the lecture slides plus the matching transcript or captions.

Claude's account may require **Code execution and file creation** to be enabled for Skills.

## Use with Claude Code

Copy `SKILL.md` into the personal Skills folder (or into `.claude/skills/lecture-core-revision/` for one project):

```sh
mkdir -p ~/.claude/skills/lecture-core-revision
cp SKILL.md ~/.claude/skills/lecture-core-revision/SKILL.md
```

Start a new Claude Code session after installing or updating a Skill.

## Use with Codex

Copy `SKILL.md` into `~/.codex/skills/lecture-core-revision/`. The optional `openai.yaml` file provides Codex-specific interface metadata; Claude reads the `SKILL.md` instructions.

## Example request

> Use Lecture Core Revision to make bilingual core revision notes from these lecture slides and matching captions. Keep the original slide numbers and verified timestamps, explain the mechanisms, and identify any gaps in source coverage.

## Repository contents

- `SKILL.md` — shared Claude/Codex Skill instructions.
- `lecture-core-revision-claude.zip` — ready-to-upload Claude skill bundle.
- `openai.yaml` — optional Codex interface metadata.

This repository contains no course slides, captions, student notes, login credentials, or private Notion destination.
