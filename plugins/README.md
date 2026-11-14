# Vendored plugin copies

This directory holds unmodified copies of third-party DSH plugins kept for reference. It is **not** a pnpm workspace member: nothing here is built, tested or published with this repository, and the folders below are not patch layers unless a profile adds them explicitly.

## `dsh-bridge-next/`

- Upstream: [`anywhere-labs/Agents-Anywhere`](https://github.com/anywhere-labs/Agents-Anywhere/tree/main/dsh-bridge-next), commit `aa12e7a2c181df29c0cf0a88959dccbefef45a92`
- npm package: `@agents-anywhere/dsh-bridge-next`
- License: Apache-2.0 (earlier revisions MIT); the upstream `LICENSE` and `NOTICE` are preserved verbatim in the folder.
- Copied on 2026-11-14 without content changes; see its own `README.md` for installation and `TECHNICAL.md` for design notes.

To install it into a profile, use the published package instead of this copy:

```sh
dsh plugin --profile <name> add @agents-anywhere/dsh-bridge-next
```

[![](https://img.shields.io/badge/powered_by-dsh-4D6BFE?style=flat-square&logo=deepseek&logoColor=white)](https://github.com/deepseek-ai/deepseek-harness)
