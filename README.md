# OpsDeck updates

Public source-update downloads for OpsDeck. The source files are intentionally public; no installed workspace data, credentials, website profiles or Ollama models are included.

`latest.json` is the feed for the macOS Apple silicon source updater. Packages are published before the feed is changed. Source packages carry a SHA-256 checksum in the HTTPS feed; this is integrity verification, not a publisher signature.

For the first updater-enabled installation, use the source ZIP in `packages/` and follow the OpsDeck README inside it. Future updates are checked in the app and installed only after user confirmation. The source updater does not support packaged Mac/Windows applications or Docker.
