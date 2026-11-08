# Backstage sources: build report

Written by `tools/backstage-sources` (WP3.7). Before merging, look at each item's sketches (`sketches/<id>/`) for respectful, age-appropriate representation (licence audit, section 1), and at `sketches/touch-up.md`.

| Item | Name | Licence | Section | Triangles | Largest texture | Fits budget | Skeleton | Height | Format | Removed | Sketches |
|---|---|---|---|---|---|---|---|---|---|---|---|
| `makehuman/Biped/p02` | Amara | CC0-1.0 | cast | 35368 → 19994 | 1024 | yes | mapped | 1.07 m | glTF | — | 16 |
| `makehuman/Biped/p03` | Kai | CC0-1.0 | cast | 46522 → 19988 | 1024 | yes | mapped | 1.1 m | glTF | — | 16 |
| `makehuman/Biped/p06` | Niamh | CC0-1.0 | cast | 48888 → 19991 | 1024 | yes | mapped | 1.53 m | glTF | — | 16 |
| `makehuman/Biped/p08` | Mei | CC0-1.0 | cast | 40454 → 19990 | 1024 | yes | mapped | 0.92 m | glTF | — | 16 |
| `makehuman/Biped/p11` | Jayden | CC0-1.0 | cast | 45714 → 19995 | 1024 | yes | mapped | 1.68 m | glTF | — | 16 |
| `makehuman/Biped/p14` | Leah | CC0-1.0 | cast | 48888 → 19993 | 1024 | yes | mapped | 1.44 m | glTF | — | 16 |
| `makehuman/Biped/p24` | Morgan | CC0-1.0 | cast | 44842 → 19994 | 1024 | yes | mapped | 1.76 m | glTF | — | 16 |

Triangles and textures show fetched → shipped where the build reduced them to the section's budget (`ITEM_BUDGETS`, provisional until the reference devices have run). VRM files are kept byte for byte, so they aren't reduced. VRM 0.x avatars face -Z and must be turned by the stage's loader.

**Prompter catalogue:** about 2,225 of 12,000 tokens. `prompter-catalogue.txt` is exactly what Claude reads; check its descriptions with the sketches.
