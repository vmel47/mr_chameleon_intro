# TEST · 02 · ROAD TO THE PRIPYAT SIGN · 20s · NO MOTION REFERENCE

**Experimental. Not merged into `SHOTLIST_PROMPTS.md` yet.**
**This is the words-only variant.** The version with the Blender animatic attached is `TEST_02_SIGN.md`.

---

## TWO REFERENCES — no animatic

This is the same shot as `TEST_02_SIGN.md`, with the grey Blender animatic removed. Everything the animatic
was carrying — when the gaze moves, how far it turns, where the sign stands — is written out in the prompt
instead, in degrees and seconds.

| # | What | Take from it | Take NOTHING else |
|---|---|---|---|
| 1 | `@loc_MC_forest_pripyat_sign_path` — forest with the road, red arrow | The route, the road surface, the verges, the forest, the season, the light, the palette | Its aerial height — the camera is at eye level |
| 2 | `@loc_pripyat_sign_2` — the edited sign frame | The sign: shape, lean, flaking paint, rusted 1970, concrete pier — and its place on the right verge, turned slightly toward the road | Its camera position, distance and framing |

**Which version to use.** Run this one first. Two references fight each other less than three, and a video
reference is the most invasive kind — it drags its gait, its shake and its flat grey look in with it, and
those have to be argued out of it line by line. If the movement comes back wrong here, switch to the
animatic version, where the schedule is shown rather than described.

**Where the numbers came from.** They are not invented. The geometry was built in Blender, measured, and
then written down: the sign 9 metres right of the centreline and 36 metres ahead at the first frame, a walk
of 2 metres per second, eye height 1.7 metres. Everything below follows from those four numbers.

## Where the narration lands

`VO-02 "Home, sweet home."` goes in at **+8.0s**, in the middle of the stretch where the gaze is on the sign.
The line and the look are one event: he glances over, says it, goes back to the road. The prompt itself
carries `No narration` — the voice is recorded separately and added in the edit.

## Why 20 seconds

Twenty seconds is what the geometry needs. At a calm walking pace the sign has to start far enough away to
read as a distant roadside object, and he has to actually walk past it and leave it behind — that is thirty
to forty metres of road. Cut it to sixteen and either he starts almost on top of the sign or he never gets
past it.

---

# THE PROMPT — copy and go

