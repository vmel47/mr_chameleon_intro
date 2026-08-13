# MR. CHAMELEON — SHOTLIST & VIDEO PROMPTS

**15 generations · 4:16 of raw material · 16:9 · Seedance 2.5 (Higgsfield), 20s max per generation**

**Generate everything. Nothing is trimmed at the prompt stage.** Some blocks deliberately overlap — 02B and the opening of 03 both cover the entry into the city. Final length and which coverage is used are decided in the edit, not here.

One generation per script block. Beats live inside `ACTION TIMING`, by the second. Where a block genuinely changes camera position, it is written as a controlled multi-shot with an explicit `HARD CUT` — still one generation.

## HOW TO USE

1. **Every prompt below is complete.** Copy the whole block and paste it. Nothing to assemble, nothing to look up in another file.
2. Duration and aspect ratio are UI settings, not prompt text.
3. Nothing generates until every tag in `ASSET_REGISTRY.md` is `LOCKED`.
4. One line changed per iteration. Everything into the log at the bottom.
6. Shots that are not part of the film's spine live in `OPTIONAL_SHOTS.md`. Nothing there is needed for the cut to work.
5. If the environment or style constants ever change, edit `STYLE_PREFIX.md` first, then re-inline them here — they are duplicated into every prompt on purpose, so that a prompt is copy-and-go.

## WALK LOCK — the same gait in every shot he moves in

He walks **slowly, calmly and at an unhurried, leisurely, cinematic pace** — never brisk, never purposeful,
never hurried. Long relaxed stride, a clear pause of weight on each foot, the pace never changing anywhere
in a shot or between shots. He is a man walking around the place he grew up in, not a man going somewhere.

The camera line is identical in every walking prompt:

```
The camera is a walking body moving at a slow, calm, unhurried gait, not a rig: gentle vertical rise
and fall on each stride, small lateral sway, organic imperfect correction after every step. It never
stabilises into a glide.
```

This is already inlined in generations 01, 02, 02B, 03, 06, 07 and 08. If a new walking shot is ever added,
paste it there too — the walk is as much a character trait as the face.
7. **Generated environmental sound is kept and used**, including the scream in generation 11. Only the narration is recorded separately by a person and must never be generated — that is why every prompt carries `No narration`.

## RUNNING ORDER

# ⏱ RAW MATERIAL — 4:16 (256 seconds). Final cut decided in the edit.

| # | Block | Length | In | Out | Narration |
|---|---|---|---|---|---|
| 00 | Deep forest | 16s | 0:00 | 0:16 | — |
| 01 | Forest | 16s | 0:16 | 0:32 | VO-01 |
| 02 | Arrival | 12s | 0:32 | 0:44 | VO-02 |
| 02B | Entrance — into the city | 14s | 0:44 | 0:58 | — |
| 03 | City square | 20s | 0:58 | 1:18 | — |
| 04A | City panorama — aerial | 20s | 1:18 | 1:38 | VO-03 |
| 04B | City interiors | 20s | 1:38 | 1:58 | — |
| 05A | Park — wheel & bumper cars | 20s | 1:58 | 2:18 | VO-04 |
| 05B | Park — swings & wide | 12s | 2:18 | 2:30 | — |
| 06 | Home entry | 20s | 2:30 | 2:50 | VO-05 |
| 07 | Inside — room / hall | 16s | 2:50 | 3:06 | VO-06, VO-07 |
| 08 | Kitchen | 14s | 3:06 | 3:20 | VO-08 |
| 09 · 10 · 11 | **The ending**, crosscut from three generations | 56s | 3:20 | 4:16 | VO-09 … VO-13 |
| | **TOTAL** | **256s** | | **4:16** | 13 cues |

**Generation 00 was added after this table was first written and never entered into it** — which is where
the stale 4:00 / 240-second figure came from. The film is 4:16 of raw material. Comfortably inside the
3–5 minute target with room to trim.

**Where the extra 32 seconds went.** Two blocks were carrying more locations than 20 seconds can hold:
the panorama had an aerial plus three interiors at four seconds each, and the park had three rides at
seven. Nothing there is a continuous action, so splitting them adds air rather than breaking anything —
the aerial now runs a full twenty seconds, the interiors get seven each, and the bumper cars get ten.
Abandonment only reads in long frames. Every other block plays exactly as generated, in order.

---

## GEO-BASEMENT — paste into generations 10 and 11, unchanged

```
GEO SPATIAL LAYOUT (locked across both basement shots — pure spatial map):
— ROOM = a low windowless basement room about seven metres deep, painted brick walls, concrete floor.
— THE DOOR: a closed steel door in the FAR wall, dead ahead of the seated viewpoint, six metres away.
  It stays shut for the whole scene.
— THE WORK TABLE: against the LEFT wall, three metres from the seated viewpoint, FRONT-LEFT in frame.
— THE MIRROR: mounted on the LEFT wall directly above the work table, facing across the room.
— THE WORKER: standing at the table, front-left, body turned to the table and the mirror, back
  three-quarters to the seated viewpoint, head down over her work.
— CAMERA POSITION 1 (generation 10): the seated viewpoint — low, on the near side of the room, facing
  the far door, with the table and the worker at FRONT-LEFT.
— CAMERA POSITION 2 (generation 11): standing height, behind the worker and half a metre to HER LEFT,
  looking over her shoulder into the mirror on the left wall.
— 180° AXIS: both camera positions live on the same side of the worker. The camera NEVER crosses to the
  far side of the table, and the door is ALWAYS ahead of camera, never behind it.
— LIGHT: one dim overhead fixture directly above the work table. The door end of the room falls away
  two stops into shade. No daylight anywhere — no window, no ENVIRONMENT LOCK in this room.
```

**Why this room gets a map and nothing else does.** Two shots share one space, and the second one has to
find the same mirror, the same table and the same wall from a completely different camera position. Without
the map the mirror moves to another wall between takes and the copy walks in from the wrong side.

---

# 00 · DEEP FOREST · 16s

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. No body, no hands, no arms, no feet, no shadow of
the viewer at any point. A person walks slowly, calmly and at an unhurried, leisurely, cinematic pace deep
inside a dense, wild, untouched forest on raw forest floor in the abandoned exclusion zone. No trodden paths,
no beaten tracks, no openings, no roads, no structures anywhere visible — only deep unbroken wild forest and
dense canopy. One continuous 16-second take, no cuts.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.

ROUTE
One continuous walk along one route: deep forest, out to a road, then along that road to the city sign.
00 — deep inside the forest. Canopy closed overhead, no sky visible, no road anywhere in frame. The darkest of the three.
01 — the same forest thinning out. The canopy opens, sky appears, the light steadily increases, and at the end an asphalt road.
02 — on that same road, walking along it. The city sign stands on the right-hand verge.
The light gets BRIGHTER from 00 through 01 to 02 and never darker. The forest is the closed dark part of the walk; the road is the open bright part. Same asphalt, same verges, same direction of travel, same afternoon.
ACTIVE REFERENCES
@loc_MC_forest for location reference — take only the space and the texture: dense pine and birch trunks,
low undergrowth, deep leaf litter, thin daylight through the canopy. Do not use as a starting frame, do
not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
First frame is already mid-stride on raw wild forest floor deep in the woods: tall pine and birch trunks
surrounding the viewer closely on all sides, dense unbroken canopy above, deep leaf litter and moss underfoot.
No trodden path, no road, no horizon opening, no clearings.

FORMAT MODE
Single continuous take, real time, no cuts, no speed ramps.

OPTICS
47° diagonal field of view, standard normal lens character, natural human-eye perspective. Deep enough
focus to hold both the near trunks and the deeper forest background. No distortion.

CAMERA
The camera is a walking person's eyes and head, not a heavy rig or mechanical pan: effortless, natural,
light head turns with organic human eye-line movement, vertical rise and fall on each stride, small lateral sway.
It never stabilises into a heavy mechanical glide. Eye height throughout.

ACTION TIMING
0.0–7.0s — walking forward slowly, calmly and steadily facing straight ahead deep inside the wild forest at an unhurried, cinematic pace; tall pine and birch trunks pass smoothly on both sides through deep leaf litter and moss. The canopy is closed overhead and stays closed — no sky, no opening, no brightening anywhere in the take.
7.0–10.0s — turn the camera slightly to the right, as if the walking person effortlessly looked to the right toward the soft sunlight filtering through the trees, while continuing the slow walk forward.
10.0–12.0s — turn the camera slightly to the left, as if the walking person effortlessly looked to the left toward the passing forest undergrowth.
12.0–16.0s — turn the camera back to centre, as if the walking person looked straight ahead again, continuing the calm, steady walk forward to the end of the take.

PHYSICS
Weight transfer on every slow step: heel contact, mass settling, toe push-off. Footfall bounce stays consistent on soft wild forest floor and leaf litter. Branches move gently on wind. Cloud moves at cloud speed, foliage on a separate faster frequency.

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

LIGHTING
This is the CLOSED, DARK end of the walk — the darkest shot in the opening sequence, and it never brightens
across the take. The canopy is shut overhead: no open sky anywhere in frame at any point. Light arrives only
as small soft dapple patches on the forest floor where the canopy thins, moving slowly as the branches move.
Mid-tones stay open and readable, shadows stay dark but never crushed to black. The overall level is
consistently one stop under generation 01 and two stops under generation 02, and it does not change from the
first frame to the last.

