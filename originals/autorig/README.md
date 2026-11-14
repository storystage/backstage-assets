# Found characters to rig

Characters found with no skeleton the joint map can read. The **Rig found characters** workflow gives each one a skeleton with storystage2's `tools/backstage-sources/blender/autorig.py`, and `sources/sketchfab.json` then adds them to Backstage (spec 17, section 3). `rigs.json` lists them, with any joints given by hand.

| File | Model | Maker | Licence | Downloaded | SHA-256 of the download |
|---|---|---|---|---|---|
| `Granny.glb` | [Old Village Granny](https://sketchfab.com/3d-models/old-village-granny-0f2d99b04b1c4918a41c3834a0285891) | Imagine (Imagineis) | CC BY 4.0 | 14 Nov 2026, the original format, through the owner's sign-in | `06661fcf71c084ef99423ecf0f0098ad8f999d04e98fed00b49f85cfa7b951f5` (zip) |
| `CAPVERM.fbx` | [Capuchinho Vermelho (Little Red Riding Hood)](https://sketchfab.com/3d-models/capuchinho-vermelho-little-red-riding-hood-38f5e17dbd8745bc8ac865610fd859aa) | Rafasilart (leafar112) | CC BY 4.0, with Sketchfab's NoAI flag | 14 Nov 2026, the original format, through the owner's sign-in | `305660915df6c5d39cad0fc4590d2e0720cee142dff46abfcdc15946caded846` (zip) |

- **Why they were chosen:** both were checked against storystage2's `docs/backstage/storybook-cast-brief.md`, section 4. Each is its maker's own design, not a copy of a film.
- **The NoAI flag:** the model may not be used to train or feed generative AI. StoryStage does neither with models; the Prompter is sent only the catalogue's words.
- **The Granny's own skeleton is replaced:** its bones are unnamed, it has no feet, and its legs end in IK handles.
