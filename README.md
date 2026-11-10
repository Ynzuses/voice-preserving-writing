# Voice-Preserving Writing

Draft, revise and translate from the author's supplied material while preserving facts, reasoning and supported voice preferences.

For academic and professional drafting, revision, and translation grounded in supplied drafts, notes, author edits, or explicit voice evidence. Preserve the author's reasoning and supported expression preferences.

## Included Skills

| Skill | Purpose |
| --- | --- |
| [voice-preserving-writing](voice-preserving-writing/SKILL.md) | Draft, revise and translate from supplied material while preserving facts, reasoning and supported author preferences. |

## Install with skills.sh

Run this from the project where you want to use the group:

```sh
npx skills@1.7.4 add https://github.com/Ynzuses/voice-preserving-writing/tree/v1.0.1 --skill "*" --agent codex
npx skills@1.7.4 add https://github.com/Ynzuses/voice-preserving-writing/tree/v1.0.1 --skill "*" --agent claude-code
```

Each line selects every member for one agent (Codex or Claude Code) and defaults to the current project. Add `--list` to inspect available members or `--global` for user-wide installation. Use `--skill <skill-name>` to select one member, or choose another supported target such as `--agent claude-code`. Keep the first installation interactive so you can review its destination. Use `--copy` if symbolic links are unavailable.

See **[INSTALL.md](INSTALL.md)** for prerequisites, pinned versions, individual installation, discovery paths, dependencies, updates, and removal. Verify discovery and an actual invocation in the target agent after installing the files.

## Example requests

> Use $voice-preserving-writing to revise this section from my draft and comments, preserving the facts, reasoning order, and evidenced voice preferences.

> Use $voice-preserving-writing to translate this author-approved text, flag semantic uncertainty, and avoid inventing data or claims.

These are requests to an agent. Codex supports explicit `$skill-name` invocation; Claude Code invokes a Skill by name through its Skill tool or `/skill-name`; other agents use their own invocation interface.

## Requirements and scope

The text workflow needs no dedicated runtime library. Supply author materials, the intended reader, and the purpose in the actual task. Compose with available document or evidence capabilities when needed.

Do not infer a complete author identity or style from absent evidence. The Skill does not support evading authorship checks or concealing generated text.

## Versions, support, and license

`1.0.0` is this group's first stable contract. Read [MIGRATION.md](MIGRATION.md) before replacing an older installation and [RELEASE_NOTES.md](RELEASE_NOTES.md) for this release. Compatibility and verification limits are documented in [STABILITY.md](STABILITY.md) and [VALIDATION.md](VALIDATION.md).

Optional companion groups: `office-authoring-suite`, `research-skills-suite`. They are independent distributions and are not installed with this group. When reporting a problem, include agent/CLI versions, reproducible steps, errors, and a synthetic example. Remove credentials, personal data, and unpublished material.

Copyright 2026 Ynzuses. [Apache-2.0](LICENSE). See [NOTICE](NOTICE) and [PROVENANCE.md](PROVENANCE.md) for attribution and retained component terms.

For proposed changes and reproducible reports, see [CONTRIBUTING.md](CONTRIBUTING.md).
