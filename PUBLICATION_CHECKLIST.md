# Fractal Light Publication Checklist

Use this checklist before publishing Fractal Light design material.

## Include

- abstract architecture,
- design principles,
- generic layer descriptions,
- source-aware memory structure,
- affect / desire / reflection model,
- action gate design,
- learning note lifecycle,
- research mapping,
- diagrams that do not expose private data.

## Exclude

- private conversations,
- user names,
- character names,
- account IDs,
- memory files,
- logs,
- API keys,
- screenshots with personal data,
- deployment URLs,
- local machine paths,
- secret prompts,
- private relationship settings,
- tool credentials,
- unpublished application source code unless intentionally open-sourced.

## Avoid

- claiming consciousness,
- claiming biological equivalence,
- presenting imagined experience as physical fact,
- encouraging emotional dependency,
- publishing intimate or private examples,
- publishing safety-critical prompts without review,
- mixing public research design with private companion data.

## Public Framing

Recommended framing:

```text
Fractal Light is a bottom-up growth architecture for studying
source-aware memory, affect, desire, reflection, skill learning,
and bounded action in long-term AI companions.
```

Avoid framing it as:

```text
This is a complete artificial soul.
This proves machine consciousness.
This is a public release of a private companion.
This system should autonomously act without oversight.
```

## Before Publishing

Run a text search against the public folder for private terms and local identifiers.

Suggested checks:

```bash
rg -n "PRIVATE|SECRET|TOKEN|API_KEY|localhost|127.0.0.1|/Users/|accountId" fractal-light-public --glob '!PUBLICATION_CHECKLIST.md'
```

Then manually review every match.

## Recommended Repository Shape

```text
fractal-light/
  README.md
  DESIGN.md
  STRUCTURE.md
  RESEARCH_MAP.md
  PUBLICATION_CHECKLIST.md
```

Add an explicit license before publishing.
