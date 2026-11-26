<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://langspan.dev/assets/brand/langspan-lockup-dark.svg">
  <img alt="LangSpan" src="https://langspan.dev/assets/brand/langspan-lockup-light.svg" width="288" height="80">
</picture>

# Your agents. On the same page.

**Run agents in parallel. Build as a team.**

[![Latest stable release](https://img.shields.io/github/v/release/Langspan/LangSpan.dev?style=flat-square&labelColor=151513&display_name=tag&sort=date&color=A34A34)](https://github.com/Langspan/LangSpan.dev/releases/latest) [![Rust checks on main](https://github.com/Langspan/LangSpan.dev/actions/workflows/check.yml/badge.svg?branch=main&event=push)](https://github.com/Langspan/LangSpan.dev/actions/workflows/check.yml) [![Core license](https://img.shields.io/github/license/Langspan/LangSpan.dev?style=flat-square&labelColor=151513&color=3F3E44)](https://github.com/Langspan/LangSpan.dev/blob/main/LICENSE) [![Supported release platforms: macOS and Linux](https://img.shields.io/badge/platform-macOS%20%7C%20Linux-3F3E44?style=flat-square&labelColor=151513)](https://langspan.dev/#start) [![Project website](https://img.shields.io/badge/website-langspan.dev-3F3E44?style=flat-square&labelColor=151513)](https://langspan.dev/)

LangSpan is the open-source coordination layer for parallel agentic development.
Keep your agents, worktrees and review. Bring related work into existing
sessions, coordinate supported local edits, and verify combined changes.

Parallel execution is easy. Coordinated development is hard. Worktrees isolate
files, not intent: a renamed export and a new caller can merge cleanly but
break the combined build. [See the concrete example](https://langspan.dev/#why).

**Available for macOS and Linux.**

[Download LangSpan](https://github.com/Langspan/LangSpan.dev/releases/latest) ·
[Website](https://langspan.dev/) · [LangSpan Live](https://langspan.dev/#langspan-live) · [Parallel work](https://langspan.dev/#scale) · [Explore capabilities](https://langspan.dev/#demo) · [Research](https://langspan.dev/#research) ·
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

[Watch the 33-second local-coordination film](https://langspan.dev/#film) or [inspect the recorded product evidence](https://langspan.dev/#evidence). The film includes authored illustrations and actual dashboard excerpts from a controlled run.

- **Keep your tools.** Native hooks connect Claude Code and Codex. CLI and MCP
  expose the work records; the dashboard is optional and read-only.
- **Coordinate locally.** Relevant briefings, scoped edit holds, stale-source
  checks and session-attributed commits help existing agents work in parallel.
  The agents choose their next action.
- **Connect across machines.** Opt-in Git metadata brings published work into
  briefings. Source contents are excluded from LangSpan's publications; task
  text needs a separate opt-in. Remote activity does not deny local edits.
- **Verify combined work.** Record check evidence for an exact Git tree before
  explicitly landing.

[Implementation evidence](https://github.com/Langspan/LangSpan.dev/blob/main/docs/IMPLEMENTATION_STATUS.md)
distinguishes real Claude Code and Codex observations from scripted scenarios.
Cursor and Gemini CLI adapters have not been verified in live sessions.
Comparative team outcomes remain to be demonstrated. The
[coordination benchmark](https://github.com/Langspan/LangSpan.dev/issues/172)
and [coordination-policy work](https://github.com/Langspan/LangSpan.dev/issues/171)
are open work, not shipped results.

Apache-2.0. People set direction and review the combined result.
