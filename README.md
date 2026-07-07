# ArcReact Continuity Framework

**A set of plaintext templates for codifying project and institutional knowledge in a way any team member — or any LLM — can bootstrap into.**

---

## The Problem

Enterprise AI adoption stalls at the same wall: models produce generic output because they don't have institutional context. Decisions, architecture rationale, ownership boundaries, delivery state, and communication conventions live scattered across Notion, Slack, Google Drive, and people's heads. Every new LLM session starts from zero. Every new team member does too.

## The Framework

Six plaintext continuity documents that hold project state and enable consistent, high-quality LLM sessions across models (Claude, ChatGPT, Gemini, Copilot). Each doc includes an explicit bootstrap block designed to orient any model in one paste.

| # | Document | Purpose |
|---|---|---|
| 01 | **Master Continuity** | Project-level source of truth — mission, scope, current state, decisions log |
| 02 | **Sprint Continuity** | Rolling sprint state — commitments, in-flight work, blockers, standup log |
| 03 | **Architecture Continuity** | System design, tech stack, ADR log, integration contracts |
| 04 | **Backlog & Roadmap** | Prioritized work ahead, epic registry, technical debt registry |
| 05 | **Session Control** | How to run effective LLM sessions — bootstrap protocols, cross-model patterns, thread health |
| 06 | **Team & Handoff** | Ownership matrix, stewardship, handoff protocols between roles |

A companion **Usage Guide** walks through how the docs work together and how to introduce the system to a team.

## Design Principles

- **Plaintext (`.txt`)** — LLM-agnostic. No formatting drift between Claude, ChatGPT, Gemini, Copilot. No markdown quirks. No proprietary format lock-in.
- **Role-based, not name-based** — ownership references roles, not people. Team composition changes; docs don't.
- **Append-only where it matters** — decisions and ADRs are never deleted, only superseded. Full history preserved for audit and for LLM context.
- **Bootstrap-first** — every doc opens with an LLM session bootstrap block. Pin the doc, paste the block, start.
- **Version-logged** — every doc has a version log. No silent edits.

## Usage

1. Copy the templates into your project's docs folder.
2. Fill in project-specific content — start with Master Continuity, then add the others as your workflow requires.
3. Assign a Steward per doc (see the Team & Handoff template for the stewardship model).
4. Start every LLM session by pinning the relevant docs and pasting the doc's bootstrap block. The Session Control template covers this in detail.

## Origin

Originally built as solo-operator tooling for ArcReact, an AI intelligence platform built on Anthropic Claude. Evolved into a team-scale doc set as the operating model grew. Published here as an LLM-agnostic reference for teams working the same underlying problem — turning institutional knowledge into infrastructure their AI tools can actually use.

## License

MIT — free to use, adapt, and redistribute. Attribution appreciated but not required.

---

**Continuity Framework by ArcReact** · [arcreact.com](https://arcreact.com)
