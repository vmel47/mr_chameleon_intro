---
name: chameleon-shotlist
description: Turn Mr. Chameleon script beats into a readable shotlist, reshoot plan, asset checklist, prompt queue, or continuity-aware production order.
---

# Chameleon shotlist

Read `AGENTS.md`, `SCENE_SHORTLIST.md`, `SCRIPT.md`, `PRODUCTION.md`, `LOOK_REFERENCE.md` and
`ASSET_REGISTRY.md` first.

## Workflow

1. Identify the dramatic function and exact duration of each scene.
2. List required characters, location states, props, starting frames and missing assets.
3. Write spatial blocking before camera language: start position, route, thresholds, screen direction and end
   state. For multiple characters, include distances, gaze lines and power changes.
4. Break performance into visible micro-beats. Every camera change or cut must serve a new piece of
   information.
5. Select the smallest coverage that tells the story. Credits are limited; do not add beauty shots for variety.
6. Mark continuity anchors, likely generation failures and the cheapest repair route.
7. Update `SCENE_SHORTLIST.md` and `PRODUCTION.md`; do not create a separate conflicting status table.

## Project overrides

- Use sequential scene IDs `01–18`.
- Default format is 16:9. Durations come from the scene, not a universal 15-second limit.
- Generation prompts are English. Human-facing planning is Russian unless requested otherwise.
- Part 1 has zero visible characters and strict embodied first-person POV.
- Location starting frames are requested only when the scene needs them.
- Output Markdown by default; HTML is only produced when the user explicitly asks.

The original supplied package and its detailed blocking, prompt-density and micro-beat references are kept
under `references/shotlist-builder/`. Its hardcoded Chinese, 21:9, 15-second and practical-light defaults are
not project rules.
