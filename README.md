# StoryStage 2: Backstage assets

The 3D models StoryStage 2 ships in **Backstage**, its model library: Cast, Props, Set and Backdrops. Alongside the models are their storyboard sketches and the record of where each came from and on what licence.

The tools that build this repository live in [storystage/storystage2](https://github.com/storystage/storystage2), with the rules in its `docs/spec/17-backstage.md` and `docs/legal/licence-audit.md`.

## What is here

| Path | What it is |
|---|---|
| `sources/*.json` | The source lists. Each item gives its name, class, section, licence, credit line, its own page, and where to fetch it, pinned to a commit, a SHA-256 or an Arweave address. Edit these to add or change models. |
| `backstage.json` | The manifest StoryStage reads (generated). Every item has a section, a licence, a credit line and a source. |
| `models/` | The models (generated): binary glTF (`.glb`) or VRM (`.vrm`, kept byte for byte). |
| `sketches/` | Storyboard sketches for every model (generated), and `touch-up.md`, the list of sketches a person should look at. Hand-drawn replacements are named in `sketches/touch-up.json`. |
| `provenance.json` | What was fetched for each item, from where, with SHA-256s and the date (generated). |
| `sources-report.md` | A table for whoever reviews a build: sizes, skeletons, formats (generated). |

## How a build works

Nothing large is downloaded to anyone's computer.

1. Run the **Build Backstage** workflow (Actions tab), naming the storystage2 branch or commit whose tools to use.
2. It fetches every item in `sources/`, writes the generated files above, and opens a pull request.
3. **Before merging,** look at each new item's sketches for respectful, age-appropriate representation. StoryStage is for learners aged 6 to 13. Also check `sketches/touch-up.md` and `sources-report.md`.

Only models the licence audit allows are listed: CC0, CC BY with its credit line, or a written permission recorded in storystage2's `docs/legal/`. Alice's own models are added only for those CMU clears, and models drawn from The Sims 2's art never are.

## Licences

Every model and sketch keeps its own licence, recorded with its credit line in `backstage.json`. The source lists, the generated manifest and records, and the workflow are under the Apache License 2.0 (`LICENSE`), like StoryStage 2.