AUDIO
Diegetic only — 0.0–4.0s near-total forest silence: subtle wind through pine needles and soft footsteps on
leaf litter only. No bird calls or sharp sounds in the opening seconds. From ~5.0s onward: distant sparse
bird calls, soft wind through leaves, drifting insects. No loud impact SFX. No music. No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, bark and lichen at material level, clean cloud gradation, no jitter, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people visible anywhere. No hands, no arms, no feet, no body part and no cast shadow of the viewer
enters frame at any time. The slow walk never stops — the body keeps moving slowly forward.
No trodden paths, no beaten tracks, no roads, no clearings, no buildings, no signs, no vehicles anywhere.
Deep unbroken forest only. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9. 16s. SFX only. NO CGI. Cinematic.
```

---

# 01 · FOREST · 16s · 0:00

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. No body, no hands, no arms, no feet, no shadow of
the viewer at any point. A person walks slowly, calmly and at an unhurried, leisurely, cinematic pace through
wild forest floor inside an abandoned zone, looks up at the sky, and comes out of the trees toward an empty
perpendicular road running across in the distance. One continuous 16-second take, no cuts.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.

ROUTE
One continuous walk along one route: deep forest, out to a road, then along that road to the city sign.
00 — deep inside the forest. Canopy closed overhead, no sky visible, no road anywhere in frame. The darkest of the three.
01 — the same forest thinning out. The canopy opens, sky appears, the light steadily increases, and at the end an asphalt road.
02 — on that same road, walking along it. The city sign stands on the right-hand verge.
The light gets BRIGHTER from 00 through 01 to 02 and never darker. The forest is the closed dark part of the walk; the road is the open bright part. Same asphalt, same verges, same direction of travel, same afternoon.
ACTIVE REFERENCES
@loc_MC_forest for location reference — take only the space and the texture: dense pine and birch trunks,
low undergrowth, deep leaf litter, thin daylight through the canopy. Do not use as a starting frame, do
not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
First frame is already mid-stride on wild forest floor: trunks passing close on both sides, stepping forward
through leaf litter toward a break in the trees dead ahead. No empty establishing beat.

FORMAT MODE
Single continuous take, real time, no cuts, no speed ramps.

OPTICS
47° diagonal field of view, standard normal lens character, natural human-eye perspective. Deep enough
focus to hold both the near trunks and the distant horizon. No distortion.

CAMERA
The camera is a walking body moving at a slow, calm, unhurried gait, not a rig: gentle vertical rise
and fall on each stride, small lateral sway, organic imperfect correction after every step. It never
stabilises into a glide. Exactly two deliberate moves in the whole take — one look up, one look back down.
Eye height throughout.

ACTION TIMING
0.0–5.0s — the canopy is still closed overhead and the light is low; walking forward slowly at an unhurried, calm, leisurely cinematic pace; trunks enter close on
the left and pass out slowly; the break in the trees ahead widens and brightens.
5.0–8.0s — the gaze lifts to the sky: broken cloud with one gap of direct sun, thin branches crossing it.
The slow walk continues underneath the tilt without breaking rhythm. The tilt eases in and settles.
8.0–9.0s — the gaze comes back down to the route, slower than it left.
9.0–13.0s — the last trunks fall away left and right; the sky opens across the top of frame; the ground
underfoot changes from leaf litter to dry grass and broken asphalt.
13.0–16.0s — open ground. Far off about fifty metres ahead in the haze, an empty perpendicular road opens up
running horizontally across in the background. The head drifts a few degrees to hold it centred.
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

PHYSICS
Weight transfer on every slow step: heel contact, mass settling, toe push-off. The footfall sound and the
body's vertical bounce change when the ground changes from soft litter to hard asphalt. Branches move on
wind and rebound. Cloud moves at cloud speed, branches on a separate faster frequency. Wind is
stronger in the open than under the canopy and moves the grass in travelling waves.

LIGHTING
This is the TRANSITION between the closed forest and the open road, and the light RISES steadily across the
whole take — it starts one stop under and ends level with the open daylight of generation 02, and it never
goes the other way. At the start the canopy is still mostly closed and the floor sits low key with moving
dapple. As the trees thin, more sky enters the top of frame and the overall level climbs continuously. By
the last beat the frame is open daylight. Mid-tones stay open throughout, shadows stay dark but never
crushed, sky highlights are retained and never clipped.

AUDIO
Diegetic only — 0.0–4.0s near-total forest silence: subtle wind through pine needles and soft footsteps on leaf litter only. No bird calls or sharp sounds in the opening seconds. From ~5.0s onward: distant sparse bird calls, soft wind, drifting insects. No music. No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, bark and lichen at material level, clean cloud gradation, no jitter, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people visible anywhere. No hands, no arms, no feet, no body part and no cast shadow of the viewer
enters frame at any time. The slow walk never stops — the body keeps moving slowly through the upward look.
Exactly ONE break in the cloud; no clear blue sky, no aircraft, no contrails. No vehicles, no buildings, no signs.
Photoreal. NON-IP. 16:9. 16s. SFX only. NO CGI. Cinematic.
```

---

# 02 · ARRIVAL · 12s · 0:16

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. A person walks along the approach road toward
Pripyat. The concrete city sign stands at the right-hand verge ahead, the way a town-entrance sign always
does. He walks up level with it, stops, and looks at it. One continuous 12-second take, no cuts.

ACTIVE REFERENCES
@loc_MC_pripyat_sign for location reference — take only the space and the texture: the white wedge-shaped
concrete city sign of Pripyat standing at the roadside, the word ПРИПЯТЬ in tall raised relief letters
across the top slab and the year 1970 on the lower panel, lichen crust in the letter troughs, rust bleed
at the fixings, grass and birch saplings at its base. Do not use as a starting frame, do not inherit the
composition, the angle or the grade.

ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.

ROUTE
One continuous walk along one route: deep forest, out to a road, then along that road to the city sign.
00 — deep inside the forest. Canopy closed overhead, no sky visible, no road anywhere in frame. The darkest of the three.
01 — the same forest thinning out. The canopy opens, sky appears, the light steadily increases, and at the end an asphalt road.
02 — on that same road, walking along it. The city sign stands on the right-hand verge.
The light gets BRIGHTER from 00 through 01 to 02 and never darker. The forest is the closed dark part of the walk; the road is the open bright part. Same asphalt, same verges, same direction of travel, same afternoon.

FIRST FRAME AND SPATIAL BLOCKING
First frame is already walking on the road: cracked asphalt running away from camera down frame-CENTRE,
overgrown verges on both sides, and the city sign standing on the RIGHT verge ahead at the edge of the
carriageway, angled slightly toward the road so its face reads to anyone arriving. Treeline behind it,
flat empty ground beyond. No empty establishing beat.

FORMAT MODE
Single continuous take, real time, no cuts.

OPTICS
47° diagonal field of view, standard normal lens character, natural human-eye perspective. Deep enough
focus to hold the road surface and the sign face together. No distortion.

CAMERA
A walking body, then a standing body. Stride rise and fall, lateral sway, organic imperfect correction.
The sign grows in frame from the walk alone — no zoom, no push. After the stop, one deliberate head turn
to frame-RIGHT onto the sign, then breath-driven micro-motion only.

ACTION TIMING
0.0–3.0s — walking up the road slowly, calmly, at an unhurried leisurely cinematic pace; the sign passes from small at the right edge to filling
the right half of frame; the relief lettering separates from the flat of the slab and becomes readable.
3.0–5.0s — the stride shortens, the last step is a half step, the body settles forward and back once and
stops on the road level with the sign.
5.0–7.0s — the head turns to frame-RIGHT onto the sign and holds. The lettering sits readable and nothing
happens at all — only grass moving on the wind and one slow blink.
7.0–10.0s — the gaze travels slowly along the lettering to one end, holds there, and comes back.
10.0–12.0s — the frame stops moving entirely. Two full seconds of stillness: grass on the wind, one slow
blink, nothing else.

PHYSICS
Weight transfer on every slow step: heel contact, mass settling, toe push-off, footfall on cracked
asphalt and loose grit. The deceleration is a real body decelerating — shorter final
stride, reduced vertical bounce, mass settling once. Grass and birch saplings at the base of the sign move
continuously on wind; the slab does not. Once the body stops, only breath moves the frame.

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

LIGHTING
This is the OPEN, BRIGHT end of the walk — the brightest of the three shots, full open daylight with no
canopy overhead, and the level does not change across the take. Soft sun behind thin cloud, no hard shadow
anywhere. The relief throws only soft wide shadow across the slab face. The white concrete holds the top of
the exposure without clipping; the asphalt and grass sit a stop and a half under it. Mid-tones open,
shadows never crushed.

AUDIO
Diegetic only — footfall on asphalt and grit, breath slowing to rest, wind across open ground, grass
movement, distant birds, complete absence of any machine sound. No music. No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Key light from sky only. No fill from the camera side.
Color: 60:30:10 — 60% new-growth birch and grass green, 30% weathered concrete grey and pale sky, 10% rust-orange oxidised metal.
Camera: Physical cine lens. 180° shutter motion blur.
Surfaces: Material-level realism — flaking paint, lichen crust, wet concrete stain, rusted steel, decades of settled dust. Nothing looks recently placed.
Physics: Gravity and inertia respected — mass has real weight, correct contact shadows. No floating props. Nothing passes through anything — no clipping, no intersection; whatever is touched bends, shakes and recovers a beat later.
Vegetation: Birch and poplar reclaiming the built environment — saplings through asphalt, tall grass across every open space, all of it moving on real wind.
Composition: Rule of thirds + golden ratio.
Continuity: Environment identical across every cut.
Technical: 24fps smooth motion. 8K detail. No jitter. No flicker. No vignette, no edge darkening, even exposure corner to corner.

QUALITY
8K detail, concrete pore and lichen at material level, crisp relief edges, no jitter, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people visible. No hands, no arms, no feet, no body part and no cast shadow of the viewer in frame at
any time. Exactly ONE sign, standing at the right-hand verge of the road, never duplicated and never in
the middle of the carriageway. The lettering reads ПРИПЯТЬ in correct Cyrillic, sharp and legible. No
vehicles, no fences, no power lines, no modern signage, no graffiti, no tourist markers, no flowers or
wreaths at its base. The last two seconds are held stillness — the frame does not drift, push or reframe.
Photoreal. NON-IP. 16:9. 12s. SFX only. NO CGI. Cinematic. Present tense. Short sentences.
```

---

# 02B · ENTRANCE · 14s · 0:28

**Overlaps deliberately with the first five seconds of generation 03.** Both are generated; which one
carries the entry into the city is decided in the edit.

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. A person keeps walking the approach road after the
city sign. The forest on both sides thins, the first apartment blocks rise out of the treeline ahead, and
by the end of the shot the road has become a street with buildings on both sides. He is inside the city.
One continuous 14-second take, no cuts.

ACTIVE REFERENCES
@loc_MC_pripyat_entrance for location reference — take only the space and the texture: the cracked asphalt
approach road into Pripyat, the surface split open by birch saplings, overgrown verges, the first
five-storey precast concrete panel blocks standing behind a thick screen of poplar and birch. Do not use
as a starting frame, do not inherit the composition, the angle or the grade.

ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.

FIRST FRAME AND SPATIAL BLOCKING
First frame is already walking on the road: cracked asphalt running away from camera to a vanishing point
at frame-CENTRE, tall grass verges and a dense tree screen on both sides. Above the treeline dead ahead,
the flat roofline and top two floors of a concrete apartment block are just visible over the canopy. No
empty establishing beat.

FORMAT MODE
Single continuous take, real time, no cuts.

OPTICS
47° diagonal field of view, standard normal lens character, natural human-eye perspective. Deep enough
focus to hold the road surface underfoot and the buildings ahead in one read. No distortion.

CAMERA
The camera is a walking body moving at a slow, calm, unhurried gait, not a rig: gentle vertical rise
and fall on each stride, small lateral sway, organic imperfect correction after every step. It never
stabilises into a glide. No push, no zoom. Exactly ONE deliberate move in the whole take — a slow
head turn to frame-LEFT near the end and back. Eye height throughout.

ACTION TIMING
0.0–4.0s — walking forward slowly, calmly and steadily at an unhurried, leisurely cinematic pace; the tree screen passes close on both sides; the roofline
ahead grows from a strip above the canopy into a recognisable building.
4.0–8.0s — the trees on the RIGHT fall away and the end wall of a five-storey concrete panel block stands
right at the roadside, ten metres off, every window opening empty and black. He walks slowly past it
without changing pace.
8.0–11.0s — more blocks open up on the LEFT as well; the head turns slowly to frame-LEFT to take one in as
he passes, then comes back to the direction of travel. The verges become a broken kerb and pavement.
11.0–14.0s — the road is now a street: buildings on both sides, saplings through the asphalt, leaning
dead street lamps passing on the right. He keeps walking straight down the middle of it at the same slow,
calm, unhurried pace.

PHYSICS
Weight transfer on every slow step: heel contact, mass settling, toe push-off, a clear pause of weight on
each foot. Footfall changes as the surface goes from open road asphalt to broken street asphalt and grit. Saplings the body passes bend on contact
and rebound. Wind moves the whole tree screen in travelling waves, and the sound changes as the trees give
way to hard building faces — the openness closes in.

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

LIGHTING
Soft sun behind thin cloud from high and three-quarters behind. Under the tree screen the road sits low
key with moving dapple; as the trees open the light broadens and the concrete faces catch a warm rim on
their upper edges. Every shadow falls the same way throughout. No fill from the camera side.

AUDIO
Diegetic only — footfall on asphalt and grit, breath at walking effort, wind through poplar and birch,
distant crows. As the buildings arrive the ambience tightens and gains a faint hard-surface reflection.
Total absence of traffic, machinery or any human sound. No music. No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Key light from sky only. No fill from the camera side.
Color: 60:30:10 — 60% new-growth birch and grass green, 30% weathered concrete grey and pale sky, 10% rust-orange oxidised metal.
Camera: Physical cine lens. 180° shutter motion blur.
Surfaces: Material-level realism — flaking paint, lichen crust, wet concrete stain, rusted steel, decades of settled dust. Nothing looks recently placed.
Physics: Gravity and inertia respected — mass has real weight, correct contact shadows. No floating props. Nothing passes through anything — no clipping, no intersection; whatever is touched bends, shakes and recovers a beat later.
Vegetation: Birch and poplar reclaiming the built environment — saplings through asphalt, tall grass across every open space, all of it moving on real wind.
Composition: Rule of thirds + golden ratio.
Continuity: Environment identical across every cut.
Technical: 24fps smooth motion. 8K detail. No jitter. No flicker. No vignette, no edge darkening, even exposure corner to corner.

QUALITY
8K detail, asphalt, concrete panel seams and foliage at material level, no jitter, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people visible anywhere in the city. No hands, no arms, no feet, no body part and no cast shadow of
the viewer in frame at any time. The walk is slow, calm and unhurried from the first frame to the last —
never brisk, never purposeful, never hurried. The body never stops and the pace never changes. No
working vehicles, no lit windows, no intact glazing, no modern signage, no barriers, no checkpoint. Every
building is derelict with empty window openings. Vegetation grows through every hard surface. Photoreal.
NON-IP. 16:9. 14s. SFX only. NO CGI. Cinematic. Present tense. Short sentences.
```

