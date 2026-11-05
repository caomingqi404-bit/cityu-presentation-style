---
name: cityu-presentation-style
description: Create or restyle editable academic slides in a City University of Hong Kong style. Use for CityUHK, CityU, 城大 or 香港城市大学 PPT requests, with the bundled logo, white background, magenta title rule and subtle wave decoration.
metadata:
  version: "1.0.0"
---

# CityUHK Academic Slides

Apply this visual style to research reports, group meetings and academic talks.
Resolve all paths below relative to this skill directory.

## Bundled reference

Read [the style guide](references/style-guide.md) before authoring. For layout
selection, consult [layout recipes](references/layout-recipes.md) and inspect
[the preview](assets/preview.png). The editable reference is
[cityu-starter.pptx](assets/cityu-starter.pptx).

The reference contains four neutral layout examples, not a required slide count.
Replace example wording with the user's content. Preserve the requested order,
language, slide count and output format. A user's existing deck or explicit
formatting request takes precedence over these defaults.

## Core visual choices

- Use a white background, dark text and magenta `#C0055A` accents.
- Place [the bundled logo](assets/cityu-logo.png) at the upper right with its
  aspect ratio intact and clear space around it.
- Put a thin magenta line below the title. Keep the title clear of the logo.
- Use [the wave SVG](assets/cityu-wave.svg), its
  [PNG equivalent](assets/cityu-wave.png), or matching native curves at the
  lower right. Keep decoration away from content.
- Let the page's main figure, diagram or evidence table determine the layout.
  Express priorities with unequal emphasis. Use equal panels only for content
  that is actually parallel or comparable.
- Keep labels concise, provide readable body text and leave purposeful whitespace.

## Authoring workflow

Use the recipient environment's presentation tools. When a presentation skill is
available, follow its creation, rendering and delivery requirements. This package
does not require a particular plugin name, API library or local executable path.
It supplies the style and reference assets, not a slide-generation engine.

For existing decks, inspect their content and preserve the requested structure.
For new decks, establish the research question, method, evidence, limitations and
next work as appropriate to the supplied material. An outline-only request should
remain an outline until the user asks for slides.

Keep text, tables and substantive diagrams editable. Use genuine supplied images
for screenshots or code captures. Do not present generated graphics as real
screenshots or invent experimental results to fill a layout.

Discover fonts and runtime tools in the current environment. Use an available
CJK-capable font for Chinese and verify the chosen font in rendering. Do not
assume the author's fonts or filesystem are present.

Use the requested language throughout titles, body, tables and speaker notes.
Treat presenter, affiliation, footer, date and page numbering as user content.
Do not insert a person's name, project, research group or date by default.

## Before delivery

Render and visually inspect every final slide. Correct clipping, overlap,
unreadable labels, stretched logos and decoration crossing the reading area.
Verify the slide count, evidence labels, language and editability. Distinguish a
rendered preview from a native PowerPoint test when describing validation.

Deliver the requested final artifact. If the environment cannot create or render
it, state the concrete missing capability rather than claiming completion.

See [asset notices](ASSET_NOTICES.md) for the university logo and font handling.
