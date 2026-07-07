# CLAUDE.md

This file provides instructions for Claude Code and other AI coding assistants working in this repository.

## Project purpose

Maintain a public, vendor-neutral interview preparation handbook for Senior Full Stack Engineers.

The project must remain useful for a broad audience and must not be personalized for any specific candidate or company.

## Core rules

- Do not personalize content.
- Do not make the handbook company-specific.
- Do not include private or confidential interview questions.
- Do not duplicate existing topics.
- Use English.
- Use Markdown.
- Keep files focused and reviewable.
- Prefer one topic per Markdown file.
- Update `PROGRESS.md` after meaningful changes.
- Update `ROADMAP.md` when scope or milestones change.
- Follow `STYLE_GUIDE.md`.
- Follow `CONTRIBUTING.md`.

## Before editing

Before creating or changing content:

1. Read `README.md`.
2. Read `ROADMAP.md`.
3. Read `PROGRESS.md`.
4. Read the relevant section README.
5. Check whether the topic already exists.
6. Decide the smallest useful change.

## File naming

Use kebab-case.

Good:

```text
react-reconciliation.md
typescript-generics.md
nodejs-streams.md
```

Bad:

```text
React Notes.md
generics_and_types.md
nodeStreams.md
```

## Content quality

Every topic should be:

- Accurate
- Practical
- Senior-level
- Easy to read
- Useful for interviews
- Suitable for future PDF generation

Avoid:

- Filler content
- Shallow explanations
- Repeating the same point in different words
- Overly broad files
- Unverified claims
- Excessive code

## Interview question format

Use this structure:

```markdown
# Question title

## Question

## Short Answer

## Deep Dive

## Example

## Common Mistakes

## Follow-up Questions

## What Interviewer Expects
```

## Updating progress

When a new file is added, update `PROGRESS.md`.

When a roadmap milestone changes, update `ROADMAP.md`.

Do not mark a section as complete unless it has:

- Topic overview
- Interview questions
- Practical examples
- Common mistakes
- Internal links
- Review pass

## Working with generated content

Generated content must be reviewed and refined.

Do not commit raw AI output without:

- Removing filler
- Checking accuracy
- Checking duplication
- Checking formatting
- Checking tone
- Checking links

## Pull request guidance

Keep PRs focused.

Good:

- Add React rendering pipeline overview
- Add TypeScript generics interview questions
- Add Markdown lint workflow

Avoid:

- Add all React content in one huge PR
- Rewrite unrelated sections
- Mix formatting, content, and tooling changes without reason