```
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. No body, no hands, no arms, no shoulders, no feet
and no cast shadow of the viewer enters frame at any moment. We only ever see what he sees.

SCENE CONTEXT
He is out of the forest and walking the road into an abandoned city. A concrete city sign stands ahead on
the right-hand verge. He does not stop for it. He has walked past it thousands of times and it is not news
to him.

GAZE AND GEOMETRY — written out, no motion reference attached
The layout. He walks down the centre of the road at an even, unhurried pace. The sign stands on the grass to
the RIGHT, about nine metres out from the centre line — that is roughly five metres clear of the asphalt
edge — and about thirty-six metres ahead of him in the first frame. He is level with it at seventeen and a
half seconds and past it after that. He never leaves the road and never walks toward it.

What that means on screen. Because the sign sits off to one side, it drifts steadily toward the right edge
of frame as he closes on it, and it slides out of frame entirely while he is still looking straight ahead.
That is correct and expected. It comes back into the picture only because the gaze turns to it — never
because the shot changes.

The gaze. It turns to the right by about twenty degrees, which is roughly a fifth of the way from straight
ahead to square to the side: enough to carry the sign from the right edge into the middle of frame, and no
more. It never turns as far as ninety degrees, never looks over his shoulder, never looks behind. While the
gaze rests on the sign it eases a further ten degrees round, slowly and continuously, reaching about thirty
degrees — because he is still walking past it, and holding your eyes on something you are walking past
requires the neck to keep giving.

How the movement itself must look. Like a person, not like a camera. It is a neck under a skull, not a
motor on an axis. The eyes arrive a fraction before the head does. The movement accelerates quickest
through the first third and eases out longer at the end, never at a constant rate. It settles when it
arrives, with the faintest give as it stops. While the gaze is held it is not locked or frozen: it carries
tiny living instability, a fraction of a degree of wander that never stops. And the head tips very slightly
downward through the middle of each turn and comes back up — real heads travel on an arc, not on a flat
plane.

What must NOT happen. No constant-speed pan. No mechanical sweep. No snap. No linear rotation. No second
movement after the first in either direction: one movement out at five seconds, one movement back at ten
and a half, and nothing else — no correction, no adjustment, no small extra shift. The walk does not react
to any of it: it keeps the same pace and the same rhythm underneath the whole turn.

ACTIVE REFERENCES
@loc_MC_forest_pripyat_sign_path for the route and the world — take the road, its surface and its verges, the forest on
both sides, the season, the daylight and the palette. The shot happens in exactly this place, in exactly
this weather, at exactly this time of year, and the walk follows this road in the direction of the arrow.
Do not use it as a starting frame and do not inherit its aerial height, its composition or its angle — the
camera is at the eye level of a walking person, about 1.7 metres from the ground, and never rises above
1.8 metres.

@loc_pripyat_sign_2 for the sign — take the object exactly as it appears: the leaning wedge-shaped
concrete slab, the raised block letters ПРИПЯТЬ standing along its top edge, the rusted orange 1970 plate
on its face, the stained concrete pier under it, the white paint flaking away in patches with bare grey
concrete showing through, the chipped letter edges. Take its position too: standing back on the grass verge
to the RIGHT of the road, off the asphalt, turned slightly toward the road so its face meets a traveller
coming into the city at an angle rather than square on. Do not use it as a starting frame and do not
inherit its camera position, its distance or its framing — in this shot the sign begins far away, grows on
the walk, and is passed.

ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything
overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft
warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: light haze thickening with distance, pollen drifting in the bright gaps.
Time: 1:00 PM, early afternoon daylight.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast
of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, sky reads pale blue. No
teal-and-orange, no bleach bypass, no film emulation LUT, no stylised grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky
retained and never clipped, shadows dark but never crushed to black — detail visible everywhere in frame.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner across
the entire frame.

FIRST FRAME AND SPATIAL BLOCKING
Eye level of a walking adult, walking down the centre of the road. The frame is centred on the road running
away from camera into the distance. Old cracked asphalt, weeds through every seam, the edges eaten back
into gravel and grass, holding the lower half of frame. Green forest walls on both sides, birch and poplar
in full leaf, undergrowth up to the verge. Sky and broken cloud across the top third.
The concrete city sign is IN THE FIRST FRAME, ahead and to the RIGHT, standing back on the grass verge,
already clearly visible. As the walk closes on it, it grows and drifts toward the right edge of frame and
eventually out of it — that is simply what a roadside object does when the eyes are on the road. It comes
back into the picture only when the gaze turns to it, and it is never cut to and never cut away from.
Nothing else is built anywhere in frame: no vehicles, no people, no wires, no fences, no billboards.

FORMAT MODE
ONE single continuous unbroken take. No cuts of any kind — no hard cut, no jump cut, no transition, no
dissolve, no change of camera position, no separate shots. The whole twenty seconds is one uninterrupted
walk from one camera. The sign entering or leaving the picture always happens because the walk moved or the
gaze turned — never because the shot changed.

OPTICS
47° horizontal field of view — normal, the way an eye reads a road. Deep focus: the asphalt underfoot and
the treeline at the horizon are both sharp. No rack focus, no shallow depth of field, no lens flare, no
anamorphic streaks, no fisheye, no barrel distortion at the edges.

CAMERA
The camera is a walking body moving at a slow, calm, unhurried gait, not a rig: gentle vertical rise and
fall on each stride, small lateral sway, organic imperfect correction after every step. It never stabilises
into a glide. He walks ALONG the road and stays on the road — he is not walking toward the sign, the sign
simply stands beside the road and is passed.

ACTION TIMING
0.0–5.0s — walking forward down the road at an unhurried, calm, leisurely cinematic pace; the gaze is
straight ahead down the centre of the road and stays there; the verges pass steadily on both sides. The
sign stands over on the right and grows as the walk closes on it, drifting toward the right edge of frame —
he simply does not look at it.
5.0–6.5s — the gaze turns to the right onto the sign. The slow walk continues underneath the turn without
breaking rhythm.
6.5–10.4s — the gaze rests on the sign: ПРИПЯТЬ across the top, 1970 below, flaking paint and rust. He is
still walking, so the sign keeps growing and the gaze keeps easing round a little to stay on it.
10.4–12.6s — the gaze returns to the road ahead, a little slower than it left.
12.6–17.5s — walking on down the road, gaze straight ahead. He draws level with the sign and passes it: it
slides across the right of frame, foreshortens as he goes by, and leaves frame behind him. He does not look
at it again and does not look back.
17.5–20.0s — the road ahead with nothing on it. Forest thinning on both sides, and in the far haze the
first flat roofline of the city separating from the treeline. The calm, steady walk continues unbroken to
the last frame.

COLLIDER — the camera is a body, not a flying camera
The camera has a physical body attached to it. The body is never seen, but it occupies space and it has
mass, and nothing in the world passes through it.
Do not place anything in the path. Do not invent branches, bushes or obstacles in front of the camera — the
road ahead stays clear and open, and the vegetation lives at the sides of frame, passing by as the walk
goes on.
But if anything does end up in the path — a bush, a clump of tall grass, a low branch, thick undergrowth —
it reacts. It bends, shakes and folds away where the unseen body meets it, and it recovers a beat later. It
is never passed through as if it were not there.
Grass and weeds underfoot bend and flatten where each step lands, then spring back after the foot lifts,
one beat behind the walk. Dust and pollen lift from the ground where the foot lands.
No arms, no hands, no shoulders, no legs and no feet ever enter frame. What is seen is the vegetation
reacting, never the body that made it react.
No clipping. Nothing intersects or passes through the camera, and nothing touches the lens.

PHYSICS
Weight transfer on every slow step: heel contact, mass settling, toe push-off. Consistent footfall bounce
on hard cracked asphalt. Wind moves the roadside grass in travelling waves and the birch leaves on a
separate faster frequency. Cloud moves at cloud speed. The sign is a heavy static mass and does not move at
all — only the grass around its base moves. Perspective shifts on the sign are produced by the walk alone.

LIGHTING
Full open afternoon daylight, no canopy overhead. Soft sun high and three-quarters behind: a warm rim runs
along the top edge of the slab and along the tops of the raised letters, and the face of the sign turned
toward camera sits a stop and a half under, so the lettering reads by its own relief and its own shadow
rather than by brightness. The light level is constant across the whole take and never drops. Mid-tones
open and readable, sky highlights retained and never clipped, shadows dark but never crushed.

AUDIO
Diegetic environmental sound only — soft footsteps on cracked asphalt and gravel, wind through roadside
grass and birch leaves, sparse distant bird calls, drifting insects. No music. No narration. No voices.
Nobody speaks.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only; painterly composed frames, strong silhouettes against the light.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind the subject — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Key light from sky only. No fill from the camera side.
Color: 60:30:10 — 60% new-growth birch and grass green, 30% weathered concrete grey and pale sky, 10% rust-orange oxidised metal.
Camera: Physical cine lens. 180° shutter motion blur.
Surfaces: Material-level realism — flaking paint, lichen crust, weathered concrete, rusted steel, cracked asphalt, decades of dirt in every seam. Nothing looks recently placed.
Physics: Gravity and inertia respected — mass has real weight, correct contact shadows. No floating props. Nothing passes through anything — no clipping, no intersection; whatever is touched bends, shakes and recovers a beat later.
Vegetation: Birch and poplar reclaiming the road — saplings through asphalt, weeds in every crack, tall grass across both verges, all of it moving on real wind.
Composition: Rule of thirds + golden ratio.
Continuity: Environment identical from the first frame to the last. No drift.
Technical: 24fps smooth motion. 8K detail. No jitter. No flicker. No vignette, no edge darkening, even exposure corner to corner.
Audio: Environmental SFX only. No music. No subtitles. No narration. No voices.

QUALITY
8K detail. Concrete, flaking paint and rust at material level. Legible relief lettering. Clean cloud
gradation. No jitter, no flicker.

POSITIVE CONSTRAINTS
Zero people visible anywhere. No hands, no arms, no feet, no body part and no cast shadow of the viewer
enters frame at any time. The slow walk never stops — the body keeps moving slowly forward through the
turn of the gaze, at the same pace, in the same direction, from the first frame to the last.
He walks along the road, not toward the sign. He never leaves the road, never turns his body, never steps
onto the verge and never approaches the sign. The camera does not arc, orbit or circle it.
ONE continuous take with ZERO cuts. Not three shots, not two shots — one. The camera never cuts away from
the road and never cuts back to it.
The sign is present in the world for the whole take. It is in the first frame, over on the right, and it
grows as the walk closes on it. It drifts toward the right edge and out of the picture while the eyes are
on the road, and it comes back in only because the gaze turns to it. Not looking at something is not the
same as it not being there, and it never appears from nowhere and never vanishes.
The gaze moves exactly TWICE in the whole take: out at 5.0s over about a second and a half, back at 10.4s
over about two seconds. Nothing else. No second adjustment, no correction afterwards, no small extra move
in either direction. Both are human head movements, not pans: quicker through the first third, easing out
longer at the end, settling on arrival. While the gaze is on the sign the head keeps easing further round,
because the body is still walking past it.
Exactly ONE sign in the whole take, standing on the RIGHT-hand verge, never duplicated, never in the middle
of the carriageway, never on the left. The lettering reads ПРИПЯТЬ in correct Cyrillic, sharp and legible,
with 1970 below it.
The sign is weathered and neglected — flaking paint, exposed grey concrete, rusted numerals. It is never
freshly painted, never restored, never clean.
No vehicles, no fences, no power lines, no billboards, no modern signage, no graffiti, no tourist markers,
no flowers or wreaths at its base, no barriers, no checkpoint.
Late spring, full new green, leaves on every tree. Not autumn, not winter, no bare branches, no brown grass.
Nothing passes through the camera or the body carrying it — no clipping, no intersection, nothing touching
the lens.
No vignette, no edge darkening, even exposure corner to corner.
Photoreal. NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic. Present tense. Short sentences.
```

