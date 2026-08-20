# MR. CHAMELEON — STYLE PREFIX & ENVIRONMENT LOCK

**Two constants.** Both live here and nowhere else, so one edit updates every asset and every shot in the film. Never retype them, never paraphrase them, never let a shotlist or an asset prompt carry its own copy.

---

# 1 · ENVIRONMENT LOCK

**Paste into every location asset prompt and every exterior or daylight-interior video prompt.** This is what makes the city read as one place on one day instead of eleven separate generations. It has to hold even when no city reference image is attached.

```
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: bright mostly sunny pale blue with a few small separated soft-white clouds and large blue gaps; never a continuous overcast sheet.
Sun: use the scene-group sun direction below; keep one coherent world azimuth inside each continuous sequence.
Shadows: softly defined and readable, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: scenes 01–02 forest opening — 11:30 AM; later Pripyat daylight material — 1:00 PM.
```

**Forest 01–02 sun lock:** 11:30 AM. Soft sun high through the trees from the left side of the walking
axis, near the upper-left edge of a forward view. The disc is not required in frame; filtered side light and
dapple establish it. Both forest clips use the same world azimuth.

**Later Pripyat sun lock:** 1:00 PM. Preserve the established 1:00 PM direction consistently across the
city, park, residential and daylight-interior sequences.

**The basement is the one exception** — no daylight reaches it. It carries its own light logic: one dim overhead fixture above the work table, the rest of the room falling away into shade. The environment lock is not pasted into basement prompts.

**Why lightly broken cloud and not flat overcast.** Flat grey is easy and dead. A mostly sunny sky with a few
separated clouds gives gentle moving light across a four-minute film while preserving a pale-blue sky and
readable sun direction. The sun never blows out a frame; passing thin cloud only softens it briefly.

---

# 1B · COLOUR LOCK

**The single biggest consistency problem in this film is grade drift** — one clip comes out bright and
pleasant, the next comes out dark and cold, and no amount of colour work in post glues them back together
cleanly. Grading fourteen separately generated clips into one look is hours of work. Getting them out of
the model already matching is a paragraph.

**Paste this block into every prompt — video and location sheet alike, including the basement.**

```
COLOUR AND GRADE — identical in every shot of this film:
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast
of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No
teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky
retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural late-spring daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across
the entire frame.
```

**The vignette is a separate, repeated ban.** Some generations produce it and some do not, which is worse
than all of them having it — it cannot be matched in post. Besides the block above, every prompt carries
`no vignette, no edge darkening, even exposure corner to corner` in its `POSITIVE CONSTRAINTS` as well. Two
mentions, because one is not enough.

**Basement colour exception.** The basement keeps the same neutral, medium-contrast, readable-shadow colour
science, but it does not inherit outdoor 5600K daylight, sky colours or foliage ratios. White-balance its
single practical fixture to neutral without a green, blue or sepia cast.

---

# 1C · ROUTE LOCK — the opening walk

Generations 00, 01 and 02 are one continuous walk on one route. They kept coming out as three unrelated
places at three different times of day. This is the map.

```
ROUTE — locked across generations 00, 01 and 02:
One continuous walk along one route: deep forest, out to a road, then along that road to the city sign.
00 — deep inside the forest. Canopy closed overhead, no sky visible, no road anywhere in frame. This is
     the darkest shot of the three.
01 — the same forest thinning out. The canopy opens, sky appears, the light steadily increases, and at
     the end an asphalt road.
02 — on that same road, walking along it. The city sign stands on the right-hand verge.
The light gets BRIGHTER from 00 through 01 to 02 and never darker. The forest is the closed dark part of
the walk; the road is the open bright part. Same asphalt, same verges, same direction of travel, same
afternoon.
```

**This is why the current forest clips fight each other.** The light was running backwards — bright under
the canopy, dark at the exit. In a real forest it is the other way round, and the audience feels it even
if they cannot name it.

---

# 1D · COLLIDER LOCK

**The problem is one thing and only one thing: the camera has no collider.** A big bush stands in the path,
the walk goes straight through it, and not a leaf moves. The shot stops being a person and becomes a camera
flying through geometry, and the audience reads it as fake before they can name why.

