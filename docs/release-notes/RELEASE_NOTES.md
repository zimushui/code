## @just-every/code v0.6.180

This release improves Linux packaging, TUI copy behavior, voice host setup, and bundled model metadata.

### Changes

- CLI: use jemalloc for Linux musl binaries to improve allocator behavior.
- TUI: preserve Markdown formatting when copying assistant responses.
- Voice: add WebRTC negotiation and initialize the packaged GStreamer runtime in the voice host.
- Models: add GPT-6-Astra to the bundled model catalog.

### Install

```
npm install -g @just-every/code@latest
code
```
