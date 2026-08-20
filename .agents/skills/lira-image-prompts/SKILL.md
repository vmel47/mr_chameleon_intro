---
name: lira-image-prompts
description: Build or repair image-generation prompts for Mr. Chameleon characters, locations, props, location sheets, and surgical edits across Soul Cinema, Soul 2.0, Nano Banana Pro, Seedream and GPT Image workflows.
---

# LIRA image prompts — Mr. Chameleon adaptation

Read `AGENTS.md`, `LOOK_REFERENCE.md` and `ASSET_REGISTRY.md` before writing an image prompt.

## Route by job

- New character/casting sheet: Soul 2.0 or Cinema Studio AI Cast.
- New location without a reference: Soul Cinema.
- Surgical edit inside an existing frame: Nano Banana Pro first.
- New viewpoint of an established location: GPT Image 2.
- Use another full-image pass only when the previous route cannot perform the change; repeated full passes
  destroy texture and drift identity.

Model names are routing hints, not permanent truth. If the user names a model, adapt to that model.

## Prompt rules

1. State the job and camera anchor first. Use observable materials, geometry, wear, weather and light.
2. Preserve the project lock: late spring, 1:00 PM, bright mostly sunny daylight, pale-blue sky, a few
   separated clouds, full new green foliage and readable shadows.
3. For edits, split the prompt into `CHANGE` and `PRESERVE EXACTLY`. Describe what replaces the removed
   element, not only what must disappear.
4. One reference has one role. State what identity, architecture, material or palette it controls and what
   composition it must not transfer.
5. Location sheets use useful future camera positions and 3/4 geometry. Avoid duplicate angles.
6. Character identity sheets stay neutral: large 3/4 portrait, clean face texture and catchlights, plus body
   views. Scene lighting and grade belong to scene assets, not identity sheets.
7. Separate state variants: costume, damage, wetness, time of day and prop state each get their own asset.
8. For exact text, quote it exactly. For buildings where text is absent, fill the roofline with ordinary
   architecture rather than a negative-only instruction.
9. Output the complete English generation prompt, then at most a short parameter line if the UI needs it.

For deeper model-specific patterns, consult `references/SOURCE_LIRA.md`; project rules above override it.