---

# 03 · CITY SQUARE · 20s · 0:24

```
SCENE CONTEXT
EXACT 1 CHARACTER — NO DUPLICATES: MR CHAMELEON. He walks into the abandoned city and crosses the central
square along the front of the ruined Palace of Culture, turning his head to read the building as he
passes. The last four seconds cut to an outside view of him crossing the same square. His face is not
visible at any point. Controlled multi-shot sequence with ONE HARD CUT at 16.0 seconds. Real time.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@char_MC_mr_chameleon for character reference — walking, muted field clothing, a dark half-mask covering
the lower face up to just under the eyes; seen from behind and three-quarters away from camera. Visible in
the second shot only.
@loc_MC_pripyat_entrance for location reference — take only the space and the texture: cracked approach
road split by birch saplings, overgrown verges, the first concrete apartment blocks rising behind a screen
of trees. Do not use as a starting frame, do not inherit the composition, the angle or the grade.
@loc_MC_dk_energetic for location reference — take only the space and the texture: a long modernist
colonnaded civic building, ruined façade, empty window openings, spalled concrete, moss on the steps,
saplings through the paving of the square in front of it. Do not use as a starting frame, do not inherit
the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
SHOT A first frame is already on the approach road in first person: broken asphalt running away from
camera to frame-CENTRE, tree screen either side, block façades above the treeline dead ahead. No empty
establishing beat.
SHOT B first frame already contains the figure: MR CHAMELEON at frame-LEFT third, mid-stride, walking
toward frame-RIGHT along the square four metres out from the colonnade, back three-quarters to camera.
The colonnade runs the full width behind him. Camera on the open-square side, twenty-five metres out.

FORMAT MODE
Controlled multi-shot: SHOT A 0.0–16.0s first person, HARD CUT, SHOT B 16.0–20.0s outside view. Real time,
no speed ramps. NO fade, NO crossfade, NO dissolve, NO transition effect. HARD CUT only.

OPTICS
SHOT A — 47° diagonal field of view, standard normal lens character, natural human-eye perspective, deep
focus holding the road surface, the colonnade and the far side of the square in one read.
SHOT B — 8° diagonal field of view, super-telephoto observation lens character, camera twenty-five metres
from the subject. Extreme background compression: the colonnade flattens into a stacked wall behind him.
Only the figure is sharp; everything else dissolves into a soft wash. Close framing achieved through lens
reach, not physical proximity. Foreground occlusion is mandatory: an out-of-focus sapling occupies the
lower-LEFT third as an oversized dark bokeh shape. Atmospheric haze between camera and subject.

CAMERA
SHOT A — The camera is a walking body moving at a slow, calm, unhurried gait, not a rig: gentle vertical rise and fall on each stride, small lateral sway, organic imperfect correction after every step. It never stabilises into a glide. Exactly ONE deliberate
move: a head turn to frame-RIGHT onto the building and back. No push, no zoom, no whip.
SHOT B — locked off on a long lens on sticks with the faintest operator drift. It does not track him; he
walks through the frame.

ACTION TIMING
0.0–5.0s — first person, walking the approach road slowly, calmly, at an unhurried leisurely cinematic
pace; saplings pass close; the façades come clear above the tree screen and grow from the walk alone.
5.0–10.0s — the road opens into the square; the colonnade of the Palace of Culture arrives along
frame-RIGHT and begins passing.
10.0–15.0s — the head turns to frame-RIGHT onto the ruin — the eyeline arrives before the framing does —
and holds there while the body keeps walking the same line, so the frame slides sideways past the
colonnade. The walking rhythm never breaks under the turn. At 15.0s the head starts back toward the
direction of travel.
16.0s — HARD CUT.
16.0–20.0s — outside view: he walks from the left third toward frame-CENTRE and on toward the right third,
slowly and calmly, stride long and relaxed, no glances around. The frame holds and does not follow him.

PHYSICS
Footfall changes from asphalt to broken paving and grit. Saplings bend on contact and rebound. In SHOT A
the vertical walking bounce continues at the same tempo throughout the head turn. In SHOT B real ground
contact, opposing arm swing and weight transfer are visible even at distance; his clothing moves a beat
behind him on the wind; the foreground sapling moves on its own faster frequency in front of the lens.

COLLIDER — the camera is a body, not a flying camera
Nothing in the world passes through the camera or through him.
Do not place anything in the path and do not invent obstacles — the way ahead stays clear and open, and the
vegetation lives at the sides of frame.
BEFORE THE HARD CUT (first person): the body carrying the camera is never seen, but it occupies space. If a
bush, a clump of tall grass or a low branch does end up in the path it bends, shakes and folds away where
the unseen body meets it and recovers a beat later. Grass underfoot flattens where each step lands and
springs back after the foot lifts. No arms, hands, shoulders, legs or feet ever enter frame — what is seen
is the vegetation reacting, never the body that made it react.
AFTER THE HARD CUT (outside view): he is fully in frame. Grass parts around his shins and closes behind
him, folding under each footfall and recovering a beat later, leaving a flattened track behind his walk.
Nothing intersects his body or his clothing.
No clipping. Nothing touches the lens.

LIGHTING
Flat overcast from directly above in both shots — the same light, the same direction, the same time of
day. The open square is the bright zone; the colonnade holds deep shade two stops under it and the camera
reads into that shade with no fill.

AUDIO
Diegetic only — footfall on asphalt, paving and grit, breath, wind moving through the colonnade with a low
hollow tone, distant crows, one loose sheet of metal shifting in the building. In the last four seconds
everything sits further away. No music. No narration. No voices. No traffic, no machinery.

CHARACTER ACTING
MR CHAMELEON in SHOT B — completely at ease in a dead city. What he wants in this moment: nothing; he is
walking a route he knows. What he is hiding: nothing. Dominant body rhythm: even, unhurried, grounded, no
wasted motion. What is missing from him is the tell: he never scans, never checks behind, never braces, and
never reacts to the ruin around him. What changes across the shot: nothing at all.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, concrete, moss and asphalt at material level, clean shade detail in the colonnade, the figure
razor-sharp against a dissolved background in SHOT B, no jitter, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Exactly ONE person in the entire sequence and no one else anywhere in the city. He wears the half-mask
throughout and it never comes off. In SHOT B he is seen in three-quarter profile from behind — the mask
reads clearly at the edge of the jaw, but he never turns toward the lens and his eyes are never legible at
this distance. He walks continuously and never stops. The camera stays on the open-square side
of his walking line and never crosses to the building side. Exactly ONE colonnaded building, never
duplicated. Exactly ONE hard cut, at 16.0 seconds. No working vehicles, no lit windows, no intact glazing,
no modern signage. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic.
```

---

# 04A · CITY PANORAMA — AERIAL · 20s · 0:44

```
SCENE CONTEXT
EXACT 0 CHARACTERS — the city itself is the subject. One slow, unbroken aerial pan across an abandoned
city from fifty metres up. Nothing else happens. One continuous 20-second take, no cuts.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@loc_MC_pripyat_city for location reference — take only the space and the texture: rows of sixteen-storey
and five-storey concrete apartment blocks, empty window openings, mature birch and poplar forest filling
the streets and courtyards between them, a flat treeless horizon beyond, an arched confinement structure
far off on that horizon. Do not use as a starting frame, do not inherit the composition, the angle or the
grade.

FIRST FRAME AND SPATIAL BLOCKING
SHOT A first frame is already the full city from fifty metres up: blocks across the lower two-thirds,
forest between them, overcast sky in the top third, horizon on the upper third line. The pan is already
at speed. No empty establishing beat, no rise, no reveal.

FORMAT MODE
Single continuous take, real time, no cuts, no speed ramps.

OPTICS
84° diagonal field of view, classic wide lens character, camera fifty metres above ground, deep
edge-to-edge focus, straight architectural lines stay rectilinear, no fisheye curve, no telephoto
compression.

CAMERA
One move only: a slow, even horizontal pan at a constant rate, the speed of a drone holding altitude. It
does not accelerate, does not stop, does not descend, does not rotate, and it is still moving at the final
frame. No push, no tilt, no roll.

ACTION TIMING
0.0–7.0s — the pan is already at speed; the near blocks traverse the frame, courtyards opening and closing
between them, forest continuous through every street.
7.0–14.0s — the middle of the city passes at exactly the same rate: more blocks, more forest, no break in
the canopy anywhere.
14.0–20.0s — the pan continues unchanged; the far edge of the city and the flat horizon beyond it come
through frame. It is still moving at the last frame.

PHYSICS
The whole tree canopy moves as one field on wind in slow travelling waves at forest scale, not at branch
scale. Nothing else in frame moves at all. Parallax between near and far blocks is correct for the
altitude and the pan rate throughout.

LIGHTING
Flat overcast across the whole city, no cast shadows with hard edges. Atmospheric haze increases with
distance and lifts the far blocks toward the sky value.

AUDIO
Diegetic only — high open wind, distant crows, the vast quiet of a city with no machines in it. No music.
No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, concrete, canopy, wood and plaster at material level, no jitter, no flicker, no stutter in the
pan, no crawling on building edges.

POSITIVE CONSTRAINTS
Zero people anywhere. Zero moving vehicles, zero lit windows, zero smoke, zero aircraft, zero contrails.
Every building is derelict with empty window openings; forest grows through every street and courtyard.
The pan runs at one constant rate from the first frame to the last and never stops, never reverses, never
changes height. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic.
```