**This is not a licence to invent obstacles.** Nothing gets staged in front of the camera. No scripted
branches, no timed events, no hand reaching in to push anything aside — there is no character yet and there
is nothing to push with. The walk is clean and the way ahead is open. Trees and undergrowth live at the
sides of frame and pass by, and that is all.

**The rule is only about what happens *if* something ends up in the path.** Then it has to react. That is
the whole fix.

**Paste into every prompt where the body moves. Not the aerial, not the held frames, not the basement.**

```
COLLIDER — the camera is a body, not a flying camera
The camera has a physical body attached to it. The body is never seen, but it occupies space and it has
mass, and nothing in the world passes through it.
Do not place anything in the path. Do not invent branches, bushes or obstacles in front of the camera — the
way ahead stays clear and open, and the vegetation lives at the sides of frame, trunks and undergrowth
passing by as the walk goes on.
But if anything does end up in the path — a bush, a clump of tall grass, a low branch, thick undergrowth —
it reacts. It bends, shakes and folds away where the unseen body meets it, and it recovers a beat later. It
is never passed through as if it were not there.
Grass and undergrowth underfoot bend and flatten where each step lands, then spring back after the foot
lifts, one beat behind the walk. Dust, pollen and leaf litter lift from the ground where the foot lands.
No arms, no hands, no shoulders, no legs and no feet ever enter frame. What is seen is the vegetation
reacting, never the body that made it react.
No clipping. Nothing intersects or passes through the camera, and nothing touches the lens.
```

**Interiors get a variant** — same law, different objects: branches grown in through broken windows,
saplings on the steps, fallen plaster, glass and dry leaves underfoot.

**Character shots get a variant** — 06 and 09, where he is in frame: grass parts around his shins and
closes behind him, leaving a flattened track; nothing intersects his body or his clothing; he never changes
pace for it and never looks at it. 03 carries both, split at the hard cut.

**The held frames get nothing** — 04A, 05A and 05B have no walk, so there is no collider to write.

**Three mentions per prompt, like the vignette.** Its own block after `ACTION TIMING`, a clause in the
`Physics:` line of the style block, and a line in `POSITIVE CONSTRAINTS`. One mention gets dropped.

**The two-beat rule is the whole trick.** Vegetation that bends *and stays bent* looks as wrong as
vegetation that does not move at all. What reads as real is the recovery — springing back one beat behind
the body.

---

# 2 · STYLE PREFIX

**Paste word for word at the end of every video prompt, in the `STYLE` slot.**

```
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: physically grounded camera appropriate to the shot; natural motivated light only; composed documentary frames with real mass and inertia.
Lighting: Late spring turning into early summer, bright mostly sunny with a pale-blue sky, a few small separated soft-white clouds and large blue gaps. Use the exact time and sun direction from the active scene-group environment lock: 11:30 AM for forest scenes 01–02, 1:00 PM for later Pripyat material. Daylight interiors are lit only by window light falling naturally into the room. No unmotivated fill from the camera side.
Color: 60:30:10 — 60% new-growth birch and grass green, 30% weathered concrete grey and pale sky, 10% rust-orange oxidised metal.
Camera: Physical cine lens. 180° shutter motion blur.
Surfaces: Material-level realism — flaking paint, lichen crust, dust-matte glass, wet concrete stain, rusted steel, decades of settled dust on horizontal surfaces. Nothing looks recently placed.
Skin: Pore-level realism — vellus hair, asymmetric moles, capillary flush, pore-shadow matching on-set light.
Acting: micro-pauses before reactions, precise eye-line, wet living eyes with catch-lights, visible breath and chest rise.
Physics: Gravity and inertia respected — mass has real weight, correct contact shadows. No floating props. Nothing passes through anything — no clipping, no intersection; whatever is touched bends, shakes and recovers a beat later.
Vegetation: Birch and poplar reclaiming the built environment — saplings through asphalt, moss on steps, branches through broken glass, tall grass across every open space, all of it moving on real wind.
Composition: Rule of thirds + golden ratio.
Continuity: Characters, props, environment identical across every cut. No identity drift.
Technical: 24fps smooth motion. 8K detail. No jitter. No flicker. No vignette, no edge darkening, even exposure corner to corner.
Audio: Environmental SFX only. No music. No subtitles. No narration. No voices unless written in the AUDIO block.
```