---

## What makes this one cinematic rather than a location card

**The sign is unreadable for the first four seconds.** It is a shape on the grass before it is a word. The
audience does the resolving, and the letters arrive as a consequence of walking, not as a title.

**The letters come out one at a time.** They emerge as the angle opens, and the rusted 1970 lands last —
so there is a small delivered beat instead of a flat reveal.

**It is backlit, not lit.** The face turned to camera sits a stop and a half under and the letters read by
their own relief and their own shadow. Concrete lettering read by shadow is the whole reason this object is
photogenic; lighting it flat throws that away.

**Living against dead.** The grass at the base moves on the wind for the whole pass and the concrete does
not move at all. One shot, two states, no comment.

**He does not look.** Two or three degrees of head drift and back. The most expressive thing available here
is indifference — and it is also the only honest option, because a man who has lived here forty years does
not stop for the name of his own town.

**And it leaves.** The sign slides out of frame and the shot keeps walking without it. Nothing is held on,
nothing is underlined. The first roofline of the city is already coming up in the haze before the audience
has finished with the sign.

---

## If it comes back wrong

| Symptom | Fix |
|---|---|
| The camera stops or slows at the sign | Repeat `the walk never stops and never slows` inside the 7.0–9.5s beat |
| The sign is centred instead of passing in the right third | Add `the sign never enters the centre of frame; it stays in the right third and exits at the right edge` to FIRST FRAME |
| The sign is readable from the first frame | Strengthen 0.0–4.0s: `an angular pale mass with no readable detail of any kind` |
| Garbled Cyrillic | Generate with the slab blank and add `ПРИПЯТЬ` and `1970` in Nano Banana Pro with the exact strings in quotes |
| Aerial or high angle | The eye-level clause is already in the reference 1 line — repeat it in CAMERA |
| Sign on the left | Flip every `RIGHT` in FIRST FRAME and ACTION TIMING |
