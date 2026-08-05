---
name: quiet-diary-illustration-v1
description: Transform one or more photographs—including weak, blurred, badly framed, ordinary, or visually busy snapshots—into a stable reference-locked experimental editorial poster. Use for quiet photo posters, art prints, travel memories, archival layouts, tiny-figure landscapes, specimen plates, geometric photo collage, or restrained visual diaries that must consistently use a vertical paper canvas, one dominant spatial gesture, decisive photographic cropping, sparse archival typography, limited flat colour, and tactile offset-print grain rather than watercolor, decorative illustration, scrapbook, or generic graphic design.
---

# Quiet Diary Illustration — Reference-Locked Poster System

Turn the user's source into both:

1. a compact final image-generation prompt, and
2. the generated raster poster made from that prompt.

Use **Reference-Locked Standard Mode** unless the user explicitly requests another direction. Do not merely describe the style or stop at a prompt.

## Reference lock

Every result must read as part of the same poster family as the supplied four references. Preserve these non-negotiable traits:

- vertical **4:5** flat poster canvas by default; no mockup, wall, frame, drop shadow, or photographed paper
- matte uncoated paper or flat ink field with visible analog grain
- one dominant spatial gesture, never a collection of equally important elements
- recognisable photographic evidence: crop, cutout, printed fragment, silhouette, or altered landscape
- extreme scale contrast: vast field versus small image, or large scene versus tiny figure and fine notation
- compact palette: paper/field tone, dark ink, one photographic colour family, and at most one accent
- sparse editorial typography: one short title plus zero to three micro-notes
- controlled strangeness created by crop, scale, boundary, colour replacement, or displaced frame
- quiet, archival, enigmatic, modern, and tactile mood

The family may range from mostly empty paper to an almost full photographic landscape. Its consistency comes from hierarchy, flat colour, small type, analog reproduction, and precise restraint—not from using the same amount of empty space every time.

Ignore screenshot UI: buttons, expand/refresh icons, profile names, red corner marks, white app margins, status bars, and social-media overlays. Do not reproduce rounded app-card clipping unless the user asks for it.

## Prompt compiler

Compile only instructions that become visible pixels. Every final prompt must answer the following questions in this order.

### 1. Canvas

- vertical 4:5 poster
- flat orthographic view
- full-frame paper or ink surface
- no external border, mockup, frame, or cast shadow

If the user explicitly requests another aspect ratio, keep all other geometry proportional.

### 2. Layout recipe

Choose exactly one of the four recipes below. Do not combine recipes.

### 3. Source anchor

Identify one strongest source fact: flock, person, bench, horizon, shoreline, object, gesture, facade, shadow, or relationship. Make it the only primary image event. A weak photo is improved by selection and context, not restoration.

### 4. Photographic treatment

Preserve the anchor as recognisably photographic or printed-photographic. Use decisive crop, grainy cutout, faded offset reproduction, halftone, xerox softness, desaturation, softened edges, or selective flat recolouring. Never repaint the full photograph.

### 5. Colour logic

Use one recipe-appropriate dominant field and no more than three principal hues. Preferred family: warm cream, oatmeal, dusty blue-grey, grey-green, olive, indigo-black, faded cobalt, burnt orange, and softened charcoal. Colour must be opaque or nearly flat; avoid gradients and digital pastel haze.

### 6. Typography

Use one short verified title or word and up to three metadata notes such as a real date, place, time, sequence, initials, or brief definition. Use restrained serif, neutral grotesk, or monospaced/typewriter lettering. Most type must remain small. Do not invent foreign text, coordinates, dates, signatures, or quotes.

### 7. Reproduction surface

Specify matte absorbent stock, warm paper tooth, offset or risograph grain, softened blacks, faded ink, subtle halftone, restrained dust, and slight misregistration. Texture must follow the fields and photograph rather than appear as uniform digital noise.

### 8. Hard avoids

End every prompt with the relevant negative constraints from this file.

## Four fixed layout recipes

### Recipe A — Low photographic strip

Use when the source contains a flock, repetition, skyline, movement, horizon, street sequence, or wide environmental rhythm.

- warm cream or oatmeal paper covers the canvas
- approximately **65%–78%** of the poster remains quiet paper
- one horizontal photographic strip occupies **22%–32%** of poster height and **78%–90%** of poster width
- place the strip in the lower-middle or lower third, not against the edge
- place two or three isolated micro-notes far apart in the upper and middle field
- keep the photograph cool, faded, grainy, and low-to-medium contrast
- no extra illustration, swatches, or second image

### Recipe B — Central specimen plate

Use when the source contains one object, artwork, bird, building fragment, portrait detail, still life, or conceptual motif.

- one dusty grey-green, faded blue, stone, or warm paper field covers the poster
- approximately **58%–75%** remains visually quiet
- one framed or paper-edged image plate occupies **20%–34%** of the poster area near the optical centre
- the plate may contain one photographic crop plus up to four small tonal swatches attached to one side
- place one lowercase title immediately below or slightly overlapping the plate
- add only one short definition or archival line below the title
- use subdued photography; one colour inside the plate may remain stronger
- no scattered labels elsewhere

### Recipe C — Monumental field with tiny figure

Use when the source includes one or two people, a bench, chair, animal, vehicle, tree, or small silhouette with emotional scale potential.

