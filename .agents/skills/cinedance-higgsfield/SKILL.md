---
name: cinedance-higgsfield
description: Write or repair complete Seedance/Higgsfield video prompts for Mr. Chameleon with reference hierarchy, spatial blocking, embodied camera motion, timing, physics, lighting, audio and continuity locks.
---

# CINEDANCE Higgsfield — Mr. Chameleon adaptation

Read `AGENTS.md`, the scene's file under `prompts/current/`, `LOOK_REFERENCE.md` and relevant assets first.

## Prompt order

Use only the sections the shot needs:

1. character-count / POV header
2. `SCENE CONTEXT`
3. `ACTIVE REFERENCES` with exact `@Image N` / `@Video N` roles
4. `LOCATION MAP`
5. `FIRST FRAME AND SPATIAL BLOCKING`
6. `FORMAT MODE`
7. `OPTICS`
8. `CAMERA`
9. `ACTION TIMING`
10. `COLLIDER` and `PHYSICS`
11. `LIGHTING`
12. `AUDIO`
13. `STYLE`, `QUALITY`, targeted `POSITIVE CONSTRAINTS`

## Hard rules

- Final prompt is a sealed current-shot document. Remove stale tags, prior-scene summaries and unused props.
- State every active reference's one job. A location reference does not automatically dictate the first frame.
- Lock frame-one geography before describing motion. Specify camera side, height, distance, orientation,
  route, thresholds and end state.
- One dominant camera behavior per beat. No lens drift or unexplained transitions.
- Camera instructions describe a physical operator/body. Walking includes heel contact, weight transfer, hip
  shift, toe push-off and subtle head settling. Vegetation and loose matter react to body collision.
- Every door remains still until physical contact causes handle/latch/hinge motion.
- Timed actions must fit the duration. A room change requires crossing the actual doorway; a pan cannot create
  a new room.
- Define one motivated light source and direction. Preserve the project weather and 1:00 PM daylight lock.
- Diegetic SFX only. No music, narration, voices, subtitles or captions unless the scene explicitly requires
  character dialogue.
- Use concise local failure locks after describing the desired state. Avoid generic negative dumps.
- Output only the full English prompt unless the user requests explanation.

Optics should be expressed by visible result and field of view when useful. The project normally uses a
natural 47° view for embodied POV; do not force an elaborate lens module into every location prompt.

The complete supplied source is preserved at `references/SOURCE_CINEDANCE.md`; these project rules override
its generic defaults.
