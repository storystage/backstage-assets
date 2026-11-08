# Backstage sources: build report

Written by `tools/backstage-sources` (WP3.7). Before merging, look at each item's sketches (`sketches/<id>/`) for respectful, age-appropriate representation (licence audit, section 1), and at `sketches/touch-up.md`.

| Item | Name | Licence | Section | Triangles | Largest texture | Fits budget | Skeleton | Height | Format | Removed | Sketches |
|---|---|---|---|---|---|---|---|---|---|---|---|
| `kaykit/Biped/barbarian` | Barbarian | CC0-1.0 | cast | 5203 | 1024 | yes | mapped | 2.4 m | glTF | 4 parts, 35 clips | 16 |
| `kaykit/Biped/knight` | Knight | CC0-1.0 | cast | 4712 | 1024 | yes | mapped | 2.47 m | glTF | 7 parts, 35 clips | 16 |
| `kaykit/Biped/mage` | Mage | CC0-1.0 | cast | 4509 | 1024 | yes | mapped | 2.72 m | glTF | 4 parts, 35 clips | 16 |
| `kaykit/Biped/rogue` | Rogue | CC0-1.0 | cast | 4347 | 1024 | yes | mapped | 2.19 m | glTF | 5 parts, 35 clips | 16 |
| `kaykit/Biped/rogue-hooded` | Hooded rogue | CC0-1.0 | cast | 4005 | 1024 | yes | mapped | 2.25 m | glTF | 5 parts, 35 clips | 16 |
| `kaykit/Biped/skeleton-mage` | Skeleton mage | CC0-1.0 | cast | 4588 | 1024 | yes | mapped | 2.63 m | glTF | 39 clips | 16 |
| `kaykit/Biped/skeleton-minion` | Skeleton minion | CC0-1.0 | cast | 5288 | 1024 | yes | mapped | 2.17 m | glTF | 39 clips | 16 |
| `kaykit/Biped/skeleton-rogue` | Skeleton rogue | CC0-1.0 | cast | 5278 | 1024 | yes | mapped | 2.31 m | glTF | 39 clips | 16 |
| `kaykit/Biped/skeleton-warrior` | Skeleton warrior | CC0-1.0 | cast | 5934 | 1024 | yes | mapped | 2.59 m | glTF | 39 clips | 16 |
| `kaykit/Prop/mug` | Mug | CC0-1.0 | props | 426 | 1024 | yes | none | 0.55 m | glTF | — | 4 |
| `makehuman/Biped/p02` | Amara | CC0-1.0 | cast | 35368 → 19994 | 1024 | yes | mapped | 1.07 m | glTF | — | 16 |
| `makehuman/Biped/p03` | Kai | CC0-1.0 | cast | 34966 → 19988 | 1024 | yes | mapped | 1.1 m | glTF | — | 16 |
| `makehuman/Biped/p06` | Niamh | CC0-1.0 | cast | 38528 → 19988 | 1024 | yes | mapped | 1.53 m | glTF | — | 16 |
| `makehuman/Biped/p08` | Mei | CC0-1.0 | cast | 40454 → 19990 | 1024 | yes | mapped | 0.92 m | glTF | — | 16 |
| `makehuman/Biped/p11` | Jayden | CC0-1.0 | cast | 35354 → 19988 | 1024 | yes | mapped | 1.68 m | glTF | — | 16 |
| `makehuman/Biped/p14` | Leah | CC0-1.0 | cast | 37332 → 19989 | 1024 | yes | mapped | 1.44 m | glTF | — | 16 |
| `makehuman/Biped/p24` | Morgan | CC0-1.0 | cast | 33286 → 19990 | 1024 | yes | mapped | 1.76 m | glTF | — | 16 |
| `osa/Biped/astronaut` | Astronaut | CC0-1.0 | cast | 4350 | 1024 | yes | mapped | 1.36 m | VRM 0 | — | 16 |
| `osa/Biped/david` | David | CC0-1.0 | cast | 4156 | 1024 | yes | mapped | 1.58 m | VRM 0 | — | 16 |
| `osa/Biped/dino-kid` | Dino kid | CC0-1.0 | cast | 4576 | 1024 | yes | mapped | 1.24 m | VRM 0 | — | 16 |
| `osa/Biped/erika` | Erika | CC0-1.0 | cast | 4032 | 1024 | yes | mapped | 1.66 m | VRM 0 | — | 16 |
| `osa/Biped/kyle` | Kyle | CC0-1.0 | cast | 5144 | 1024 | yes | mapped | 1.67 m | VRM 0 | — | 16 |
| `osa/Biped/olivia` | Olivia | CC0-1.0 | cast | 3888 | 1024 | yes | mapped | 1.67 m | VRM 0 | — | 16 |
| `osa/Biped/polybot` | Polybot | CC0-1.0 | cast | 2130 | 1024 | yes | mapped | 1.06 m | VRM 0 | — | 16 |
| `osa/Biped/robert` | Robert | CC0-1.0 | cast | 4732 | 1024 | yes | mapped | 1.61 m | VRM 0 | — | 16 |
| `osa/Biped/rose` | Rose | CC0-1.0 | cast | 5622 | 2048 | **no** | mapped | 1.66 m | VRM 0 | — | 16 |
| `osa/Biped/teddy` | Teddy | CC0-1.0 | cast | 3068 | 1024 | yes | mapped | 1.65 m | VRM 0 | — | 16 |

Triangles and textures show fetched → shipped where the build reduced them to the section's budget (`ITEM_BUDGETS`, provisional until the reference devices have run). VRM files are kept byte for byte, so they aren't reduced. VRM 0.x avatars face -Z and must be turned by the stage's loader.

**Prompter catalogue:** about 2,231 of 12,000 tokens. `prompter-catalogue.txt` is exactly what Claude reads; check its descriptions with the sketches.
