# v1.0.0 — Voice-Preserving Writing

Draft, revise and translate from the author's supplied material while preserving facts, reasoning and supported voice preferences.

This is the group's first stable release. For academic and professional drafting, revision, and translation grounded in supplied drafts, notes, author edits, or explicit voice evidence. Preserve the author's reasoning and supported expression preferences.

## Included in this release

- `voice-preserving-writing`

Install members by task; other groups are optional companions. The text workflow needs no dedicated runtime library. Supply author materials, the intended reader, and the purpose in the actual task. Compose with available document or evidence capabilities when needed.

## Installation

```sh
npx skills@1.7.4 add https://github.com/Ynzuses/voice-preserving-writing/tree/v1.0.0 --skill "*" --agent codex
```

Project scope is the default. Add `--global` for user-wide use or select one member with `--skill <skill-name>`. Check Node/npm/Git and existing installations first. See the [installation guide](INSTALL.md) for complete setup, dependencies, and removal.

## Migration

Read [MIGRATION.md](MIGRATION.md) before upgrading. Existing tags and versions retain their identities. Upgrading does not automatically remove old installations, install companion groups, or migrate local settings. `1.0.0` marks the first stable contract; internal review rounds are not public version numbers.

## Validation and limits

Do not infer a complete author identity or style from absent evidence. The Skill does not support evading authorship checks or concealing generated text. See [VALIDATION.md](VALIDATION.md) for applicable structural, script, and entrypoint checks. Static checks do not guarantee future agent invocation, native application acceptance, or an external connection.

## Downloads and checksums

Custom assets: `voice-preserving-writing-1.0.0.zip` and `voice-preserving-writing-1.0.0.zip.sha256`. The extracted ZIP contains per-file `SHA256SUMS` and `RELEASE_MANIFEST.json`. GitHub's automatic Source code archives come from the tagged tree and have different packaging bytes and generated inventories.

Use `Get-FileHash <zip-path> -Algorithm SHA256` on Windows, `shasum -a 256 <zip-path>` on macOS, or `sha256sum <zip-path>` on Linux, then compare the companion checksum. Signatures, platform listings, and native application acceptance are reported only when actually completed.

Copyright 2026 Ynzuses. [Apache-2.0](LICENSE). See [NOTICE](NOTICE) for retained terms.

## Feedback and contributions

Use GitHub Issues for synthetic reproductions and installation feedback. See [CONTRIBUTING.md](CONTRIBUTING.md) for changes and validation expectations.
