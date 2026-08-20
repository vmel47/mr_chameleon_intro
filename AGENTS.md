# MR. CHAMELEON — CANONICAL AGENT ENTRY

This file is the common entry point for Codex, Claude, Gemini and other agents.

Read in this order before changing the project:

1. `GENERATION_DATABASE.md` — full-reset database for prompts, images, references and assets.
2. `PRODUCTION.md` — current reshoot status and next work.
3. `SCENE_SHORTLIST.md` — canonical scene order and new numbering.
4. `SCRIPT.md` — story and narration source.
5. `LOOK_REFERENCE.md` — approved light, weather, palette and moving-image references.
6. `ASSET_REGISTRY.md` — character, location and prop identities.
7. `prompts/current/README.md` — preserved prompt candidates from before the reset.

## Current production state

The project entered a full reset on 2026-08-20. Every video, image, starting frame, location sheet,
character sheet, prop sheet and reference asset must be generated again. Existing material is only a
candidate prompt or visual orientation source. Never mark an asset complete because a file already exists.

Active IDs are sequential `01–18`. Legacy IDs (`00`, `02B`, `03A`, `F0–F8`) exist only in archived
material and in the migration map in `SCENE_SHORTLIST.md`.

## Non-negotiable rules

- Part 1 is strict first-person POV: zero visible characters or body parts. The camera is a human body
  with mass, footfall, collision and contact physics.
- Narration is recorded separately. Video prompts always say: `No narration. No voices. Nobody speaks.`
- Use `@Image 1`, `@Image 2`, `@Video 1` exactly. Never use filenames as in-prompt reference tags.
- Generation prompts are delivered in full, in English, without placeholders.
- Current picture lock: late spring, 1:00 PM, bright mostly sunny daylight, pale-blue sky, a few small
  separated clouds, full new green foliage, readable shadows, no overcast blanket.
- Preserve the approved color and movement language in `LOOK_REFERENCE.md`.
- One reference has one declared job. Do not let a location reference inherit composition unless wanted.
- For a changed prompt, record what changed and the result. Prefer one surgical change per iteration.
- Never overwrite a canonical prompt with a speculative version. Put experiments under
  `_archive/legacy-prompts-pre-reshoot/` or a clearly named work file until approved.

## Project-local skills

- `.agents/skills/lira-image-prompts/SKILL.md`
- `.agents/skills/chameleon-shotlist/SKILL.md`
- `.agents/skills/chameleon-acting/SKILL.md`
- `.agents/skills/cinedance-higgsfield/SKILL.md`

These wrappers adapt the supplied source skills to this film. Their `references/` folders preserve the
original material for audit; project rules override generic defaults.

Useful process practices extracted from the separate template project are summarized in
`docs/HELL_GRIND_PRACTICES.md`; that external project is evidence, not canon.

## Git and cleanup

Preserve unrelated user changes. Old prompts are archived, not silently deleted. Do not commit generated
video binaries unless the user explicitly asks; existing tracked media remains untouched.
