# Blender Studio's characters (WP3.8)

Characters from [Blender Studio](https://studio.blender.org/characters/) that are marked Free, under
**CC BY 4.0**. Each is credited "(CC) Blender Foundation | studio.blender.org".

`studio.json` lists the ones that ship: each one's page, download link and the download's sha256. The
**Blender Studio characters** workflow fetches each file, checks it against the hash, and exports it
with storystage2's `tools/backstage-sources/blender/studio.py`. That step reduces the character to the
cast's budget (20,000 triangles, a 1,024-pixel picture), bakes its look, including hair and fur, into
the picture, and gives it our skeleton, placed where its own bones are. The files themselves are never
committed.

## Tested, 15 Nov 2026 (the owner chose Spring and Autumn)

| Character | Result |
|---|---|
| **Autumn** (Spring, 2019): a small dog | **Ships.** 20,679 to 19,599 triangles, fur baked into the picture; all 28 joints mapped (quadruped). The owner approved her. |
| **Spring** (Spring, 2019): a young shepherdess | **Left out.** Her face, eyes and clothes survive, but her hair is particle hair. Reduced, it becomes a tight cap without her ponytail and side locks. Turning it into a few thick locks didn't work headless: Blender gave no positions for her head hair's strands. The owner chose: if locks still looked wrong, she stays out. |