---

# 04B · CITY INTERIORS · 20s · 1:04

```
SCENE CONTEXT
EXACT 0 CHARACTERS — three real interiors of the abandoned city, each held still. A school gymnasium, a
classroom, a shop. Controlled multi-shot sequence with TWO HARD CUTS. Real time.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@loc_MC_pripyat_city for location reference — take only the material and the atmosphere: Soviet
institutional interiors abandoned for decades, peeling green and cream wall paint, fallen plaster,
buckled parquet, empty window openings, birch visible outside every window. Do not use as a starting
frame, do not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
SHOT A first frame is a school gymnasium: the sprung wooden floor running away from camera, buckled and
lifted across the room, a rusted goal frame at frame-CENTRE, tall windows along frame-LEFT, wall bars on
the far wall. Camera low, at floor-board height, two metres from the nearest buckle.
SHOT B first frame is a classroom: rows of wooden desks running away toward a window wall at frame-RIGHT,
blackboard wall at frame-LEFT, floor deep in fallen plaster and scattered paper. Camera low at desk
height, one and a half metres from the nearest desk.
SHOT C first frame is a shop interior: empty steel shelving racks in rows running away from camera, a
tiled floor under plaster dust, daylight through a shopfront of empty window frames at frame-LEFT.
Camera at chest height, two metres from the nearest rack.

FORMAT MODE
Controlled multi-shot: SHOT A 0.0–7.0s, HARD CUT, SHOT B 7.0–14.0s, HARD CUT, SHOT C 14.0–20.0s. Real
time. NO fade, NO crossfade, NO dissolve, NO transition effect. HARD CUTS only.

OPTICS
84° diagonal field of view in all three, classic wide lens character, camera one and a half to two metres
from the nearest foreground object. Foreground presence looms larger than natural, the room stays visible
to the frame edges, deep edge-to-edge focus, straight lines stay rectilinear, no fisheye curve.

CAMERA
All three static on sticks with the faintest breathing drift. No push, no pan, no tilt, no zoom anywhere
in the sequence.

ACTION TIMING
0.0–4.0s — the gymnasium held. Dust drifts through the window light in slow suspension.
4.0–7.0s — a loose floorboard settles a millimetre on the room's own movement and stops. Nothing else.
7.0s — HARD CUT.
7.0–11.0s — the classroom held. Dust only.
11.0–14.0s — a single sheet of paper on the floor lifts at one corner on a draught, travels a few
centimetres, and settles.
14.0s — HARD CUT.
14.0–20.0s — the shop held for the longest of the three. Dust in the shopfront light. A shelving rack
ticks once as the building moves, and nothing else happens for the rest of the shot.

PHYSICS
Dust moves on real slow air currents, non-linear. The paper has real mass — it lifts, travels and settles
with weight rather than gliding. The floorboard and the rack move like loaded structures settling, not
like objects pushed.

LIGHTING
Flat overcast in all three — one light, one time of day. Daylight enters only from the window wall and
falls away into the room; the opposite wall sits two stops under with no fill from the camera side.

AUDIO
Diegetic only — a different room tone in each with real reverberation: a huge hollow gymnasium, a small
dead classroom, a long hard-tiled shop. Wind through broken glazing, paper moving on the floor, one
structural tick, distant crows outside. No music. No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, parquet, plaster crust, paper, painted steel and tile at material level, no jitter, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people, zero animals in any shot. No legible text on the blackboard, on any sign, on any shelf label
or on any paper. No dolls, no toys, no gas masks, no personal items and no photographs staged anywhere in
frame — nothing is arranged and nothing is freshly disturbed. Every window opening is empty of glass. No
lit fixtures, no power anywhere. Exactly TWO hard cuts, at 7.0 and 14.0 seconds. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9.
20s. SFX only. NO CGI. Cinematic.
```

---

# 05A · PARK — WHEEL & BUMPER CARS · 20s · 1:24

```
SCENE CONTEXT
EXACT 0 CHARACTERS — the two most recognisable rides of the abandoned amusement park, each held long and
still: the Ferris wheel, then the bumper-car pavilion. Nothing works, nothing turns, nobody is there.
Controlled multi-shot sequence with ONE HARD CUT at 10.0 seconds. Real time.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@loc_MC_park for location reference — take only the space and the texture: a small amusement park gone to
forest; a Ferris wheel with yellow rusted cabins on an oxide-streaked steel frame; an open-sided
bumper-car pavilion with painted steel cars rusted in place on a metal floor under a contact grid; rusted
swing boats on their frames and a small carousel with a partly collapsed canopy; birch and poplar grown up
through the asphalt everywhere. Do not use as a starting frame, do not inherit the composition, the angle
or the grade.

FIRST FRAME AND SPATIAL BLOCKING
SHOT A first frame is already the full wheel: the structure across the centre and upper two-thirds, its
base cut by sapling growth in the lower third, overcast sky filling every gap in the frame. Camera low,
twenty metres out, looking slightly up.
SHOT B first frame is the full pavilion: the cars scattered across the lower two-thirds, the overhead
contact grid cutting across the upper third, forest through the open sides at both frame edges. Camera low
at the height of a car body, three metres from the nearest one.

FORMAT MODE
Controlled multi-shot: SHOT A 0.0–10.0s, HARD CUT, SHOT B 10.0–20.0s. Real time. NO fade, NO crossfade,
NO dissolve, NO transition effect. HARD CUT only.

OPTICS
SHOT A — 47° diagonal field of view, standard normal lens character, camera twenty metres from the base of
the wheel; natural proportions, no distortion of the steelwork, focus holding both the saplings and the
top of the wheel.
SHOT B — 84° diagonal field of view, classic wide lens character, camera three metres from the nearest
car; foreground car presence looms larger than natural, the pavilion stays visible to the frame edges,
deep edge-to-edge focus, straight grid lines rectilinear, no fisheye curve.

CAMERA
Both static and locked, with only the faintest breathing drift on a heavy head. No push, no pan, no
tilt, no zoom anywhere in the sequence.

ACTION TIMING
0.0–6.0s — the wheel held. Sapling canopy in the lower third moves continuously on wind; the structure
does not move at all.
6.0–10.0s — one cabin high on the wheel shifts a few degrees on a gust and comes back with the slow heavy
period of a large suspended mass, then settles.
10.0s — HARD CUT.
10.0–15.0s — the pavilion held. Leaves move across the metal floor on a low draught. Nothing else.
15.0–20.0s — a single dry leaf travels the open floor between two cars, catches on a rusted edge and stops
dead. The shot holds on the parked cars for the rest of its length with nothing moving at all.

PHYSICS
The cabin is heavy steel on a worn pivot: it moves late, moves little, and takes a long time to settle.
The leaf has almost no mass — it skips and tumbles rather than slides, and stops dead when it catches.
Vegetation moves on a fast light frequency, completely separate from every structure.

LIGHTING
Flat overcast throughout — one light, one time of day. On the wheel the sky is bright behind the steelwork
so the frame reads as silhouette and edge, with the yellow of the cabins the only colour holding against
it. In the pavilion the centre under the grid sits a stop and a half darker than the open sides. No fill
from the camera side anywhere.

AUDIO
Diegetic only — open wind through the steel frame with a low tonal hum, birch leaves, one dry metallic
groan as the cabin moves, a dry leaf skittering on metal, a loose piece of the contact grid ticking,
distant crows. No music. No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, oxidised steel, flaking paint and moss at material level, clean sky gradation with no banding,
no jitter, no flicker, no crawling on thin steelwork against the sky.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people, zero animals in either shot. The Ferris wheel NEVER rotates — exactly ONE cabin moves, and
only a few degrees. No bumper car moves at any point, ever. No power anywhere: no lit bulbs, no sparks at
the contact grid, no music box, no machinery sound. Nothing is arranged and nothing is freshly disturbed.
Exactly ONE hard cut, at 10.0 seconds. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic.
```

---

# 05B · PARK — SWINGS & WIDE · 12s · 1:44

```
SCENE CONTEXT
EXACT 0 CHARACTERS — the swing boats and carousel, then the whole park in one frame with the forest
closing in on it. Controlled multi-shot sequence with ONE HARD CUT at 6.0 seconds. Real time.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@loc_MC_park for location reference — take only the space and the texture: rusted swing boats hanging
dead-still on their frames, a small carousel behind them with its canopy partly collapsed, asphalt broken
open by birch saplings, the Ferris wheel standing above the treeline further back, forest closing in on
all sides. Do not use as a starting frame, do not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
SHOT A first frame is the swing boats at frame-LEFT and CENTRE, the carousel behind them at frame-RIGHT,
saplings through the asphalt in the foreground, forest wall across the background. Camera at standing
height, eight metres out.
SHOT B first frame is the whole park in one wide: the Ferris wheel standing at frame-RIGHT above the
treeline, the pavilion roof and the swing frames small at frame-CENTRE and LEFT, birch and poplar grown
up between and through all of it, overcast sky across the top third. Camera at standing height, forty
metres back, at the edge of the trees.

FORMAT MODE
Controlled multi-shot: SHOT A 0.0–6.0s, HARD CUT, SHOT B 6.0–12.0s. Real time. NO fade, NO crossfade,
NO dissolve, NO transition effect. HARD CUT only.

OPTICS
SHOT A — 47° diagonal field of view, standard normal lens character, camera eight metres from the swing
frames; natural proportions, foreground saplings and background forest both readable.
SHOT B — 84° diagonal field of view, classic wide lens character, camera forty metres back; the whole
park stays visible to the frame edges, deep edge-to-edge focus, straight steelwork stays rectilinear,
no fisheye curve, no telephoto compression.

CAMERA
Both static and locked, with only the faintest breathing drift on a heavy head. No push, no pan, no tilt,
no zoom anywhere in the sequence.

ACTION TIMING
0.0–3.5s — the swings and carousel held. The saplings and the forest behind move continuously on wind;
the swing boats do not move at all.
3.5–6.0s — a gust crosses the frame, the whole vegetation field bends together and recovers — and the
swing boats still do not move.
6.0s — HARD CUT.
6.0–12.0s — the whole park held in one frame. The forest moves as one field across the entire width of
the shot. Not one piece of the machinery in frame moves for six seconds.

PHYSICS
The swing boats are seized on rusted pivots and are visibly incapable of moving; the gust proves it. The
collapsed canopy fabric on the carousel moves only at its torn edge. In the wide, the canopy moves at
forest scale in slow travelling waves while every steel structure inside it stays absolutely fixed.

LIGHTING
Flat overcast in both, no hard shadow anywhere — one light, one time of day. The forest behind sits a stop
under the open ground. In the wide, the sky is the brightest value and the steelwork reads as silhouette
against it.

AUDIO
Diegetic only — wind through birch, one dry metallic creak from the swing frame with no movement to match
it, distant crows; in the wide, open wind across the whole park with a low tonal hum through the wheel's
steel, and nothing else at all. No music. No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, rusted steel, flaking paint and torn fabric at material level, clean sky gradation with no
banding, no jitter, no flicker, no crawling on thin steelwork against the sky.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people, zero animals in either shot. The swings NEVER swing and the carousel NEVER turns, not by a
degree, not even in the gust — this stillness is the shot. The Ferris wheel in the wide NEVER rotates. No
lit bulbs, no music box, no machinery sound, no power anywhere. Exactly ONE hard cut, at 6.0 seconds.
Photoreal. NON-IP. 16:9. 12s. SFX only. NO CGI. Cinematic.
```

