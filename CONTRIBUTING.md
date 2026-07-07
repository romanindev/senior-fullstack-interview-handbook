# Contributing

Thank you for considering a contribution.

This repository is a public documentation project for Senior Full Stack Engineer interview preparation.

The goal is to keep content practical, clear, accurate, and useful for real interviews.

## Contribution principles

Contributions should be:

- Practical
- Senior-level
- Vendor-neutral
- Public and ethical
- Easy to read
- Easy to review
- Free from duplicated topics
- Suitable for future PDF generation

## What you can contribute

You can contribute:

- Topic explanations
- Interview questions
- Senior-level answers
- Practical examples
- Diagrams
- Common mistakes
- Follow-up questions
- Glossary entries
- Documentation improvements
- Typos and formatting fixes

## What not to contribute

Do not contribute:

- Private or confidential interview questions
- Proprietary company information
- Personal notes about a specific candidate
- Shallow generated content
- Duplicated questions
- Low-quality listicles
- Unverified claims presented as facts
- Company-specific claims without public sources

## Language

Use English for all repository content.

## File naming

Use kebab-case for files and folders.

Good:

```text
react-rendering-pipeline.md
nodejs-event-loop.md
api-versioning.md
```

Avoid:

```text
React Rendering.md
generics_and_types.md
My Notes.md
```

## Markdown structure

Use:

- One `#` heading per file
- `##` for main sections
- `###` for subsections
- Fenced code blocks
- Relative links
- Mermaid diagrams where helpful

## Interview question structure

Each interview question should use this structure:

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

Optional sections:

```markdown
## Senior Tip

## Related Topics

## References
```

## Quality checklist

Before submitting a pull request, check:

- [ ] The content is useful for senior-level interviews
- [ ] The content is not company-specific unless it belongs in `10-company-interviews`
- [ ] The content does not include confidential material
- [ ] The file name uses kebab-case
- [ ] The Markdown is readable
- [ ] Examples are concise and practical
- [ ] Related topics are linked where appropriate
- [ ] `PROGRESS.md` is updated when needed
- [ ] `ROADMAP.md` is updated if scope changes

## AI-assisted contributions

AI-assisted contributions are allowed.

However:

- Review all generated content manually
- Remove filler text
- Check for duplicated topics
- Check technical accuracy
- Keep a consistent tone
- Update `PROGRESS.md`

See:

- `CLAUDE.md`
- `AGENTS.md`

## Pull request size

Prefer small, focused pull requests.

Good PR examples:

- Add React rendering pipeline explanation
- Add TypeScript generics interview questions
- Improve contributing guide
- Add glossary entries for architecture terms

Avoid large PRs that update many unrelated sections at once.

## Commit message examples

```text
docs: add start here section
docs: improve contributing guide
chore: add markdown lint workflow
docs(react): add rendering pipeline overview
docs(nodejs): add event loop interview question
```
