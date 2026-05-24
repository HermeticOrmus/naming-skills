# Naming Skills

> A single `CLAUDE.md` for product naming methodology. Mine the brand's vocabulary, converge through register pivots, scale to suite architecture when warranted.

## The principle

> "A product's name already lives inside the brand's vocabulary — mine, don't invent."

Most AI-generated names feel cheap because they're invented from generic startup-name templates. The fix is mining the corpus the brand already has — product names, About page, brand voice docs, project memory, even table names in the DB.

## What this is for

- Product renames (e.g., Legion → Crux)
- Naming new products in an existing suite
- Naming components of a larger system you've designed
- Multi-product suite architecture when scope expands

## What this is NOT for

- Variable names, function names, file names, CLI flags
- One-shot "name my company" requests with no context
- Names that need legal trademark search (this isn't a lawyer)

## The 5-step workflow

1. Understand the product's actual function (verb + parts + user relationship)
2. Mine the brand's vocabulary in order of preference
3. Generate 10 candidates with source + meaning + register + pronounceability
4. Present 3-5 finalists, ask for taste pivot
5. Commit + document the finalists for future renaming context

Full content: [`CLAUDE.md`](CLAUDE.md).

## Install

```bash
curl -o CLAUDE.md https://raw.githubusercontent.com/HermeticOrmus/naming-skills/main/CLAUDE.md
```

Or as a [Claude Code skill](skills/naming/) or [Cursor rule](.cursor/rules/naming.mdc).

## Scaling to suites

When the work signals a multi-product line: pick a thematic root, identify role hierarchy, name from the same root for every product in the suite.

Example: an alchemy-themed suite — flagship "Magnum Opus", seven stages (Calcinate, Dissolve, Separate, Conjoin, Ferment, Distill, Coagulate), supporting tools (Athanor, Crucible, Alembic). The thematic root is what makes the suite read as coherent.

## See also

- [`christen` skill](https://github.com/HermeticOrmus/naming-skills/blob/main/skills/naming/SKILL.md) — the original skill this was packaged from
- [`vibe-engineer-skills`](https://github.com/HermeticOrmus/vibe-engineer-skills)
- [`markdown-discipline-skills`](https://github.com/HermeticOrmus/markdown-discipline-skills)

## License

MIT.


---

## Part of the Libre Open-Source Stack for Claude Code

This repository is part of a growing family of open-source toolkits for Claude Code.

### Libre suite — comprehensive plugin bundles

- [LibreUIUX-Claude-Code](https://github.com/HermeticOrmus/LibreUIUX-Claude-Code) — UI/UX development (152 agents, 70 plugins, 76 commands, 74 skills)
- [LibreArch-Claude-Code](https://github.com/HermeticOrmus/LibreArch-Claude-Code) — Software architecture and system design
- [LibreCopy-Claude-Code](https://github.com/HermeticOrmus/LibreCopy-Claude-Code) — Technical writing and documentation engineering
- [LibreDevOps-Claude-Code](https://github.com/HermeticOrmus/LibreDevOps-Claude-Code) — DevOps engineering and infrastructure automation
- [LibreEmbed-Claude-Code](https://github.com/HermeticOrmus/LibreEmbed-Claude-Code) — Embedded systems, firmware, and IoT development
- [LibreFinTech-Claude-Code](https://github.com/HermeticOrmus/LibreFinTech-Claude-Code) — Financial technology development
- [LibreGEO-Claude-Code](https://github.com/HermeticOrmus/LibreGEO-Claude-Code) — AI-search optimization (ChatGPT, Perplexity, Gemini, Google AI Overviews)
- [LibreGameDev-Claude-Code](https://github.com/HermeticOrmus/LibreGameDev-Claude-Code) — Game development across Godot, Unity, Unreal
- [LibreMLOps-Claude-Code](https://github.com/HermeticOrmus/LibreMLOps-Claude-Code) — ML engineering and AI operations
- [LibreMobileDev-Claude-Code](https://github.com/HermeticOrmus/LibreMobileDev-Claude-Code) — Mobile app development (Flutter, React Native, native iOS, native Android)
- [LibreSecOps-Claude-Code](https://github.com/HermeticOrmus/LibreSecOps-Claude-Code) — Security operations

### Skills mini-repos — single CLAUDE.md drop-ins

- [vibe-engineer-skills](https://github.com/HermeticOrmus/vibe-engineer-skills) — Direct AI codegen well (hypothesis → scope → validate → reject working-but-wrong)
- [markdown-discipline-skills](https://github.com/HermeticOrmus/markdown-discipline-skills) — Strip AI-slop from markdown (no em dashes, no marketing fluff)
- [shell-safety-skills](https://github.com/HermeticOrmus/shell-safety-skills) — `set -euo pipefail` discipline + 15 failure-mode examples
- [commit-standard-skills](https://github.com/HermeticOrmus/commit-standard-skills) — Ormus Commit Standard v1.0 + commit-msg hook + commitlint
- [unwoke-skills](https://github.com/HermeticOrmus/unwoke-skills) — Strip AI theater (ten sins to eliminate, symmetric engagement)
- [python-conventions-skills](https://github.com/HermeticOrmus/python-conventions-skills) — Modern Python 3.11+ (types, pathlib, async, ruff, mypy, uv)
- [typescript-conventions-skills](https://github.com/HermeticOrmus/typescript-conventions-skills) — TypeScript strict mode, discriminated unions, Result types
- [hermetic-laws-skills](https://github.com/HermeticOrmus/hermetic-laws-skills) — Seven Hermetic Principles applied to engineering
- [riper-workflow-skills](https://github.com/HermeticOrmus/riper-workflow-skills) — Research / Innovate / Plan / Execute / Review systematic dev
- [six-day-cycle-skills](https://github.com/HermeticOrmus/six-day-cycle-skills) — Sustainable shipping cadence with mandatory rest
- [token-optimization-skills](https://github.com/HermeticOrmus/token-optimization-skills) — Claude Code token + context optimization
- [osint-skills](https://github.com/HermeticOrmus/osint-skills) — OSINT research methodology (multi-wave investigative spiral)
- [calcinate-skills](https://github.com/HermeticOrmus/calcinate-skills) — Stage 1 of the Magnum Opus (burn project bloat)
- [claude-md-overhaul-skills](https://github.com/HermeticOrmus/claude-md-overhaul-skills) — Audit CLAUDE.md and MEMORY.md against caps
- [session-handoff-skills](https://github.com/HermeticOrmus/session-handoff-skills) — Session handoff + pickup discipline
- [magnum-opus-skills](https://github.com/HermeticOrmus/magnum-opus-skills) — Seven-stage alchemy applied to project transformation

### Template source

- [andrej-karpathy-skills](https://github.com/HermeticOrmus/andrej-karpathy-skills) — the canonical single-file CLAUDE.md pattern (fork of jiayuan_jy's original)

Star the family, not just one — that's how the suite stays coherent.