---

# 06 · HOME ENTRY · 20s · 1:56

```
SCENE CONTEXT
EXACT 1 CHARACTER — NO DUPLICATES: MR CHAMELEON. He stands at the entrance of an abandoned residential
block with his back to the doorway; then he goes in, climbs to the second floor, shoulders a flat door
open and walks into the apartment with the camera following him. His face is not visible at any point.
Controlled multi-shot sequence with ONE HARD CUT at 6.0 seconds. Real time.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@char_MC_mr_chameleon for character reference — muted field clothing, a dark half-mask covering the lower
face up to just under the eyes; standing with his back to the entrance in the first shot, then seen from
directly behind for the rest.
@loc_MC_home_area for location reference — take only the space and the texture: the façade and entrance of
a derelict concrete apartment block, empty window openings, spalled render, a dark entrance doorway,
overgrown courtyard. Do not use as a starting frame, do not inherit the composition, the angle or the
grade.
@loc_MC_home_stairs for location reference — take only the space and the texture: a Soviet stairwell, torn
mailboxes in the entrance hall, bare concrete flights with a steel handrail, plaster down the treads, tall
stairwell windows with the glazing gone. Do not use as a starting frame, do not inherit the composition,
the angle or the grade.
@loc_MC_home_appartment for location reference — take only the space and the texture: a padded torn
entrance door, a hallway running away from it, patterned wallpaper hanging off the walls, daylight from
the rooms beyond. Do not use as a starting frame, do not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
SHOT A first frame already contains him: MR CHAMELEON standing in front of the entrance doorway at
frame-CENTRE, small, in the lower quarter of frame, back to the doorway, head down and turned away. The
façade rises through the whole frame above him. Camera at ground level, fifteen metres out, tilted up.
SHOT B first frame already contains him: MR CHAMELEON in the entrance hall at frame-CENTRE, three metres
ahead of camera, back fully to the lens, already walking toward the first flight; torn mailboxes at
frame-LEFT.

FORMAT MODE
Controlled multi-shot: SHOT A 0.0–6.0s exterior locked, HARD CUT, SHOT B 6.0–20.0s following handheld.
Real time. NO fade, NO crossfade, NO dissolve, NO transition effect. HARD CUT only.

OPTICS
SHOT A — 84° diagonal field of view, classic wide lens character, camera fifteen metres out and low; the
façade looms and fills the frame edge to edge, straight architectural lines stay rectilinear, no fisheye
curve, deep edge-to-edge focus. He reads as a small figure against a very large building.
SHOT B — 84° diagonal field of view, classic wide lens character, camera three metres behind the subject;
the stairwell and hallway stay visible to the frame edges, deep edge-to-edge focus, straight lines
rectilinear, no fisheye curve, no portrait bokeh.

CAMERA
SHOT A — static, locked, faintest breathing drift. No push, no pan, no zoom.
SHOT B — shoulder-mounted handheld with real mass: operator breath, weight shift on every stair,
micro-settling at each turn of the flight, organic imperfect correction. It holds three metres behind him
and never closes the distance. No push, no zoom, no whip.

ACTION TIMING
0.0–3.0s — he stands completely still in front of the entrance, weight settled, head down. Courtyard
vegetation moves around him; he does not.
3.0–6.0s — one small weight shift from one foot to the other, and nothing else. The head does not lift.
6.0s — HARD CUT.
6.0–9.0s — he crosses the entrance hall past the mailboxes slowly and calmly and starts the first flight;
the camera follows into the stairwell.
9.0–13.0s — first flight and the half-landing turn: his hand never takes the handrail, his pace is slow,
calm and unhurried,
plaster grit crunching under each step; he rounds the turn at the same calm, steady pace and the camera takes it a beat
later.
13.0–16.0s — second flight to the landing; he is ALREADY mid-push at the flat door, his shoulder ALREADY
into it, the door ALREADY cracking against its swollen frame. It gives all at once and swings.
16.0–20.0s — he steps through without breaking stride and walks down the hallway away from camera; the
camera crosses the threshold a beat behind him; the rooms open off the hallway and the daylight from the
far end grows in frame.

PHYSICS
Real stair mechanics: knee lift, weight onto the ball of the foot, mass carried upward, plaster grit
crushing underfoot with a change of sound on every step. The camera's mass lags his movement and catches
up. The door has real mass and a swollen frame — it resists, gives suddenly, swings past its stop and
rebounds a few centimetres; dust lifts off its edge and hangs in the doorway light. Floorboards flex under
both sets of weight. His clothing moves a beat behind his body.

COLLIDER — his body displaces what it touches
Nothing in the world passes through him. No grass, branch or object intersects his body or his clothing at
any point.
Do not place anything in his path and do not invent obstacles for him — he walks a clear route, and the
vegetation lives around him rather than in front of him.
But whatever he does walk through reacts: grass parts around his shins and closes behind him, folds under
each footfall and springs back a beat later, leaving a flattened track behind his walk. Anything he brushes
bends away and recovers.
Dust and grit lift where his feet land. He never changes pace for any of it and never looks at it.
No clipping, no intersection, no vegetation ignoring his mass.

LIGHTING
Flat overcast on the façade, and the entrance doorway is a black void three stops under it. Inside, the
daylight comes only from the tall stairwell windows at each half-landing, so the light rises and falls in
bands as they climb; the hallway beyond the flat door is darker still, with the far rooms brightest. No
fill from the camera side anywhere.

AUDIO
Diegetic only — open wind against a large concrete face and courtyard vegetation in the first shot; then
two sets of footfall on concrete and plaster grit, breath at climbing effort, a very reverberant hard
stairwell tone, wind through empty window openings, a swollen door tearing free of its frame, hinges, and
a dead flat interior tone in the hallway. No music. No narration. No voices.

CHARACTER ACTING
MR CHAMELEON — completely at home. What he wants in this moment: to go inside, the way anyone goes inside.
What he is hiding: nothing. Dominant body rhythm: even, grounded, unhurried, no hesitation at any
threshold. Visible habits in this beat: he never touches the handrail, never checks a step, never pauses
at the flat door to consider it — he simply puts his shoulder through it, because it is his. What changes
across the shot: nothing. He does not slow down anywhere in this building.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, concrete, render, plaster, rusted steel, torn door padding and wallpaper at material level,
clean detail in the dark bands and the doorway void, no jitter beyond the intended handheld, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Exactly ONE person in the entire sequence and no one else anywhere in the building. He wears the half-mask
throughout and it never comes off. Head down and turned away in the first shot, seen from directly behind
for the whole second shot; he never looks back and never turns at the landing.
He opens the door by shoulder alone — he never touches a handle and never uses a key. Exactly ONE building,
exactly ONE door opening. Exactly ONE hard cut, at 6.0 seconds. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9. 20s. SFX only.
NO CGI. Cinematic.
```

---

# 07 · INSIDE — ROOM / HALL · 16s · 2:16

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV throughout. No body, no hands, no arms, no feet, no
shadow of the viewer at any point. A person walks into his own bedroom in a derelict flat and looks it
over, then moves through into the main room, where a window has been torn out and a tree has grown its
branches inside. Controlled multi-shot sequence with ONE HARD CUT at 8.0 seconds. Real time.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@loc_MC_home_appartment for location reference — take only the space and the texture: a small Soviet
bedroom with an iron bed frame and rotted mattress under the window, a veneered wardrobe, a small writing
desk beside the window, patterned wallpaper peeling in sheets; and a living room with a glazed display
cabinet, a rotted patterned carpet, a heavy sideboard, and a window opening partly torn out with a mature
tree branch grown through it into the room over a floor of leaf litter. Do not use as a starting frame, do
not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
SHOT A first frame is already inside the bedroom doorway: the bed frame under the window on the far wall
at frame-CENTRE, the wardrobe on the LEFT wall, the desk beside the window at frame-RIGHT.
SHOT B first frame is already at the living-room threshold: the torn-out window with the tree branch on
the far wall frame-RIGHT of centre, the display cabinet along the LEFT wall, the carpet running away
underfoot.

FORMAT MODE
Controlled multi-shot: SHOT A 0.0–8.0s, HARD CUT, SHOT B 8.0–16.0s. Both first person. Real time. NO fade,
NO crossfade, NO dissolve, NO transition effect. HARD CUT only.

OPTICS
84° diagonal field of view in both shots, classic wide lens character, camera one and a half to two metres
inside each room. The whole room stays visible to the frame edges, deep edge-to-edge focus, straight lines
stay rectilinear, no fisheye curve.

CAMERA
The camera is a body in both shots: slow steps forward with real weight transfer, then a stop, then one
slow head turn that eases in and eases out. Handheld with breath-driven micro-motion throughout. Exactly
one turn per shot. No push, no zoom.

ACTION TIMING
0.0–3.0s — two slow, unhurried steps into the bedroom; the bed frame grows in frame; dust lifts where the
feet land and hangs in the window light.
3.0–6.0s — the body stops. The gaze turns slowly to the desk at frame-RIGHT and holds on it.
6.0–8.0s — the gaze comes back toward the window, slower than it left, and settles. One slow blink event.
8.0s — HARD CUT.
8.0–11.5s — three slow, unhurried steps into the living room; the tree branch and the torn window opening
grow in frame.
11.5–14.0s — the body stops. The gaze crosses slowly from the cabinet at frame-LEFT to the tree at
frame-RIGHT.
14.0–16.0s — held on the tree. The branch moves on the outside wind, inside the room. One slow blink event.

PHYSICS
Floorboards flex and sound under each step. Dust lifts on footfall and hangs, then drifts on the room's own
slow air. The branch is a real branch outdoors moving on real wind, and the part inside the room moves with
the same motion delayed by its length. Leaf litter lifts at its edges on the draught through the opening.
Wallpaper sheets move only at their loose edges. Nothing in either room is disturbed by the walk.

COLLIDER — the camera is a body, not a flying camera
The camera has a physical body attached to it. The body is never seen, but it occupies space and it has
mass, and nothing in the world passes through it.
Do not place anything in the path. Do not invent obstacles in front of the camera — the way ahead stays
clear and open.
But if anything does end up in the path — a branch grown in through a window, a sapling on the steps, tall
grass through the concrete, hanging debris — it reacts. It bends, shakes and folds away where the unseen
body meets it, and it recovers a beat later. It is never passed through as if it were not there.
Underfoot: dust, fallen plaster, broken glass, dry leaves and moss react to every step — the surface
compresses or shifts under the weight, and settled dust lifts where the foot lands.
No arms, no hands, no shoulders, no legs and no feet ever enter frame. What is seen is the object reacting,
never the body that made it react.
No clipping. Nothing intersects or passes through the camera, and nothing touches the lens.

LIGHTING
Overcast daylight from the far wall of each room and nothing else. In the bedroom it rakes across the bed
frame and falls away toward the doorway, the wardrobe wall two stops under. In the living room the torn-out
opening is the brightest zone by two stops and falls away hard toward the cabinet wall, the corners going
to near black. No fill from the camera side.

