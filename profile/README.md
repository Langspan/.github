<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://langspan.dev/assets/brand/langspan-lockup-dark.svg">
  <img alt="LangSpan" src="https://langspan.dev/assets/brand/langspan-lockup-light.svg" width="288" height="80">
</picture>

# Your agents. On the same page.

LangSpan is an open-source coordination layer for the coding agents your team
already uses. Bring related work into existing sessions before their next edit,
catch supported overlaps in a shared checkout, and share work updates between
machines through your Git remote.

**v0.1.0 is available for macOS and Linux.**

[Download LangSpan](https://github.com/Langspan/LangSpan.dev/releases/tag/v0.1.0) ·
[Website](https://langspan.dev/) · [Explore capabilities](https://langspan.dev/#demo) · [Launch film](https://langspan.dev/#film) ·
[Quickstart](https://github.com/Langspan/LangSpan.dev#get-started) ·
[Source](https://github.com/Langspan/LangSpan.dev)

<a href="https://langspan.dev/#edit-coordination">
  <picture>
    <source media="(max-width: 600px)" srcset="https://langspan.dev/assets/product/langspan-overview-compact.svg">
    <source media="(prefers-reduced-motion: reduce) and (prefers-color-scheme: dark)" srcset="https://langspan.dev/assets/product/langspan-card-dark-still.svg">
    <source media="(prefers-reduced-motion: reduce)" srcset="https://langspan.dev/assets/product/langspan-card-light-still.svg">
    <source media="(prefers-color-scheme: dark)" srcset="https://langspan.dev/assets/product/langspan-card-dark.svg">
    <img src="https://langspan.dev/assets/product/langspan-card-light.svg" alt="LangSpan: in a shared checkout Agent A holds src/auth/session.ts, Agent B’s overlapping request is refused, and B independently chooses tests/session.test.ts." width="1300">
  </picture>
</a>

*Illustrated local coordination; not a session recording.
[Motionless version](https://langspan.dev/assets/product/langspan-card-light-still.svg).*

[Watch the 33-second launch film](https://langspan.dev/#film) or [inspect the recorded product evidence](https://langspan.dev/#evidence). The film includes authored illustrations and actual dashboard excerpts from a controlled run.

- **Keep your tools.** Native hooks connect Claude Code and Codex. CLI and MCP
  expose the same work records; a dashboard is optional and read-only.
- **Work in parallel.** Local holds can refuse supported overlapping edits.
  Linked worktrees keep their own physical holds and share related context.
- **Stay aware across machines.** Opt-in Git-based sharing brings published
  work metadata into briefings. Remote activity does not deny a local edit.

[Implementation evidence](https://github.com/Langspan/LangSpan.dev/blob/main/docs/IMPLEMENTATION_STATUS.md)
distinguishes real Claude Code and Codex observations from scripted scenarios.
Cursor and Gemini CLI adapters have not been verified in live sessions.
Comparative team outcomes remain to be demonstrated.

Apache-2.0. People set direction and review the combined result.
