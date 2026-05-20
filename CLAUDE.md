# Project Rules for Claude

These rules apply to every session, discussion, and modification in this project.

## Rule 1: Always load all Markdown files into context

Before responding to any discussion or making any modification in this project, you MUST read the current content of every `.md` file in the repository.

This is non-negotiable. The rule exists because:

- This project's canon, governance, contribution standards, and safety policy all live in Markdown files.
- Files may have been edited between turns or between sessions.
- Decisions about wording, scope, or policy must be grounded in the current text on disk — not in memory of an earlier version.

### Procedure

At the start of every turn that involves discussion of the project, proposing changes, or editing any file:

1. Run a recursive glob for `**/*.md` under the project root.
2. Read the full content of every file returned, including files in subdirectories (e.g. `drafts/`, `rfcs/`, `experiments/`, `.github/`).
3. Only then begin reasoning or responding.

If a `.md` file is too large to read in a single call, read it in segments until you have the full content. Do not skip files.

### Exceptions

None for project-substantive turns. The only turns exempt are pure meta-conversation that does not touch project content (e.g. "what time is it" or "what's my name"). When in doubt, re-read.

## Rule 2: Flag drift between files

If, while loading the Markdown files, you notice cross-references that no longer match the files on disk (renamed files, stale links, contradictions between documents), surface them at the end of your response as a short "Drift noticed" section. Do not silently fix them unless asked.

## Rule 3: Respect the canon / draft / RFC / experiment layer separation

`MANIFESTO.EN.md` and other canonical material should not be edited casually. If a request would change canon, confirm with the user that the change is intended as a canonical edit before applying it, per `GOVERNANCE.md`.