AUDIO
Diegetic only — footfall on old boards and carpet, boards flexing, breath, wind at the window opening,
leaf movement, a branch scraping the frame edge, glass grit underfoot, a dead flat interior tone. No music.
No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, veneer, rusted iron, rotted fabric, glazed cabinet, carpet fibre, bark and leaf at material
level, clean detail in the dark corners, no jitter, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people visible in either shot. No hands, no arms, no feet, no body part and no cast shadow of the
viewer enters frame at any time. NO MIRROR in either room, and THE GLAZED CABINET NEVER RETURNS A FACE —
it reflects only the window and the room. No photographs, no portraits, no dolls, no toys, no legible text
anywhere in frame. Exactly ONE tree branch through exactly ONE window opening. Nothing is touched or moved.
Exactly ONE hard cut, at 8.0 seconds. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9. 16s. SFX only. NO CGI. Cinematic.
```

---

# 08 · KITCHEN · 14s · 2:32

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. No body, no hands, no arms, no feet, no shadow of
the viewer at any point. A person walks into the kitchen of the flat. Everything is in place and everything
is long dead. One continuous 14-second take, no cuts.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@loc_MC_home_appartment for location reference — take only the space and the texture: a small Soviet
kitchen, a rounded enamel fridge in the far corner with rust bleeding through the paint, a table under the
window with objects still standing on it, open shelves above, oilcloth curled and blackened, dark mould
blooming across the wall above the sink, floor under plaster and grit. Do not use as a starting frame, do
not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
First frame is already inside the kitchen doorway: the fridge in the far LEFT corner, the table under the
window at frame-CENTRE, the shelves above it at frame-RIGHT. No empty establishing beat.

FORMAT MODE
Single continuous take, real time, no cuts.

OPTICS
84° diagonal field of view, classic wide lens character, camera one and a half metres inside the room. The
whole kitchen stays visible to the frame edges, deep edge-to-edge focus, straight lines stay rectilinear,
no fisheye curve.

CAMERA
The camera is a body: two slow steps in, a stop, then one slow continuous head turn from the fridge across
to the shelves and down to the table, with no reversal mid-turn. Handheld with breath-driven micro-motion
throughout. No push, no zoom.

ACTION TIMING
0.0–3.0s — two slow, unhurried steps in; the fridge and the table both come fully into frame; dust lifts
where the feet land.
3.0–7.0s — the body stops. The gaze travels slowly left to right across the fridge, the mould wall and the
shelves.
7.0–11.0s — the gaze settles on the table and the objects still standing on it.
11.0–14.0s — held. Dust in the window light and nothing else. One slow blink event.

PHYSICS
Floorboards and grit under each step. Dust lifts on footfall and hangs. The curled oilcloth moves only at
its lifted corner on the draught. Nothing on the shelves moves. Nothing is touched.

COLLIDER — the camera is a body, not a flying camera
The camera has a physical body attached to it. The body is never seen, but it occupies space and it has
mass, and nothing in the world passes through it.
Do not place anything in the path. Do not invent obstacles in front of the camera — the way ahead stays
clear and open.
But if anything does end up in the path — a branch grown in through a window, a sapling on the steps, tall
grass through the concrete, hanging debris — it reacts. It bends, shakes and folds away where the unseen
body meets it, and it recovers a beat later. It is never passed through as if it were not there.
Underfoot: dust, fallen plaster, broken glass, dry leaves and moss react to every step — the surface
compresses or shifts under the weight, and settled dust lifts where the foot lands.
No arms, no hands, no shoulders, no legs and no feet ever enter frame. What is seen is the object reacting,
never the body that made it react.
No clipping. Nothing intersects or passes through the camera, and nothing touches the lens.

LIGHTING
Overcast daylight from the window behind the table — the table edge and the objects on it are rim-lit
against it, the fridge corner sits two and a half stops under, the mould wall is the darkest value in
frame. No fill from the camera side.

AUDIO
Diegetic only — footfall on grit, breath, a slow irregular drip somewhere out of frame, wind at the window
opening, a small hard-surfaced room tone. No music. No narration. No voices.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, chipped enamel, rust bleed, mould bloom and curled oilcloth at material level, clean detail in
the dark corner, no jitter, no flicker.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Zero people visible. No hands, no arms, no feet, no body part and no cast shadow of the viewer enters frame
at any time. No mirror and no reflective surface that could return a face — the window glazing is gone, not
intact. No legible text or branding on any object or packaging. Exactly ONE fridge, never duplicated.
Nothing in the kitchen is touched or moved. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9. 14s. SFX only. NO CGI. Cinematic.
```

---

# 09 · HOME EXIT · 20s · 2:46 (crosscut — see ENDING ASSEMBLY)

```
SCENE CONTEXT
EXACT 1 CHARACTER — NO DUPLICATES: MR CHAMELEON. He stands outside the entrance of the block looking out
toward the street, tiny under a huge sky with the reactor confinement on the horizon far behind him. The
camera then moves in on him without stopping, all the way to a close framing of the face, settles, and
holds — and his dark pupils take on a green cast from inside. Controlled multi-shot sequence with ONE HARD
CUT at 3.0 seconds. Real time.


ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.
ACTIVE REFERENCES
@char_MC_mr_chameleon for character reference — standing still, muted field clothing, a dark half-mask
covering the lower face up to just under the eyes; turned away from the lens in the first shot, facing
camera in the second with only the eyes and brow uncovered.
@loc_MC_home_area for location reference — take only the space and the texture: the entrance and courtyard
of a derelict concrete apartment block, overgrown asphalt, birch saplings, empty window openings, and far
off on the flat horizon a vast arched steel confinement structure seen through haze. Do not use as a
starting frame, do not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
SHOT A first frame already contains him: MR CHAMELEON standing at the block entrance in the lower-LEFT
third of frame, small, facing out toward frame-RIGHT in three-quarter profile with the head turned away
from the lens. The arched confinement structure sits on the horizon frame-RIGHT of centre, compressed
large behind him. Camera elevated, one hundred metres out.
SHOT B first frame already contains him: MR CHAMELEON at frame-CENTRE in a medium-wide framing, head and
torso in the upper two-thirds, the block façade behind him, courtyard vegetation at the lower frame edge.
Camera at eye height, six metres out, already moving.

FORMAT MODE
Controlled multi-shot: SHOT A 0.0–3.0s locked telephoto wide, HARD CUT, SHOT B 3.0–20.0s continuous push
and hold. Real time, no speed ramps. NO fade, NO crossfade, NO dissolve, NO transition effect. HARD CUT
only.

OPTICS
SHOT A — 18° diagonal field of view, classic telephoto lens character, camera one hundred metres from the
subject. Strong background compression stacks the confinement structure close behind him despite the real
distance. Only the figure and the near façade are sharp; the horizon sits soft in haze. Close framing
achieved through lens reach, not physical proximity.
SHOT B — 29° diagonal field of view, short telephoto portrait lens character, camera travelling from six
metres to two metres. The lens character does NOT change during the move — the framing tightens because
the camera travels. Background compresses closer behind him and dissolves into soft bokeh as the distance
closes. Face proportions stay flattering and stable throughout.

CAMERA
SHOT A — locked off on a long lens on a heavy head, faintest thermal drift, no move at all.
SHOT B — one move only: a slow, continuous, dead-straight dolly toward him on the lens axis at one
constant rate, steadicam-smooth with the faintest operator breath. It does not accelerate, does not pause,
does not drift off axis, does not arc, and there is no zoom at any point. It comes to rest at 15.0s and
does not move again.

ACTION TIMING
0.0–3.0s — he stands completely still, looking out. Vegetation across every depth of the frame moves on
wind; he does not. His clothing moves; his body does not.
3.0s — HARD CUT.
3.0–8.0s — the approach begins already at speed; his torso and head grow steadily in frame; his eyes are
on the lens from the first frame and never leave it.
8.0–12.0s — the framing tightens to head and shoulders. The half-mask reads fully now: everything below
the eyes is covered, and the eyes are all there is. One slow blink. There is no expression available to
read, and that is the event.
12.0–15.0s — the framing closes onto the eyes and brow alone, the top edge of the mask across the lower
frame. Breath moves the mask fabric twice, visible at this distance. One quick double-blink, then one hard
reset-blink. The camera comes to rest at 15.0s.
15.0–17.0s — completely locked. He holds still. Nothing happens.
17.0–20.0s — the change begins inside the pupils: a green cast rises from within the dark of the pupil
outward, slowly, like a filter coming up behind glass. It is a change of colour only. He does not react in
any way, and the green is still there in the final frame.

PHYSICS
He is a standing body, not a statue: micro-sway at the shoulders, breath visibly lifting and dropping the
chest, hair and collar moving on the courtyard wind. The camera's own mass shows as a very slight vertical
float on the dolly. The green sits BEHIND the wet surface of the eye, under the corneal reflection, never
on top of it; the sky catch-light stays exactly where it was throughout and is never overwritten.

COLLIDER — his body displaces what it touches
Nothing in the world passes through him. No grass, branch or object intersects his body or his clothing at
any point.
Do not place anything in his path and do not invent obstacles for him — he walks a clear route, and the
vegetation lives around him rather than in front of him.
But whatever he does walk through reacts: grass parts around his shins and closes behind him, folds under
each footfall and springs back a beat later, leaving a flattened track behind his walk. Anything he brushes
bends away and recovers.
Dust and grit lift where his feet land. He never changes pace for any of it and never looks at it.
No clipping, no intersection, no vegetation ignoring his mass.

LIGHTING
Flat overcast from a high sky in both shots — one light, one time of day, no hard shadows. His eyes carry a
clear catch-light from the open sky; the eye sockets stay open and readable, never crushed. Nothing in the
frame gets brighter when the pupils change — the face is not lit by them. No fill from the camera side, no
bounce.

AUDIO
Diegetic only — open wind across the courtyard, vegetation, distant crows, his breath arriving as the
camera closes. The ambience does not change when the eyes do. No music. No narration. No voices. No sound
effect on the change.

CHARACTER ACTING
MR CHAMELEON — completely at ease. What he wants in this moment: nothing at all, and that is what makes it
land. What he is hiding: nothing, because he does not believe there is anything to hide. Dominant body
rhythm: still, grounded, unhurried breathing that never quickens as the camera closes. Visible habits in
this beat: the phased blinking, the total absence of the micro-adjustments a person makes when watched, the
eyes tracking the lens without effort. What changes across the shot: nothing about him changes — holding
that unbroken while a camera walks into his face, and then not reacting when his own eyes change, is the
entire performance.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, pore-level skin around the eyes, brow and temple, individual lashes, iris fibre structure at
the closest framing, woven mask fabric texture, wet living eyes with catch-lights, no jitter, no flicker,
no identity drift between the first and last frame.

POSITIVE CONSTRAINTS
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching the lens. Nothing is placed in the path; but anything that does end up in it bends, shakes and recovers instead of being passed through.
Exactly ONE person in the entire sequence and no one else anywhere. In SHOT A he is turned away and never faces camera. In SHOT B he faces camera and holds the lens for the whole shot — he never
looks away, never turns his head, never steps back, and his expression stays neutral throughout with no
smile and no widening of the eyes. THE MASK NEVER COMES OFF and never slips — everything below the eyes stays
covered for the entire shot, and the eyes and brow match the reference exactly at every distance in the
move. The green stays INSIDE the pupils only: no glow on the skin, no light cast on the face, no light in the air, no
lens flare, no particles, no rays. Both eyes change identically and at the same rate. The catch-light stays
in both eyes throughout. Exactly ONE confinement structure on the horizon, never duplicated. No vehicles,
no aircraft, no lit windows, no smoke. Exactly ONE hard cut, at 3.0 seconds. No vignette, no edge darkening, even exposure corner to corner. Photoreal. NON-IP. 16:9. 20s.
SFX only. NO CGI. Cinematic.
```

