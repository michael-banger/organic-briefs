# organic-briefs

Public bridge repo so ChatGPT scheduled tasks can fetch validated reference images by raw
GitHub URL (no auth needed, since it's public). No secrets ever go here — only AI-generated
product/avatar/location reference PNGs and, later, `DAILY-BRIEF-*.md` prompt files.

Source of truth for what should be in here: `organic-ai-workflow` (private repo) and
`~/Desktop/CLAUDE/YANN-VAULT/wiki/ecom-organic/higgsfield-elements-registry.md`.

## Structure

```
refs/[brand]/[name].png
```

- `refs/onsimplifie/` — douche-chien product, dog props, bathroom location, avatar Clara.
- `refs/myteaovo/` — pot styles, plant prop, salon location, avatars Clemence + Julie
  (split-test, alternate per video, never both in one video).
- `refs/troputile/` — drink bag (Sipsway 3 colors + AliExpress), 13 Paris/Riviera locations,
  avatar group.
- `refs/spiraledazur/` — handbag product/avatar/location refs, mirrored under their
  **original filenames** (`SAC-COWGIRL-REF1.png`, `MEUF-HANDBAG-V2.png`,
  `MONOPRIX-RAYON.png`, etc.) — these predate the `[brand]-[type]-[name]` convention and
  were not renamed here (uncertain 1:1 mapping to the Higgsfield element names in the
  registry; renaming blind risked mislabeling a reference). Match by the self-descriptive
  filename until someone confirms the exact rename mapping against
  `higgsfield-elements-registry.md`.
- `refs/carblazz/`, `refs/whiskeysmok/` — no refs yet, product not chosen for either brand.

## Usage in a ChatGPT scheduled task

Fetch the raw URL for the 2-3 files a given scene needs, e.g.:
`https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/onsimplifie/ons-pr-douchechien-gray.png`

Never fetch more than 3 references per single image/video generation (workflow rule). One
video = 3 storyboards covering every scene = one request, well under the 10-image-per-request
ChatGPT cap.

## Updating

When new refs are validated in `organic-ai-workflow`, copy them here under the matching
`refs/[brand]/` folder and push. Keep filenames identical across both repos so the naming
convention in the registry stays valid everywhere.
