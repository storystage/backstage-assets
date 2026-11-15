# Backstage sources: build report

Written by `tools/backstage-sources` (WP3.7). Before merging, look at each item's sketches (`sketches/<id>/`) for respectful, age-appropriate representation (licence audit, section 1), and at `sketches/touch-up.md`.

| Item | Name | Licence | Section | Triangles | Largest texture | Fits budget | Skeleton | Height | Format | Removed | Sketches |
|---|---|---|---|---|---|---|---|---|---|---|---|
| `blender-studio/Quadruped/autumn` | Autumn | CC-BY-4.0 | cast | 19599 | 1024 | yes | mapped | 0.41 m | glTF | — | 4 |

Triangles and textures show fetched → shipped where the build reduced them to the section's budget (`ITEM_BUDGETS`, provisional until the reference devices have run). VRM files are kept byte for byte, so they aren't reduced. VRM 0.x avatars face -Z and must be turned by the stage's loader.

**Prompter catalogue:** about 7,914 of 12,000 tokens. `prompter-catalogue.txt` is exactly what Claude reads; check its descriptions with the sketches.