- warm cream paper is the base
- one large flat rectangular or slightly irregular colour field occupies **48%–64%** of the canvas, mainly in the upper half
- use olive, moss, faded blue, muted red, charcoal, or another single source-derived hue
- isolate one tiny photographic figure/object cluster occupying **2.5%–7%** of the canvas
- place it exactly on or just across the lower boundary of the large field
- retain a small source-derived ground/shadow notch if it improves the join
- use no title by default; allow only one tiny caption or initials near a lower corner
- the tiny figure must remain photographic, not cartooned or redrawn

### Recipe D — Fractured photographic landscape

Use when the source is a landscape, sea, architecture, road, mountain, large interior, or scene with strong planes.

- the photographic scene occupies **72%–92%** of the poster
- preserve one dominant horizon, shoreline, wall, path, or structural axis
- replace one or two broad source regions with flat colour; together they occupy **18%–42%** of the canvas
- use one high-impact field such as burnt orange, deep indigo, olive, cream, or dusty blue
- keep one very small photographic human or object, when present, as a scale marker
- add one family of hairline geometry only: one offset rectangle or two thin divisions
- allow at most one micro-label aligned to a frame edge
- maintain coarse offset-print or archival magazine reproduction rather than glossy photography

## Recipe selection

Select by source structure, not at random:

- repetition or wide motion → Recipe A
- isolated object or image-within-image → Recipe B
- person/object with scale potential → Recipe C
- strong environmental planes → Recipe D

If two recipes seem possible, choose the one that requires less invention and preserves the strongest real source fact. For a batch, deliberately rotate compatible recipes; do not default every image to a tiny central plate.

When multiple photographs are supplied, use one as the primary anchor. A second may contribute one crop, silhouette, texture, or colour sample inside the selected recipe. Never create a split screen, equal grid, before/after pair, or dense montage unless explicitly requested.

## Fixed prompt shape

Write the final generation prompt as exactly four compact paragraphs:

1. canvas, paper/field, selected recipe, exact visual proportions, and placement
2. source anchor, decisive crop, photographic treatment, and source details that must remain recognisable
3. palette, verified typography, optional geometry, and analog reproduction defects
4. mood plus hard avoids

Use concrete visual wording. Do not include analysis, source paths, rule names, explanations, checklists, or alternative layouts in the final prompt. Never ask the image model to choose the composition.

## Generation workflow

1. Inspect the source and record only: strongest source fact, dominant axis, usable palette, emotional temperature, and exact user-supplied text.
2. Choose one recipe using the selection rules.
3. Fill every prompt field and compile the four-paragraph prompt.
4. Generate the raster image with the built-in image-generation capability.
5. Inspect the output at full size and thumbnail size.
6. Regenerate once with stricter wording if any hard failure occurs:
   - it looks like a filtered photograph instead of a designed print
   - the chosen recipe geometry is not visible
   - the photographic anchor disappeared or became an illustration
   - typography is large, promotional, excessive, or nonsensical
   - colour became multicoloured, pastel, glossy, or weak
   - texture looks digital, 3D, cinematic, or like a paper mockup
   - screenshot UI entered the art
7. Return the generated image, the exact prompt used, and the recipe name.

If exact lettering is important and generation distorts it, generate with reserved text space, then add the verified typography in a separate editing pass before delivery.

## Negative constraints

Always avoid:

- watercolor, gouache painting, pencil illustration, cute doodles, stickers, tape, scrapbook, or notebook clutter
- full-scene painted imitation or generic photo filter
- generic centered photo with a conventional headline below
- multiple equal images, mood-board grids, dense collage, or scattered decorative fragments
- large advertising headline, logo, CTA, brand campaign, magazine cover, or corporate infographic
- glossy mockup, floating paper, border shadow, hard studio light, cinematic lighting, depth of field, HDR, 3D, neon, or cyberpunk
- smooth vector minimalism, clean UI white, perfect digital gradients, or sterile branding
- anime, kawaii, cartoon, fashion-editorial drama, or stock-photo polish
- long text, motivational quotation, arbitrary foreign writing, fake metadata, fake signature, watermark, or copied artist mark
- interface buttons, social-media chrome, screenshot margins, or app overlays

## Quality gate

Before delivery, confirm every item:

- Reference-Locked Standard Mode was used.
- The output is a flat vertical 4:5 printed poster unless another ratio was requested.
- Exactly one of Recipes A–D is clearly visible.
- Recipe geometry and approximate proportions are respected.
- One photographic source fact remains recognisable.
- One spatial gesture dominates; secondary elements do not compete.
- The palette contains no more than three principal hues.
- Typography is sparse, small, verified, and editorial rather than promotional.
- Analog print grain is embedded in paper, ink, and photography.
- Scale, crop, boundary, or colour replacement creates one controlled strange decision.
- No watercolor, cute hand-drawing, scrapbook, generic template, glossy photo treatment, or screenshot UI appears.
- The poster belongs visually with all four references at thumbnail size.
- The image was actually generated and inspected.

Revise before delivery if any item fails.

## Output format

````markdown
**生成图**

![Quiet Diary poster](absolute-image-path-or-rendered-image)

**版式**

Recipe [A/B/C/D] — [recipe name]

**最终 Prompt**

```text
[exact final prompt]
```
````
