# v1.0.1 — Voice-Preserving Writing

Draft, revise and translate from the author's supplied material while preserving facts, reasoning and supported voice preferences.

This documentation patch extends the installation and invocation guidance from Codex to Claude Code. Member instructions, scripts, tests, templates and schemas are unchanged from v1.0.0 apart from the version metadata, and v1.0.0 remains available at its own tag.

## What changed

- The README and the [installation guide](INSTALL.md) give the Claude Code command (`--agent claude-code`) next to the Codex one and explain how each host invokes a Skill.
- The discovery check in the installation guide covers Claude Code.
- Fixed-tag links, the product tag and asset names now refer to v1.0.1.

## Included in this release

- `voice-preserving-writing`

Install members by task; other groups are optional companions. The text workflow needs no dedicated runtime library. Supply author materials, the intended reader, and the purpose in the actual task. Compose with available document or evidence capabilities when needed.

## Install or update

```sh
npx skills@1.7.4 add https://github.com/Ynzuses/voice-preserving-writing/tree/v1.0.1 --skill "*" --agent codex
npx skills@1.7.4 add https://github.com/Ynzuses/voice-preserving-writing/tree/v1.0.1 --skill "*" --agent claude-code
```

Project scope is the default. Add `--global` for user-wide use or select one member with `--skill <skill-name>`. Replace complete member directories; upgrading does not remove old copies, install companion groups or change local settings. See [MIGRATION.md](MIGRATION.md) and the [installation guide](INSTALL.md).

## Validation and limits

Do not infer a complete author identity or style from absent evidence. The Skill does not support evading authorship checks or concealing generated text. See [VALIDATION.md](VALIDATION.md) for applicable structural, script, and entrypoint checks. Static checks do not guarantee future agent invocation, native application acceptance, or an external connection.

For this patch the source and an independent candidate copy were re-run with the group's regressions and official Skill validation; see [VALIDATION.md](VALIDATION.md).

## Downloads and checksums

Custom assets: `voice-preserving-writing-1.0.1.zip` and `voice-preserving-writing-1.0.1.zip.sha256`. The extracted ZIP contains per-file `SHA256SUMS` and `RELEASE_MANIFEST.json`. GitHub's automatic Source code archives come from the tagged tree and have different packaging bytes and generated inventories.

Use `Get-FileHash <zip-path> -Algorithm SHA256` on Windows, `shasum -a 256 <zip-path>` on macOS, or `sha256sum <zip-path>` on Linux, then compare the companion checksum. Signatures, platform listings, and native application acceptance are reported only when actually completed.

Copyright 2026 Ynzuses. [Apache-2.0](LICENSE). See [NOTICE](NOTICE) for retained terms.

## Feedback and contributions

Use GitHub Issues for synthetic reproductions and installation feedback. See [CONTRIBUTING.md](CONTRIBUTING.md) for changes and validation expectations.
