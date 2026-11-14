# Backstage sources: build report

Written by `tools/backstage-sources` (WP3.7). Before merging, look at each item's sketches (`sketches/<id>/`) for respectful, age-appropriate representation (licence audit, section 1), and at `sketches/touch-up.md`.

| Item | Name | Licence | Section | Triangles | Largest texture | Fits budget | Skeleton | Height | Format | Removed | Sketches |
|---|---|---|---|---|---|---|---|---|---|---|---|
| `sketchfab/Biped/grandmother` | Grandmother | CC-BY-4.0 | cast | 617 | 256 | yes | mapped | 1.55 m | glTF | — | 16 |
| `sketchfab/Biped/red-riding-hood` | Little Red Riding Hood | CC-BY-4.0 | cast | 11596 | — | yes | mapped | 1.2 m | glTF | — | 16 |

Triangles and textures show fetched → shipped where the build reduced them to the section's budget (`ITEM_BUDGETS`, provisional until the reference devices have run). VRM files are kept byte for byte, so they aren't reduced. VRM 0.x avatars face -Z and must be turned by the stage's loader.

**Prompter catalogue:** about 7,473 of 12,000 tokens. `prompter-catalogue.txt` is exactly what Claude reads; check its descriptions with the sketches.
