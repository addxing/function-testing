# Function Testing

[![skills.sh](https://skills.sh/b/addxing/function-testing)](https://skills.sh/addxing/function-testing)

A skill for generating functional test cases from PRDs, Git commits, or user stories, and exporting an Excel-style test report. Works with any AI coding agent.

## Install

```bash
npx skills add addxing/function-testing
```

### DeepSeek Harness

This repo follows the DeepSeek Harness (DSH) Skill format. Clone it into a skills directory and it will be auto-discovered:

```bash
# User-level install (available in all projects)
git clone https://github.com/addxing/function-testing ~/.dsh/skills/function-testing

# Project-level install (current project only)
git clone https://github.com/addxing/function-testing .dsh/skills/function-testing
```

DSH hot-reloads the skills directory after cloning; the skill becomes available in new sessions.

## Usage

After installing the skill, ask your AI agent to use it when you need functional test cases:

```text
Use $function-testing to generate test cases for this PRD.
```

For best results, provide one of:

- a PRD or requirements document
- Git commit details or a diff
- a user story or feature description

## What It Does

This skill guides an agent to:

- analyze the input material and identify its source type
- extract testable functional points
- design concise test cases covering positive, negative, boundary, state transition, and data consistency scenarios
- assign priorities such as P0, P1, and P2
- generate an Excel report with overview, feature list, and test case sheets

## Files

- `SKILL.md` - the skill instructions
- `LICENSE.txt` - Apache 2.0 license

## Chinese Documentation

See [README.zh.md](README.zh.md).
