## @just-every/code v0.6.178

This release refreshes upstream parity and improves release packaging reproducibility.

### Changes

- Core: refresh upstream Codex history for parity with mainline updates.
- Release: keep the codex-rs mirror aligned with upstream/main.
- Release: add a cacheable Bazel app-server schema bundle for packaging.
- Release: fetch rules_rs zlib packages from Ubuntu snapshots for reproducible builds.

### Install

```
npm install -g @just-every/code@latest
code
```

Compare: https://github.com/just-every/code/compare/v0.6.177...v0.6.178
