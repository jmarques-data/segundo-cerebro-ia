---
description: Saves a quick capture to 00-inbox/ with date and tags
argument-hint: <what you want to capture>
---

Save the following as a new note in `00-inbox/`:

$ARGUMENTS

Rules:
- File name: `YYYY-MM-DD-short-title.md` (today's date, title in kebab-case).
- Frontmatter: `date` (today), `tags` (2 to 4 tags suggested by the content) and `status: inbox`.
- Body: the captured text, faithful to what I said, with a short title.
- Follow CLAUDE.md (English, no sensitive data).
- At the end, show the path of the new file and suggest which folder it should be organized into later.