## OPTICS LOCK

- Every embodied first-person POV shot uses a **47° diagonal field of view**: a spherical normal-lens
  character with natural human spatial perception, straight lines and no wide-angle stretching.
- Every standing or walking embodied POV shot keeps the camera optical centre **1.8 metres above the local
  supporting surface**. It rises with terrain and stairs but never drifts relative to the body. A scripted
  seated POV is the only height exception and stays at its natural seated level.
- The focal length never changes inside a take. Scale changes only through physical camera movement.
- Use deep practical focus unless a scripted close-up explicitly requires otherwise. No fisheye, anamorphic
  streaks, barrel distortion, lens flare, artificial shallow depth of field or unexplained lens drift.
- Aerial geography and the final telephoto reveal are motivated exceptions. Their focal lengths may differ
  by shot, but each shot locks one lens and preserves the same neutral colour, contrast and exposure logic.
- Starting-frame image prompts use the same visible field of view as the video they feed. Do not add a camera
  brand or prestige-lens name unless it produces a required visible result that cannot be described directly.

## CLOSING TECHNICAL TAGS

Every prompt ends with this line after the style block, duration filled in:

```
Photoreal. NON-IP. 16:9. [N]s. SFX only. NO CGI. Cinematic. Present tense. Short sentences.
```

---

# 3 · AUDIO — THIS EPISODE

**There is no rule against generating sound.** Sound gets generated, and it gets used. The decisions below
are about *this* film, not about the pipeline. Later episodes may work differently — dialogue included.

| Layer | How it is made | Used in the film |
|---|---|---|
| Environmental sound — wind, footfall, structure, birds, water | **Generated with the shot.** Keep it. | Yes |
| The scream in generation 11 | **Generated**, a real scream, from the shot itself | Yes |
| Narration | **Not generated.** Spoken by a person and recorded separately. See `NARRATION.md`. | Yes |
| Music | Not used anywhere | No |
| Dialogue | There is none in this film — nobody in the story speaks. This is a story fact, not a technical limit. | No |

## What every prompt says, and why

```
Diegetic environmental sound only — <the specific sounds of this place>. No music. No narration.
No voices. Nobody speaks.
```

`No narration` is there because the narration is recorded separately and a generated voice-over on top of
it is unusable. `Nobody speaks` is there because without it the model gives silent characters mumbling,
chuckles and half-words, and moves their mouths for it. Both lines are protecting the picture as much as
the track.

**Generation 11 is the exception** and the scream is written out in full — because a written scream is a
*physical* instruction. It gets a throat working, tendons standing out, a chest emptying, shoulders
climbing. Delete the line and you get a mouth opening.

## Post

Generated ambience is the bed; spot effects and a continuous room tone per location are layered on top in
post — one shared atmosphere under the whole film is what glues separately generated shots into one space
even where the picture drifts. Narration sits above it, dry and close. No music at any point.

---

# 4 · BAN DICTIONARY

Grow this list every time a shot fails because of wording.

| Avoid | Use instead |
|---|---|
| dark | low key |
| jolting | rapid motion |
| creepy / scary / horror | *(describe the physical event instead)* |
| post-apocalyptic | abandoned for decades, reclaimed by vegetation |
| ghost town | empty city, no people anywhere |
| nobody moves | held still, breath the only motion |
| overcast / grey day | bright mostly sunny pale-blue sky, a few separated small clouds, high soft sun |
| autumn, golden leaves | new green, late spring |
| any age or age word, in any language | role, clothing, action |
| softshell, technical fabric, performance shell | cotton canvas, cotton shirting, worn leather |
| cargo pants, tactical, low-profile pack | heavy canvas trousers, canvas bag on a leather strap |
| a matching olive outfit | every garment a different faded shade, nothing matches |
| hiking boots, combat boots | short black rubber boots |
| quilted, padded, lined, parka | thin, worn open, sleeves pushed up — it is a hot afternoon |
| *(silence about contact)* — the model walks through bushes untouched | the CONTACT LOCK block, all three mentions |
| staged branches and bushes in the path | nothing placed in the path — the collider rule covers whatever happens to be there |
| a hand or arm pushing anything aside | no limbs in frame; the plant reacts, the body that moved it is never seen |
