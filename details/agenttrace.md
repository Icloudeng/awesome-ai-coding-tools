# agenttrace

agenttrace is a local CLI and TUI for inspecting AI coding agent session history. It reads Claude Code, Codex CLI, Gemini CLI, Aider, Cursor exports, OpenCode, OpenClaw, Hermes Agent, Kimi CLI, and generic JSON/JSONL traces, then summarizes cost, token usage, elapsed time, tool failures, slow gaps, and session health.

It fits AI workflow automation because teams can run `agenttrace --overview -f json` in scripts or CI to compare agent sessions and catch expensive or slow runs before digging through raw logs.

**Highlights**

- Local-first session analysis for common coding-agent logs.
- JSON, Markdown, and self-contained HTML overview reports.
- TUI views for overview, critical sessions, detail diagnostics, and diffs.
- CI-friendly health gates for critical sessions and tool failure rates.
