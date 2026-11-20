# Gobkit originals

These are the 30 animals of Gobkit's three free packs (Gobkit / Alsomind Tech Co., Ltd., [gobkit.com/freebies](https://gobkit.com/freebies)), each pack's own `LICENSE.txt` dedicating them to the public domain under **CC0 1.0 Universal**. The owner chose to ship all 30 after a close look (20 Nov 2026). Each file is kept here exactly as it came in its pack, renamed to plain English, so the build can fetch it pinned to the commit that added it. Each file's SHA-256 is in the table.

**The makers' metadata is stripped by the build.** Gobkit's files carry its marketing in their glTF `extras`, including, in Vol. 5, a line promoting AI tools, while calling the models hand-authored. The build clears every model's `extras` (`stripExtras`, storystage2's `tools/backstage-sources`), so none of it ships. Each model is credited "<Animal> by Gobkit, <pack> (CC0)" in `backstage.json` (storystage2's `docs/legal/licence-audit.md`).

Every model shares one template rig with one bone a leg, so they're prop only on the stage and move with their own clips. In Vol. 1 and Vol. 2 the four actions are baked onto one 120-frame track at 24 fps (idle 0–29, attack 30–59, dead 60–89, walk 90–119), which the source list slices; Vol. 5 names them.

| File | Pack | In the pack | SHA-256 |
|---|---|---|---|
| `anglerfish.glb` | Free Animal Pack | `Anglerfish.glb` | `8d07bd212527ec2e0ba2d42367dcf65ae91eb35538fb3b57a2bfd8e1d8ac60fa` |
| `bat.glb` | Free Animal Pack | `Bat.glb` | `1a4317609094c64d3f751adb9150df628aaf7902f7440174afcb642c30e0e072` |
| `corgi.glb` | Free Animal Pack | `Corgi.glb` | `95cd2c4d53d70ee9dd2e1329dcb6de7d4a725301d504a4f2f00ecb34dc1a0851` |
| `duck.glb` | Free Animal Pack | `Duck.glb` | `6550a5807bc83edbadec0759155b3d9242b6ce6b980213a3872b49db80dfd579` |
| `hippo.glb` | Free Animal Pack | `Hippo.glb` | `6a911f141482994f890911429e0863353a10fb567822e553b91a273e0fb1d5bd` |
| `jellyfish.glb` | Free Animal Pack | `Jellyfish.glb` | `b0625fa8a726c594afc47a317b997d98da97b163fe551b15e32262854c99ea46` |
| `platypus.glb` | Free Animal Pack | `Platypus.glb` | `9d5e67a5147dabe04c5e3f677b10aa8042ed4efe337378bccc3b7dd6338d99b6` |
| `red-panda.glb` | Free Animal Pack | `Red.glb` | `412df0483b64f3339dfa8405c75c194effb90b72bb279bd233bfb4653d70c7a8` |
| `rhino.glb` | Free Animal Pack | `Rhino.glb` | `65cea4e6533e50d00efdde03de3e792f7337736d97b8f8c8f8b12c4bc0ee5017` |
| `shark.glb` | Free Animal Pack | `Shark.glb` | `0fc450c99f0fd9f2e5d774ef58cd42b8d8d927bed138444254204b366595dc42` |
| `bee.glb` | Free Animal Pack Vol. 2 | `Bee.glb` | `e1ad6d56297c4f9c04c6e2978df3d1fd232de19acce9c0a4eb4d5b150bb821aa` |
| `blue-bird.glb` | Free Animal Pack Vol. 2 | `Blue.glb` | `79769b2ef413ca7532a94c8332cbc22664a12a4be07e940fd58bd2194c2f35c8` |
| `boar.glb` | Free Animal Pack Vol. 2 | `Boar.glb` | `b1ffefd7e63870c50e79ef9c5ce892e403d66189147a9bbfc00bb5f442841377` |
| `pufferfish.glb` | Free Animal Pack Vol. 2 | `Fugu.glb` | `d9cafd1a354abc92f0e20e3f7fa78efa90402d4e8193ec21c14bea6b3eb921c7` |
| `goat.glb` | Free Animal Pack Vol. 2 | `Goat.glb` | `6e5e7524bec0373445136b6c814d93f57992d094a1b72fce27a0040bc4f9830b` |
| `marmot.glb` | Free Animal Pack Vol. 2 | `Marmot.glb` | `6771dc7717702492845b1cd3c40702a8edadf6df038f2efef2eaee9c43287be6` |
| `owl.glb` | Free Animal Pack Vol. 2 | `Owl.glb` | `b0d06b3319dee88393f339a03c060178e453f91bd422a997c1ac3cd63e5661b3` |
| `rat.glb` | Free Animal Pack Vol. 2 | `Rat.glb` | `0a5b9d57a5a7b3362850dc0ebe84ce113ce48e10e553eba79f86294586793985` |
| `seal.glb` | Free Animal Pack Vol. 2 | `Seal.glb` | `4ffe3fe0536e1c380ae2995b8012e90417094c96114bf2be61bc27780a1645ef` |
| `whale.glb` | Free Animal Pack Vol. 2 | `Whale.glb` | `2d46053e4c4a4287dc20019e68b1072ea880ef1ea28f5ec85f9f9eac212153c7` |
| `chick.glb` | Free Animal Pack Vol. 5 | `Chick.glb` | `c74b1e07f052eb4a75b959abe5691cdf937971c18bfc58fab36536a4abf7c090` |
| `dingo.glb` | Free Animal Pack Vol. 5 | `Dingo.glb` | `75e8bfe22ecffe2a96dc032b6fa15b57a07c777826b5c6e939f649643e9046ce` |
| `koala.glb` | Free Animal Pack Vol. 5 | `Koala.glb` | `41e008751c798c662560fc0da4711c1beb8a69d9ac515a72cb812020448f7f6c` |
| `mole.glb` | Free Animal Pack Vol. 5 | `Mole.glb` | `d2abd76c175dc910a1b836cabe1cb18836ef3c41f7c331d0412cd0795668b0d8` |
| `narwhal.glb` | Free Animal Pack Vol. 5 | `Narwhal.glb` | `f3497a82d21198bc19be7dee07718d95bc9db29d6191d61cb51c8720cc7d9769` |
| `quail.glb` | Free Animal Pack Vol. 5 | `Quail.glb` | `462d5980c6ae0ee922e5ddd20eacccda4ff08bdd1d5baf0d767085179b6feeb1` |
| `scorpion.glb` | Free Animal Pack Vol. 5 | `Scorpion.glb` | `6e50166b3efe1e95e714009125e332af89af575d5cadebfce40db08dac6eab0a` |
| `seagull.glb` | Free Animal Pack Vol. 5 | `Seagull.glb` | `2909080ed283b9c4eb4cde5d46743bd623cd26e37a868ba62a0db5ca1d591eab` |
| `sea-otter.glb` | Free Animal Pack Vol. 5 | `SeaOtter.glb` | `27f54f879846af5ca48419da73a9e92e3b8c107b0cb0f0eabf8c89c99e99569f` |
| `tasmanian-devil.glb` | Free Animal Pack Vol. 5 | `TasmanianDevil.glb` | `e02ec4e264812692c86528cb36e1d6c2fbb3447aefea184b279f834f40f1b67a` |
