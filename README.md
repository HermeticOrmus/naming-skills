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
