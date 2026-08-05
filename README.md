# Quiet Diary Illustration

> Make the familiar feel newly seen.

Quiet Diary Illustration is a reference-locked system for transforming one or more photographs—even ordinary or flawed snapshots—into restrained experimental editorial posters. A fixed prompt compiler and four source-matched layout recipes keep the results visually connected and repeatable.

## Repository contents

- [`ART_DIRECTION.md`](ART_DIRECTION.md) — the creative philosophy and visual language.
- [`SKILL.md`](SKILL.md) — executable guidance for an image-capable AI agent.
- [`agents/openai.yaml`](agents/openai.yaml) — optional Codex interface metadata.
- `examples/` — source-and-output pairs.
- `assets/` — project artwork.

## Use in Codex

Install this repository as a skill, then invoke:

```text
Use $quiet-diary-illustration-v1 in Reference-Locked Standard Mode.
Analyse these photographs, select exactly one compatible Recipe A–D, compile the fixed four-paragraph prompt, generate the poster, inspect it against the quality gate, and return the image, recipe, and exact prompt.
```

## Core principles

1. Preserve a photographic trace while changing its scale and context.
2. Build the composition around one dominant field.
3. Use colour as structure, not decoration.
4. Treat typography as sparse archival notation.
5. Create sophistication through hierarchy, texture, and one controlled anomaly.

The system deliberately avoids full-scene watercolor conversion, scrapbook styling, decorative doodle filling, generic centered templates, and glossy photo enhancement.

## Status

Version 3.0 adds a deterministic prompt compiler, four fixed composition recipes, measurable geometry, source-based recipe selection, and a regenerate-on-failure quality gate.

## License

The documentation and skill instructions are released under the [MIT License](LICENSE). Source photographs and example artworks may carry separate rights.
