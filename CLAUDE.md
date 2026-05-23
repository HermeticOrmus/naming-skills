# CLAUDE.md

Product naming methodology. Iteratively converge on names by mining the client's existing vocabulary (catalog, corpus, DB) rather than inventing from generic startup-name templates.

> "A product's name already lives inside the brand's vocabulary — mine, don't invent."

**Use for**: product renames, naming new products in an existing suite, naming components of a larger system the user has designed.

**Do NOT use for**: variable names, file names, function names, CLI flags — that's naming a symbol, not a brand.

## Core principle

**Name from the client's own corpus first.** Only when the corpus is exhausted or inadequate do you broaden to cross-cultural, multi-language, internet sources. This produces names that feel *native* to the brand rather than *stuck on*.

The inverse — pulling names from a generic startup-name generator — is what makes AI-generated brand names feel cheap. The fix is using corpuses the user already owns and tools they already trust.

## Workflow

### Step 1: Understand the product's actual function

Before generating a single name, load the technical context.

- Read CLAUDE.md, README.md, main source directory
- Identify what the product DOES, its architecture, its parts
- Document: core verb (orchestrate? navigate? transform? bind? measure?), key architectural elements (agents? pipelines? vessels? instruments? stages?), target user's relationship (wield? observe? ride?)

A name that doesn't come from function is decoration, not meaning.

### Step 2: Mine the brand's vocabulary

Sources, in order of preference:

1. **Existing product names** in the suite — pick patterns and stylistic cues
2. **Brand voice docs**, About page, marketing copy — recurring words, metaphors, archetypes
3. **Product database** — table names, column names, type names that already carry meaning
4. **CLAUDE.md / project memory** — what does the team already call the things?
5. **Industry/domain corpus** — vocabulary the target audience uses
6. **Latin / Greek / mythological** — if the brand has a classical leaning
7. **Cross-cultural translations** — if global appeal matters

Stop at the first source that produces 5+ viable candidates.

### Step 3: Generate first round (10 candidates)

For each candidate, name:

- The vocabulary source (where this came from)
- The core meaning it carries
- The register (formal / casual / technical / mystical / playful)
- The pronounceability test (would a stranger say it correctly on first try?)

Filter for: not already trademarked in the relevant class, domain available (.com or .ai or .dev as fits the brand), not a slur in any language the user cares about.

### Step 4: Present 3-5 finalists, ask for taste pivot

User picks one or none. If none: ask what register would fit better and pivot.

- Too clinical → pivot to evocative
- Too whimsical → pivot to serious
- Too long → pivot to single-syllable
- Too generic → pivot deeper into the brand vocabulary

Repeat with the new register. The pivot is the user's taste signal — respect it.

### Step 5: Commit

When the user picks, document:

- The chosen name
- The vocabulary source it came from
- The reason it won over the others
- The other finalists (so a future renaming knows what was considered)

Save to project memory or `naming-finalists.md`.

## Scale up: product-suite architecture

When the work signals a multi-product line (not just one product), the methodology scales:

1. Define the suite's *thematic root* (alchemy? aviation? navigation? rhythm? cartography?)
2. Identify the *role hierarchy* — what's the flagship, what's the secondary, what are the components?
3. Name from the same thematic root for every product in the suite
4. Generate a *suite diagram* showing how the products relate visually + thematically

Example: a suite themed around alchemy might have a flagship (Magnum Opus), seven stages (Calcinate, Dissolve, Separate, Conjoin, Ferment, Distill, Coagulate), and supporting tools (Athanor, Crucible, Alembic). Each name pulls from the thematic root.

## Anti-patterns

- **Starting with the name generator** — produces names with no connection to the product
- **Optimizing for SEO before semantics** — names that rank for keywords but mean nothing
- **Choosing names that explain themselves in the URL** — `simpleinvoicing.com` is a feature description, not a brand
- **Forcing the suite framing on a single product** — sometimes one product is one product
- **Picking the longest word** in the brand vocabulary — first-time-pronounceability matters
- **Ignoring the user's taste pivot** — they live with the name; the methodology serves their taste, not the other way

## When the brand has no vocabulary

For brand-new ventures with no existing corpus, broaden the source order:

1. Founder's own vocabulary (what words do they reach for?)
2. Target audience's vocabulary (what words do they trust?)
3. Industry vocabulary (what register fits?)
4. Classical sources (Latin / Greek / mythological)
5. Cross-cultural (after consultation)

Stop at the first source producing 5+ viable candidates. The process is iterative; you don't have to mine everything at once.

---

**License**: MIT.
