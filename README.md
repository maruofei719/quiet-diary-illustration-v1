# Quiet Diary Illustration

> Create images that feel remembered rather than recreated.

Quiet Diary Illustration is an open visual system for recomposing any photograph—even an ordinary or flawed snapshot—into an elevated minimal handmade poster. It extracts one memorable motif, rebuilds the composition with generous paper space, and combines selective pigment, visible pencil or ink, and integrated handwriting.

## What this repository contains

- [`ART_DIRECTION.md`](ART_DIRECTION.md) — the lasting creative philosophy and visual principles.
- [`SKILL.md`](SKILL.md) — concise, executable instructions for an image-capable AI agent.
- [`agents/openai.yaml`](agents/openai.yaml) — optional Codex interface metadata.
- `examples/` — source-and-output pairs demonstrating the system.
- `assets/` — project artwork such as a banner or icon.

The art direction explains **why** the work looks and feels this way. The skill explains **how** to produce it consistently.

## Use it

### In Codex

Copy this repository into your Codex skills directory, then invoke it by name:

```text
Use $quiet-diary-illustration-v1 to recompose this photograph as a minimal handmade poster.
Keep the original aspect ratio, isolate one motif, and include one short handwritten English line.
```

### With another image-capable model

Attach a photograph, provide the contents of `SKILL.md` as the style instructions, and add any request-specific choices such as:

- no handwriting
- English and Chinese lines
- fewer diary elements
- preserve every architectural landmark

The source photograph remains the authority for identity and emotion, but not for framing. The system may crop, isolate, enlarge, shift, or omit material to create a stronger poster.

## Core principles

1. Extract one memorable motif instead of reproducing the full photograph.
2. Rebuild the composition as a poster rather than applying a watercolor filter.
3. Let empty paper participate in the composition.
4. Keep hand-drawn lines, selective pigment, and integrated handwriting visible.
5. Make every output feel intentional, minimal, and part of the same notebook.

For the complete philosophy, read [`ART_DIRECTION.md`](ART_DIRECTION.md). For generation rules and the quality checklist, read [`SKILL.md`](SKILL.md).

## Example structure

Add examples as paired files with clear, matching names:

```text
examples/
├── temple-source.jpg
├── temple-output.jpg
├── cafe-source.jpg
└── cafe-output.jpg
```

Only publish source photographs you own or have permission to share. Do not include personal or sensitive images without consent.

## Status

Version 1.0 defines the first stable visual language. Future revisions may improve reproducibility, examples, and model-specific guidance without changing the central art direction.

## License

The documentation and skill instructions are released under the [MIT License](LICENSE). Source photographs and example artworks may carry separate rights; label them clearly when adding them.