---

# 10 · BASEMENT · 16s · (crosscut — see ENDING ASSEMBLY)

```
SCENE CONTEXT
EXACT 1 CHARACTER — NO DUPLICATES: THE WORKER. Strict first-person POV from a seated position, low, in a
low basement room with the door shut. No body, no hands, no arms, no feet, no shadow of the viewer at any
point. A woman in a white coat works at a table, loading syringes and moving instruments, and never looks
over. Partway through, a fine structured pattern begins to surface on her skin. She notices nothing. One
continuous 16-second take, no cuts.

ACTIVE REFERENCES
@char_MC_employee for character reference — a woman in a white medical coat, medical mask pulled down under
her chin with her face open, standing at the table with her head down over her work, back three-quarters to
the room, neck and hands exposed.
@loc_MC_basement for location reference — take only the space and the texture: a low windowless
institutional basement room, painted brick walls, a work table against the far wall, glass syringes, tubes
and instrument trays on it, one dim overhead fixture, a mirror mounted on the wall above the table, a
closed steel door. Do not use as a starting frame, do not inherit the composition, the angle or the grade.

GEO SPATIAL LAYOUT (locked across both basement shots — pure spatial map):
— ROOM = a low windowless basement room about seven metres deep, painted brick walls, concrete floor.
— THE DOOR: a closed steel door in the FAR wall, dead ahead of the seated viewpoint, six metres away.
  It stays shut for the whole scene.
— THE WORK TABLE: against the LEFT wall, three metres from the seated viewpoint, FRONT-LEFT in frame.
— THE MIRROR: mounted on the LEFT wall directly above the work table, facing across the room.
— THE WORKER: standing at the table, front-left, body turned to the table and the mirror, back
  three-quarters to the seated viewpoint, head down over her work.
— CAMERA POSITION 1 (generation 10): the seated viewpoint — low, on the near side of the room, facing
  the far door, with the table and the worker at FRONT-LEFT.
— CAMERA POSITION 2 (generation 11): standing height, behind the worker and half a metre to HER LEFT,
  looking over her shoulder into the mirror on the left wall.
— 180° AXIS: both camera positions live on the same side of the worker. The camera NEVER crosses to the
  far side of the table, and the door is ALWAYS ahead of camera, never behind it.
— LIGHT: one dim overhead fixture directly above the work table. The door end of the room falls away
  two stops into shade. No daylight anywhere.

COLOUR AND GRADE
Neutral white balance, no colour cast of any kind. Natural saturation — the coat reads true off-white, the brick reads neutral. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones readable, shadows dark but never crushed to black — detail visible in every part of frame.
Medium contrast. NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.

FIRST FRAME AND SPATIAL BLOCKING
First frame already contains her: THE WORKER at the work table at FRONT-LEFT, three metres from the seated
viewpoint, body turned to the table, back three-quarters to camera, head down over the instruments. The
mirror is on the LEFT wall directly above her. The closed steel door sits dead ahead in the far wall, six
metres out, and holds the centre of frame. The camera is low — the table edge sits high in frame. No empty
establishing beat.

FORMAT MODE
Single continuous take, real time, no cuts.

OPTICS
84° diagonal field of view, classic wide lens character, camera three metres from her and low. The whole
room stays visible to the frame edges — her at front-left, the shut door dead ahead — with deep
edge-to-edge focus so she and the mirror above her are both readable. Straight lines stay rectilinear, no
fisheye curve, no portrait bokeh.

CAMERA
The camera is a seated body: breath-driven micro-motion only, a small settle, and one very slow lean
forward of a few centimetres in the second half as the attention narrows onto her. It stays low and never
rises. No push, no pan, no zoom.

ACTION TIMING
0.0–4.0s — she draws liquid into a glass syringe, taps it, sets it on the tray. Her head stays down. She
does not look over, not once.
4.0–7.0s — she moves a tube from one rack to another; glass touches glass; her shoulders work but her head
never lifts.
7.0–11.0s — on the back of her neck and the back of her working hand, a fine structured pattern begins to
surface UNDER the skin — very low contrast at first, like a watermark coming up in paper, following the
curve of the body beneath it.
11.0–16.0s — the pattern reaches full density across the neck, the hand and the forearm inside the cuff,
and moves with the skin as she works. She does not feel it, does not look, does not pause. The seated body
leans a few centimetres closer.

PHYSICS
Glass has weight and rings when set down. Liquid moves in the syringe barrel with real viscosity and
settles. The coat fabric moves a beat behind her arms. The pattern lives UNDER the surface of the skin and
deforms exactly with it — stretching over a tendon as the hand moves, compressing as the neck turns. It has
no light of its own and is never an overlay on top of the image. Her work rhythm is completely unchanged
throughout.

LIGHTING
One dim overhead fixture directly above the table: she is lit from above with her eye sockets in shadow,
the tray surface catching the brightest value, the room falling away into deep shade at every edge. Nothing
in the room gets brighter as the pattern appears. No fill from the camera side.

AUDIO
Diegetic only — glass on metal, a drawer, liquid drawn into a barrel, the low hum of the overhead fixture,
a small dead hard-walled room tone, no sound at all from outside the room. No music. No narration. No
voices. Nobody speaks. No sound effect on the pattern.

CHARACTER ACTING
THE WORKER — absorbed and routine. What she wants in this moment: to finish the tray and move on. What she
is hiding: nothing — she is not performing for anyone, and her total lack of awareness of being watched is
the whole read. Dominant body rhythm: economical, practised, unhurried, no wasted movement. Visible habits
in this beat: the head stays down, the shoulders carry the work, one exhale through the nose between tasks.
What changes across the shot: nothing about her changes at all — the marks arrive on a body that is not
aware of them, and the absence of any reaction is what makes them frightening.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, glass, enamel, coat fabric and pore-level skin with the pattern reading as structure beneath it,
clean detail in the deep shade at the room edges, no jitter, no flicker.

POSITIVE CONSTRAINTS
Exactly ONE person in the room and no one else. No hands, no arms, no feet, no body part and no cast shadow
of the viewer enters frame at any time. THE MIRROR SHOWS ONLY HER AND THE ROOM — it never returns a face at
the camera position and never shows a second person. She NEVER looks at the camera and NEVER looks at the
mirror. The door in the far wall stays shut and nobody comes through it. The pattern is NOT LANGUAGE — no letters, no numerals, no legible text, no symbols in any alphabet
or script. The pattern DOES NOT GLOW — no light, no colour, no emission, no particles, no floating elements
in the air, no overlay, no screen effect. It appears only on the neck, the hand and the forearm, never on
the coat, the walls or the instruments. The door stays closed for the whole take. Nobody speaks. Photoreal.
NON-IP. 16:9. 16s. SFX only. NO CGI. Cinematic.
```

---

# 11 · BASEMENT 2 · 20s · (crosscut — see ENDING ASSEMBLY)

