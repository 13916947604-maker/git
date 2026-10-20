# Lecture Core Revision

A bilingual study-note Skill for turning university lecture slides and matching timestamped transcripts or captions into compact, source-grounded core revision notes. It uses the open `SKILL.md` Agent Skills format shared by Claude and Codex.

## What it does

- Reviews supplied slides and matching transcripts or captions; reports missing sources or partial transcript coverage.
- Organises concepts by question and dependency while preserving page references, verified timestamps, mechanisms, examples, values, conditions, and qualifications.
- Writes in approximately 60% English and 40% Chinese, with an abstract, numbered topics, and a compact bilingual vocabulary table.
- Keeps notes grounded in the supplied sources and flags caption errors or unresolved disagreements.
- Makes Notion saving optional and destination-specific; the public Skill contains no private page address or credentials.

## Use with Claude.ai

Download this repository as a ZIP. Put `SKILL.md` inside a folder named `lecture-core-revision`, compress that folder, then open **Customize → Skills → Create skill → Upload a skill** in Claude and select the ZIP. Enable the Skill, start a chat, and provide the lecture slides plus matching transcript or captions. Claude may require **Code execution and file creation** to be enabled for Skills.

## Use with Claude Code

Copy `SKILL.md` into `~/.claude/skills/lecture-core-revision/SKILL.md` for a personal Skill, or into `.claude/skills/lecture-core-revision/SKILL.md` for one project. Start a new session after installing or updating it.

## Use with Codex

Copy `SKILL.md` into `~/.codex/skills/lecture-core-revision/`. `openai.yaml` provides optional Codex interface metadata; Claude reads the `SKILL.md` instructions.

## Example

> Use Lecture Core Revision to make bilingual core revision notes from these lecture slides and matching captions. Keep original slide numbers and verified timestamps, explain the mechanisms, and identify any gaps in source coverage.

## Repository files

- `SKILL.md` — shared Claude/Codex Skill instructions.
- `openai.yaml` — optional Codex interface metadata.

This repository contains no course slides, captions, student notes, login credentials, or private Notion destination.
