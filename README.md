# Quiet Diary Illustration

> Make the familiar feel newly seen.

Quiet Diary Illustration is a reference-locked system for deconstructing one or more photographs—even ordinary or flawed snapshots—into original experimental editorial posters. The source becomes a material library: identity-bearing fragments are extracted, the original scene is removed, and scale, position, medium, and relationships are rebuilt through four repeatable composition recipes.

## Repository contents

- [`ART_DIRECTION.md`](ART_DIRECTION.md) — the creative philosophy and visual language.
- [`SKILL.md`](SKILL.md) — executable guidance for an image-capable AI agent.
- [`agents/openai.yaml`](agents/openai.yaml) — optional Codex interface metadata.
- `examples/` — source-and-output pairs.
- `assets/` — project artwork.

## Use in Codex

Install this repository as a skill, then invoke:

```text
Use $quiet-diary-illustration-v1 in Deconstructed Standard Mode.
Treat these photographs as a material library, select exactly one compatible Recipe A–D, execute extract → remove → rescale → recompose, compile the fixed four-paragraph prompt, generate the poster, inspect it against the quality gate, and return the image, recipe, and exact prompt.
```

## Core principles

1. Preserve only two to four identity cues; remove the original scene.
2. Radically rescale, reposition, and change the medium of extracted elements.
3. Build a new composition around active paper and one dominant spatial gesture.
4. Use colour as structure and typography as sparse archival notation.
5. Reject any result from which the original photographic composition can be reconstructed.

The system deliberately avoids full-scene watercolor conversion, scrapbook styling, decorative doodle filling, generic centered templates, and glossy photo enhancement.

## Status

Version 4.0 replaces photograph-preserving layouts with deconstruction rules, a strict photographic-material limit, radical scale changes, changed spatial order, and a reverse-reconstruction quality gate.

## License

The documentation and skill instructions are released under the [MIT License](LICENSE). Source photographs and example artworks may carry separate rights.