```
SCENE CONTEXT
EXACT 2 CHARACTERS — NO DUPLICATES BEYOND THESE TWO: THE WORKER and THE COPY. The camera moves in behind
the woman at her table toward the mirror above it, stops, and holds on the glass. A second woman with the
identical face walks into the reflection in ordinary clothes. The worker lifts her head, sees her own copy,
and screams. One continuous 20-second take, no cuts.

ACTIVE REFERENCES
@char_MC_employee for character reference — a woman in a white medical coat, medical mask pulled down under
her chin, standing at the table with her head down over her work, seen from directly behind.
@char_MC_employee_civil for character reference — THE SAME WOMAN'S FACE, in ordinary civilian clothes, no
coat and no mask, standing upright and calm.
@loc_MC_basement for location reference — take only the space and the texture: the same low basement room,
work table, instruments, dim overhead fixture, and the mirror mounted on the wall above the table. Do not
use as a starting frame, do not inherit the composition, the angle or the grade.

GEO SPATIAL LAYOUT (locked across both basement shots — pure spatial map):
— ROOM = a low windowless basement room about seven metres deep, painted brick walls, concrete floor.
— THE DOOR: a closed steel door in the FAR wall, dead ahead of the seated viewpoint, six metres away.
  It stays shut for the whole scene.
— THE WORK TABLE: against the LEFT wall, three metres from the seated viewpoint, FRONT-LEFT in frame.
— THE MIRROR: mounted on the LEFT wall directly above the work table, facing across the room.
— THE WORKER: standing at the table, front-left, body turned to the table and the mirror, back
  three-quarters to the seated viewpoint, head down over her work.
— CAMERA POSITION 1 (generation 10): the seated viewpoint — low, on the near side of the room, facing
  the far door, with the table and the worker at FRONT-LEFT.
— CAMERA POSITION 2 (generation 11): standing height, behind the worker and half a metre to HER LEFT,
  looking over her shoulder into the mirror on the left wall.
— 180° AXIS: both camera positions live on the same side of the worker. The camera NEVER crosses to the
  far side of the table, and the door is ALWAYS ahead of camera, never behind it.
— LIGHT: one dim overhead fixture directly above the work table. The door end of the room falls away
  two stops into shade. No daylight anywhere.

COLOUR AND GRADE
Neutral white balance, no colour cast of any kind. Natural saturation — the coat reads true off-white, the brick reads neutral. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones readable, shadows dark but never crushed to black — detail visible in every part of frame.
Medium contrast. NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across the entire frame.

FIRST FRAME AND SPATIAL BLOCKING
First frame already contains her: THE WORKER seen from behind and half a metre to HER LEFT, filling the
lower two-thirds of frame at frame-CENTRE-RIGHT, her shoulder in the near foreground. The mirror on the
LEFT wall above the table holds the upper frame, her reflection already visible in it, head down. The shut
steel door is out of frame behind camera-right. Camera at standing height, three metres back, already
moving. No empty establishing beat.

FORMAT MODE
Single continuous take, real time, no cuts, no speed ramps.

OPTICS
47° diagonal field of view, standard normal lens character, camera travelling from three metres to one and
a half. Natural proportions, no distortion of the room or the mirror frame, comfortable depth of field with
both her back and her reflection readable. The lens character does not change during the move.

CAMERA
One move only: a slow, continuous push forward and slightly left, past her shoulder and in toward the
mirror on the left wall, at one constant rate, steadicam-smooth with the faintest operator breath. It does not accelerate, does not arc, and there is no
zoom. It comes to rest at 7.0s and does not move again — except for the faintest handheld tremor arriving
in the final three seconds, where the camera reacts a fraction and the copy does not.

ACTION TIMING
0.0–4.0s — the push begins already at speed; her back fills the lower frame; her reflection in the mirror
is small and clear, head down over the work.
4.0–7.0s — the camera passes her shoulder; the mirror opens up and fills the upper half of frame; her
reflected face is now readable, still angled down. The camera comes to rest.
7.0–10.0s — held. She works on. The right side of the glass shows only the empty room behind.
10.0–13.0s — THE COPY walks into the reflection from the RIGHT edge of the mirror and stops at
frame-CENTRE-RIGHT inside the glass, upright, facing the mirror. Both faces are now in the glass at once.
Neither reacts. THE WORKER still has not lifted her head.
13.0–14.5s — held. THE COPY stands completely still and does not look at her.
14.5–16.0s — the worker's head lifts — the eyes reach the glass before the head finishes moving. Then the
assessment: her face does nothing for almost a full second, the hands stop, the breath stops, and only the
eyes move, from her own reflection to the one beside it and back.
16.0–20.0s — it lands. She is ALREADY mid-scream at 16.0s — the mouth ALREADY wide, the throat ALREADY
working, the sound ALREADY at full — no wind-up. Her hands come up and grip the sides of her head, the
shoulders climb toward her ears, the torso folds forward over the table. The scream continues and breaks
into a ragged intake. She does not look away from the glass. THE COPY has not moved a millimetre through
any of it.

PHYSICS
The reflection is geometrically correct for the camera's changing position during the push — her reflected
position shifts across the glass as the camera travels. THE COPY walks with real weight: heel contact, mass
transfer, a settle when she stops, clothing moving a beat behind her; after she stops she is completely
inert and her clothing does not move at all. Real vocal effort on the scream: the throat works, the chest
empties, the neck tendons stand out, the shoulders rise with the breath and drop. The hands grip with real
pressure and deform the hair and skin at the temples. Instruments on the table ring and shift as her torso
folds against it. The glass carries a faint dust haze in front of both figures equally.

LIGHTING
One dim overhead fixture above the table, unchanged for the whole take. She is lit from above and behind,
so the camera side of her back is the darkest value in frame and the mirror is a stop brighter than she is.
Both figures in the glass are lit from the same source in the same direction. Nothing brightens when the
second woman arrives, nothing flickers, no light changes at any point. Her open mouth is the darkest value
in the final frames. No fill.

AUDIO
Diegetic only — glass and instruments at the table, the fixture hum, a small dead hard-walled room tone,
one set of quiet footsteps arriving and stopping, instruments ringing as she folds over the table, and one
human scream, raw and unmodulated, from THE WORKER and nobody else, with real short reverberation on the
voice. This is the ONLY human vocal sound anywhere in the film. No music. No narration. No words — the
scream contains no language. (Written out in full because a written scream is a physical
instruction — it gets a throat working, tendons standing out, a chest emptying, shoulders climbing. The
generated scream is kept and used.)

CHARACTER ACTING
THE WORKER — for the first thirteen seconds: absorbed, routine, head down, hands working, no awareness of
anything, a camera walking up behind her that she never registers. Then: what she wants is for what she is
looking at to not be there; what is in her way is that it is there, and it is her; and what she is hiding is
nothing at all — this is the one moment in the film where somebody stops managing their face. Dominant body
rhythm: absolute stillness for a second and a half, then everything at once, then a ragged aftermath that
does not recover. Visible habits in this beat: the eyes reaching the glass before the head does, the total
physical stop before the break, the hands going to the head rather than to the table.
THE COPY — no want, no concealment, no reaction, no movement. Weight settled evenly, hands loose at her
sides, face completely neutral with no expression played on it. She does not look at the worker and does
not look at herself; she simply looks into the glass. She is not frightened and she is not gloating. She is
simply present, and the fact that she does not react is worse than anything she could do.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Interiors lit only by window light falling away into the room. Key light from sky and windows only. No fill from the camera side.
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

QUALITY
8K detail, pore-level skin on both faces, identical facial structure between the two, glass surface dust
resolved, tendon and throat detail on the scream, no jitter, no flicker, no identity drift between the
woman and her copy at any point.

POSITIVE CONSTRAINTS
EXACTLY TWO people in the whole take and no one else anywhere in frame — never a third, never a further
reflection, never a duplicate at the edge of the glass. For the first ten seconds there is exactly ONE
person and ONE reflection. BOTH FACES ARE THE SAME FACE, matching the reference exactly: identical bone
structure, identical features, identical hair. They differ ONLY in clothing — one in a white coat with a
mask under the chin, one in ordinary clothes with no coat and no mask. THE COPY stays completely motionless
after she stops — she never flinches, never turns, never changes expression, never speaks, and does not
react to the scream. Only THE WORKER makes sound, and that sound is a scream with no words in it. The
camera stays on the door side of the room and never crosses behind the table. The overhead light does not
flicker, dim or change colour. No green, no glow, no pattern and no effect anywhere in this shot. Photoreal.
NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic.
```

---

# ENDING ASSEMBLY — CROSSCUT (edit only, no extra generations)

Generations 09, 10 and 11 are generated **whole, exactly as written**, then sliced and interleaved in the
edit. Same footage, same 56 seconds, zero extra cost — the escalation comes from the cutting.

**Why it is cut this way.** Generation 09 is one continuous push, so every time the edit returns to him the
camera is closer than it was before, automatically and perfectly matched. Four separate generations could
never do that. And it lets the film end on the scream instead of on him.

## Slice list

From **09** (20s): `WIDE` 0.0–3.0 · `A1` 3.0–8.0 · `A2` 8.0–12.0 · `A3` 12.0–20.0
From **10** (16s): `B1` 0.0–7.0 · `B2` 7.0–16.0
From **11** (20s): `B3` 0.0–13.0 · `B4` 13.0–20.0

## Assembly order

The ending starts at **3:20** in the film.

| # | Piece | Source | Len | Film time | What the audience gets | VO |
|---|---|---|---|---|---|---|
| 1 | `WIDE` | 09 | 3s | 3:20 | Him tiny, the reactor stacked behind him | — |
| 2 | `A1` | 09 | 5s | 3:23 | The approach starts | VO-09 @ 3:24 |
| 3 | `B1` | 10 | 7s | 3:28 | Cut away. A basement. She works, never looks up | VO-10 @ 3:29 |
| 4 | `A2` | 09 | 4s | 3:35 | Back to him — closer than we left him | — |
| 5 | `B2` | 10 | 9s | 3:39 | The marks surface on her skin | VO-11 @ 3:41 |
| 6 | `A3` | 09 | 8s | 3:48 | Back to him, closest — eyes above the mask, held, and the pupils go green | — |
| 7 | `B3` | 11 | 13s | 3:56 | Push to the mirror. The copy walks in. Nobody reacts | VO-12 @ 3:58 |
| 8 | `B4` | 11 | 7s | 4:09 | She lifts her head. The scream. **CUT TO BLACK** | VO-13 @ 4:10 |

**Runs out at 4:16.** Two seconds of held black, then the end card.


## Why it ends on the scream, not on him

Three reasons, and this is the one place I would argue hard for it:

1. **The scream is the only human voice in the entire film.** Three and a half minutes of wind and
   footsteps, and then one person loses her mind out loud. Ending anywhere else wastes the loudest thing
   you own.
2. **Quiet after a scream deflates.** His face is a still, ambiguous, low-energy image. Put it last and the
   film exhales on the way out. Put the scream last and it stops dead.
3. **VO-13 needs something to land against.** "But I am still good old me. Or am I?" over his own calm eyes
   is merely spooky. Over a woman screaming at her own double it is monstrous — he is being flippant about
   what he just did to somebody. That gap is the whole character.

The audience leaves holding the consequence, not the cause. His eyes still get their moment, at `A3`,
eight seconds long and closer than anything before it — but they are the second-to-last beat, not the last.

## If the green pupils get dropped

Replace them in `A3` with the marks surfacing under the skin around his own eyes — the same pattern the
audience watched arrive on her thirty seconds earlier. Keeps the ending deniable and ties the mechanism
together without a visual effect. One line changed in generation 09; everything else stays.

# GENERATION ORDER

## PHASE 1 — CHARACTER-FREE. 160 seconds of 256, or 62% of the raw material.

Ten of the fifteen generations contain no person at all. **Every one of them can be generated today** —
they need only location sheets, and no character asset has to be locked first.

| Gen | Length | Location sheets needed | What it is |
|---|---|---|---|
| 00 | 16s | `@loc_MC_forest` | POV, deep forest |
| 01 | 16s | `@loc_MC_forest` | POV, forest thinning to the road |
| 02 | 12s | `@loc_MC_pripyat_sign` | POV, the ПРИПЯТЬ sign |
| 02B | 14s | `@loc_MC_pripyat_entrance` | POV, into the city |
| 04A | 20s | `@loc_MC_pripyat_city` | Aerial pan, no people |
| 04B | 20s | `@loc_MC_school`, `@loc_MC_shop` | Three held interiors, dust only |
| 05A | 20s | `@loc_MC_park` | Ferris wheel, bumper cars, held |
| 05B | 12s | `@loc_MC_park` | Swings and the wide park, held |
| 07 | 16s | `@loc_MC_home_appartment` | POV, his room and the living room |
| 08 | 14s | `@loc_MC_home_appartment` | POV, the kitchen |

**Eight location sheets unlock all ten.** `forest`, `pripyat_sign`, `pripyat_entrance`, `pripyat_city`,
`school`, `shop`, `park`, `home_appartment`.

**Generate all eight sheets back to back in one sitting** — the ENVIRONMENT LOCK is only worth anything if
they come out of the same session. Come back a week later and the palette has drifted.

**Then generate 00, 01 and 02 back to back too**, in that order, and check them against each other before
moving on. They are one continuous walk under the ROUTE LOCK and the light has to climb across the three.

### Order inside phase 1

| Pass | Generations | Why |
|---|---|---|
| **1A** | 00, 01, 02, 02B | The opening walk. Route and light continuity is the one thing here that can fail, so prove it first. |
| **1B** | 07, 08 | POV interiors. Same camera language, no continuity chain to break. |
| **1C** | 04A, 04B, 05A, 05B | Held frames where almost nothing moves. Cheapest, lowest risk, generate last. |

## PHASE 2 — MR CHAMELEON. 60 seconds.

Blocked until `@char_MC_mr_chameleon` is `LOCKED`. Also needs `@loc_MC_dk_energetic`, `@loc_MC_home_area`,
`@loc_MC_home_stairs`.

| Gen | Length | Note |
|---|---|---|
| 09 | 20s | The push onto his eyes. **Hardest shot in the film — generate it first of the three**, while there is budget to solve it. |
| 06 | 20s | Entrance, stairwell, the door. |
| 03 | 20s | 16s of POV, then a 4s outside view of him after the hard cut. |

> **03 can be pulled forward if you want.** Only its last four seconds contain him. Generated as a 16s
> POV-only version it belongs in phase 1 and the outside view becomes a separate short generation later.
> It costs one extra generation and it unblocks 20 more seconds now.

## PHASE 3 — THE WOMAN. 36 seconds.

Blocked until `@char_MC_employee`, `@char_MC_employee_civil` and `@char_MC_employee_signs` are all `LOCKED`
— a separate character set from Mr Chameleon, and 11 needs two of them in the same frame. Also needs
`@loc_MC_basement` and `@loc_MC_basement_rev`.

| Gen | Length | Note |
|---|---|---|
| 11 | 20s | Two identical faces in one frame. The single hardest technical problem in the project. |
| 10 | 16s | The marks surfacing. |

**This is the order to generate in, not the order of the film.** The film runs 00 → 11.

# ITERATION LOG

| Gen | v | What changed from previous | Verdict |
|---|---|---|---|
| | | | |
