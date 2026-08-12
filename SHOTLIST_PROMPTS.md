# MR. CHAMELEON — SHOTLIST & VIDEO PROMPTS

**13 generations · 3:42 total · 16:9 · Seedance 2.5 (Higgsfield), 20s max per generation**

One generation per script block. Beats live inside `ACTION TIMING`, by the second. Where a block genuinely changes camera position, it is written as a controlled multi-shot with an explicit `HARD CUT` — still one generation.

## HOW TO USE

1. Paste the `ENVIRONMENT LOCK` block from `STYLE_PREFIX.md` directly under `SCENE CONTEXT` in **every generation except 10 and 11** (the basement has no daylight and carries its own light logic).
2. Paste the `STYLE PREFIX` block from `STYLE_PREFIX.md` **word for word** into the `STYLE` slot, then the closing technical line with the duration filled in.
3. Duration and aspect ratio are UI settings, not prompt text.
4. `GEO-BASEMENT` is pasted into generations 10 and 11 **unchanged**. It exists only because those two share one room, one mirror and one axis. Nothing else in this film needs a map.
5. Nothing generates until every tag in `ASSET_REGISTRY.md` is `LOCKED`.
6. One line changed per iteration. Everything into the log at the bottom.
7. **No generated audio is used in this film.** The `AUDIO` blocks below exist to shape the performance and to stop the model inventing speech — the finished soundtrack is built separately in post. Cut every clip on picture alone.

## RUNNING ORDER

# ⏱ TOTAL RUNTIME — 3:42 (222 seconds), + 2s held black = 3:44 delivered

| # | Block | Length | In | Out | Narration |
|---|---|---|---|---|---|
| 01 | Forest | 16s | 0:00 | 0:16 | VO-01 |
| 02 | Arrival | 8s | 0:16 | 0:24 | VO-02 |
| 03 | City square | 20s | 0:24 | 0:44 | — |
| 04A | City panorama — aerial | 20s | 0:44 | 1:04 | VO-03 |
| 04B | City interiors | 20s | 1:04 | 1:24 | — |
| 05A | Park — wheel & bumper cars | 20s | 1:24 | 1:44 | VO-04 |
| 05B | Park — swings & wide | 12s | 1:44 | 1:56 | — |
| 06 | Home entry | 20s | 1:56 | 2:16 | VO-05 |
| 07 | Inside — room / hall | 16s | 2:16 | 2:32 | VO-06, VO-07 |
| 08 | Kitchen | 14s | 2:32 | 2:46 | VO-08 |
| 09 · 10 · 11 | **The ending**, crosscut from three generations | 56s | 2:46 | 3:42 | VO-09 … VO-13 |
| | **TOTAL** | **222s** | | **3:42** | 13 cues |

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

# 01 · FOREST · 16s · 0:00

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. No body, no hands, no arms, no feet, no shadow of
the viewer at any point. A person walks a forest path inside an abandoned zone, looks up at the sky, and
comes out of the trees onto open ground where a distant built shape stands on the horizon. One continuous
16-second take, no cuts.


[paste ENVIRONMENT LOCK]
ACTIVE REFERENCES
@loc_MC_forest for location reference — take only the space and the texture: dense pine and birch trunks,
low undergrowth, deep leaf litter, thin daylight through the canopy. Do not use as a starting frame, do
not inherit the composition, the angle or the grade.
@loc_MC_pripyat_sign for location reference — take only the shape and the material of the distant
structure on the horizon: a low horizontal concrete slab standing alone on open ground. Do not use as a
starting frame, do not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
First frame is already mid-stride on the path: trunks passing close on both sides, the overgrown route
running away from camera toward a break in the trees dead ahead. No empty establishing beat.

FORMAT MODE
Single continuous take, real time, no cuts, no speed ramps.

OPTICS
47° diagonal field of view, standard normal lens character, natural human-eye perspective. Deep enough
focus to hold both the near trunks and the distant horizon. No distortion.

CAMERA
The camera is a walking body, not a rig: vertical rise and fall on each stride, small lateral sway,
organic imperfect correction after every step. It never stabilises into a glide. Exactly two deliberate
moves in the whole take — one look up, one look back down. Eye height throughout.

ACTION TIMING
0.0–5.0s — walking forward at a steady confident pace; trunks enter close on the left and pass out; the
break in the trees ahead widens and brightens.
5.0–8.0s — the gaze lifts to the sky: broken cloud with one gap of direct sun, thin branches crossing it.
The walk continues underneath the tilt without breaking rhythm. The tilt eases in and settles.
8.0–9.0s — the gaze comes back down to the route, slower than it left.
9.0–13.0s — the last trunks fall away left and right; the sky opens across the top of frame; the ground
underfoot changes from leaf litter to dry grass and broken asphalt.
13.0–16.0s — open ground. Far off in the haze, low and horizontal at frame-CENTRE, a pale built shape
that is clearly not vegetation. The head drifts a few degrees to hold it centred. It stays too distant
to read.

PHYSICS
Weight transfer on every step: heel contact, mass settling, toe push-off. The footfall sound and the
body's vertical bounce change when the ground changes from soft litter to hard asphalt. Branches move on
contact and rebound. Cloud moves at cloud speed, branches on a separate faster frequency. Wind is
stronger in the open than under the canopy and moves the grass in travelling waves.

LIGHTING
Flat overcast above the canopy. Forest floor low key; the break in the trees two stops brighter. On the
upward look the frame exposes for the sky and the branches fall to near silhouette. Atmospheric haze
thickens with distance over the open ground.

AUDIO
Diegetic only — footfall on leaf litter then on grass and asphalt, breath at walking effort, wind through
pine, distant crows, insects. No music. No narration. No voices.

STYLE
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, bark and lichen at material level, clean cloud gradation, no jitter, no flicker.

POSITIVE CONSTRAINTS
Zero people visible anywhere. No hands, no arms, no feet, no body part and no cast shadow of the viewer
enters frame at any time. The walk never stops — the body keeps moving through the upward look. Exactly
ONE break in the cloud; no clear blue sky, no aircraft, no contrails. The distant structure stays
unreadable — no legible lettering at any point. Exactly ONE structure on the horizon, standing alone; no
other buildings, no towers, no vehicles. Photoreal. NON-IP. 16:9. 16s. SFX only. NO CGI. Cinematic.
```

---

# 02 · ARRIVAL · 8s · 0:16

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. A person walks the last stretch toward the concrete
city sign standing alone on open ground, stops in front of it, and looks it over. One continuous 8-second
take, no cuts.


[paste ENVIRONMENT LOCK]
ACTIVE REFERENCES
@loc_MC_pripyat_sign for location reference — take only the space and the texture: a freestanding
Soviet-era concrete city sign, raised relief lettering and a date, weathered white surface, lichen crust
in the letterforms, rust bleed at the fixings, grass and saplings at its base. Do not use as a starting
frame, do not inherit the composition, the angle or the grade.

FIRST FRAME AND SPATIAL BLOCKING
First frame already has the sign at readable size in the middle third of frame, its base cut by grass,
open ground running to it. No empty establishing beat.

FORMAT MODE
Single continuous take, real time, no cuts.

OPTICS
47° diagonal field of view, standard normal lens character. Focus rides forward with the walk and holds
the sign face sharp; the horizon behind falls slightly soft.

CAMERA
A walking body approaching a fixed object, then a standing body. The object grows in frame from the walk
alone — no zoom, no push. After the stop, breath-driven micro-motion and one slow lateral drift as the
gaze travels the sign, then a full settle.

ACTION TIMING
0.0–2.5s — the sign grows in frame; relief lettering separates from the flat of the slab.
2.5–4.0s — surface detail arrives: lichen in the letter troughs, rust runs, spalled concrete at the lower
edge. The stride shortens; the last step is a half step; the body settles forward and back once and stops.
4.0–6.5s — standing. The gaze travels slowly along the lettering to one end and stops there.
6.5–8.0s — the frame comes back a few degrees to centre and stops completely. Nothing moves but the grass
and one slow blink event.

PHYSICS
The deceleration is a real body decelerating — shorter final stride, reduced vertical bounce, mass
settling once. Grass and saplings at the base move continuously on wind; the slab does not.

LIGHTING
Flat overcast, no hard shadow anywhere. The relief throws only soft wide shadow. The white slab holds the
top of the exposure without clipping; the ground sits a stop and a half under it.

AUDIO
Diegetic only — footfall on grass and grit, breath slowing to rest, wind across open ground, grass
movement, distant birds, complete absence of any machine sound. No music. No narration. No voices.

STYLE
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, concrete pore and lichen at material level, crisp relief edges, no jitter, no flicker.

POSITIVE CONSTRAINTS
Zero people visible. No body part and no cast shadow of the viewer in frame at any time. Exactly ONE sign,
standing alone, never duplicated. No vehicles, no fences, no power lines, no modern signage, no graffiti,
no tourist markers, no flowers or wreaths at its base. The last two seconds are held stillness — the frame
does not drift, push or reframe. Photoreal. NON-IP. 16:9. 8s. SFX only. NO CGI. Cinematic.
```

---

# 03 · CITY SQUARE · 20s · 0:24

```
SCENE CONTEXT
EXACT 1 CHARACTER — NO DUPLICATES: MR CHAMELEON. He walks into the abandoned city and crosses the central
square along the front of the ruined Palace of Culture, turning his head to read the building as he
passes. The last four seconds cut to an outside view of him crossing the same square. His face is not
visible at any point. Controlled multi-shot sequence with ONE HARD CUT at 16.0 seconds. Real time.


[paste ENVIRONMENT LOCK]
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
SHOT A — a walking body: stride rise and fall, lateral sway, organic correction. Exactly ONE deliberate
move: a head turn to frame-RIGHT onto the building and back. No push, no zoom, no whip.
SHOT B — locked off on a long lens on sticks with the faintest operator drift. It does not track him; he
walks through the frame.

ACTION TIMING
0.0–5.0s — first person, walking the approach road; saplings pass close; the façades come clear above the
tree screen and grow from the walk alone.
5.0–10.0s — the road opens into the square; the colonnade of the Palace of Culture arrives along
frame-RIGHT and begins passing.
10.0–15.0s — the head turns to frame-RIGHT onto the ruin — the eyeline arrives before the framing does —
and holds there while the body keeps walking the same line, so the frame slides sideways past the
colonnade. The walking rhythm never breaks under the turn. At 15.0s the head starts back toward the
direction of travel.
16.0s — HARD CUT.
16.0–20.0s — outside view: he walks from the left third toward frame-CENTRE and on toward the right third,
stride even and unhurried, no glances around. The frame holds and does not follow him.

PHYSICS
Footfall changes from asphalt to broken paving and grit. Saplings bend on contact and rebound. In SHOT A
the vertical walking bounce continues at the same tempo throughout the head turn. In SHOT B real ground
contact, opposing arm swing and weight transfer are visible even at distance; his clothing moves a beat
behind him on the wind; the foreground sapling moves on its own faster frequency in front of the lens.

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
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, concrete, moss and asphalt at material level, clean shade detail in the colonnade, the figure
razor-sharp against a dissolved background in SHOT B, no jitter, no flicker.

POSITIVE CONSTRAINTS
Exactly ONE person in the entire sequence and no one else anywhere in the city. He wears the half-mask
throughout and it never comes off. In SHOT B he is seen in three-quarter profile from behind — the mask
reads clearly at the edge of the jaw, but he never turns toward the lens and his eyes are never legible at
this distance. He walks continuously and never stops. The camera stays on the open-square side
of his walking line and never crosses to the building side. Exactly ONE colonnaded building, never
duplicated. Exactly ONE hard cut, at 16.0 seconds. No working vehicles, no lit windows, no intact glazing,
no modern signage. Photoreal. NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic.
```

---

# 04A · CITY PANORAMA — AERIAL · 20s · 0:44

```
SCENE CONTEXT
EXACT 0 CHARACTERS — the city itself is the subject. One slow, unbroken aerial pan across an abandoned
city from fifty metres up. Nothing else happens. One continuous 20-second take, no cuts.


[paste ENVIRONMENT LOCK]
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
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, concrete, canopy, wood and plaster at material level, no jitter, no flicker, no stutter in the
pan, no crawling on building edges.

POSITIVE CONSTRAINTS
Zero people anywhere. Zero moving vehicles, zero lit windows, zero smoke, zero aircraft, zero contrails.
Every building is derelict with empty window openings; forest grows through every street and courtyard.
The pan runs at one constant rate from the first frame to the last and never stops, never reverses, never
changes height. Photoreal. NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic.
```

---

# 04B · CITY INTERIORS · 20s · 1:04

```
SCENE CONTEXT
EXACT 0 CHARACTERS — three real interiors of the abandoned city, each held still. A school gymnasium, a
classroom, a shop. Controlled multi-shot sequence with TWO HARD CUTS. Real time.


[paste ENVIRONMENT LOCK]
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
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, parquet, plaster crust, paper, painted steel and tile at material level, no jitter, no flicker.

POSITIVE CONSTRAINTS
Zero people, zero animals in any shot. No legible text on the blackboard, on any sign, on any shelf label
or on any paper. No dolls, no toys, no gas masks, no personal items and no photographs staged anywhere in
frame — nothing is arranged and nothing is freshly disturbed. Every window opening is empty of glass. No
lit fixtures, no power anywhere. Exactly TWO hard cuts, at 7.0 and 14.0 seconds. Photoreal. NON-IP. 16:9.
20s. SFX only. NO CGI. Cinematic.
```

---

# 05A · PARK — WHEEL & BUMPER CARS · 20s · 1:24

```
SCENE CONTEXT
EXACT 0 CHARACTERS — the two most recognisable rides of the abandoned amusement park, each held long and
still: the Ferris wheel, then the bumper-car pavilion. Nothing works, nothing turns, nobody is there.
Controlled multi-shot sequence with ONE HARD CUT at 10.0 seconds. Real time.


[paste ENVIRONMENT LOCK]
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
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, oxidised steel, flaking paint and moss at material level, clean sky gradation with no banding,
no jitter, no flicker, no crawling on thin steelwork against the sky.

POSITIVE CONSTRAINTS
Zero people, zero animals in either shot. The Ferris wheel NEVER rotates — exactly ONE cabin moves, and
only a few degrees. No bumper car moves at any point, ever. No power anywhere: no lit bulbs, no sparks at
the contact grid, no music box, no machinery sound. Nothing is arranged and nothing is freshly disturbed.
Exactly ONE hard cut, at 10.0 seconds. Photoreal. NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic.
```

---

# 05B · PARK — SWINGS & WIDE · 12s · 1:44

```
SCENE CONTEXT
EXACT 0 CHARACTERS — the swing boats and carousel, then the whole park in one frame with the forest
closing in on it. Controlled multi-shot sequence with ONE HARD CUT at 6.0 seconds. Real time.


[paste ENVIRONMENT LOCK]
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
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, rusted steel, flaking paint and torn fabric at material level, clean sky gradation with no
banding, no jitter, no flicker, no crawling on thin steelwork against the sky.

POSITIVE CONSTRAINTS
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


[paste ENVIRONMENT LOCK]
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
6.0–9.0s — he crosses the entrance hall past the mailboxes and starts the first flight; the camera follows
into the stairwell.
9.0–13.0s — first flight and the half-landing turn: his hand never takes the handrail, his pace is even,
plaster grit crunching under each step; he rounds the turn without slowing and the camera takes it a beat
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
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, concrete, render, plaster, rusted steel, torn door padding and wallpaper at material level,
clean detail in the dark bands and the doorway void, no jitter beyond the intended handheld, no flicker.

POSITIVE CONSTRAINTS
Exactly ONE person in the entire sequence and no one else anywhere in the building. He wears the half-mask
throughout and it never comes off. Head down and turned away in the first shot, seen from directly behind
for the whole second shot; he never looks back and never turns at the landing.
He opens the door by shoulder alone — he never touches a handle and never uses a key. Exactly ONE building,
exactly ONE door opening. Exactly ONE hard cut, at 6.0 seconds. Photoreal. NON-IP. 16:9. 20s. SFX only.
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


[paste ENVIRONMENT LOCK]
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
0.0–3.0s — two steps into the bedroom; the bed frame grows in frame; dust lifts where the feet land and
hangs in the window light.
3.0–6.0s — the body stops. The gaze turns slowly to the desk at frame-RIGHT and holds on it.
6.0–8.0s — the gaze comes back toward the window, slower than it left, and settles. One slow blink event.
8.0s — HARD CUT.
8.0–11.5s — three steps into the living room; the tree branch and the torn window opening grow in frame.
11.5–14.0s — the body stops. The gaze crosses slowly from the cabinet at frame-LEFT to the tree at
frame-RIGHT.
14.0–16.0s — held on the tree. The branch moves on the outside wind, inside the room. One slow blink event.

PHYSICS
Floorboards flex and sound under each step. Dust lifts on footfall and hangs, then drifts on the room's own
slow air. The branch is a real branch outdoors moving on real wind, and the part inside the room moves with
the same motion delayed by its length. Leaf litter lifts at its edges on the draught through the opening.
Wallpaper sheets move only at their loose edges. Nothing in either room is disturbed by the walk.

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
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, veneer, rusted iron, rotted fabric, glazed cabinet, carpet fibre, bark and leaf at material
level, clean detail in the dark corners, no jitter, no flicker.

POSITIVE CONSTRAINTS
Zero people visible in either shot. No hands, no arms, no feet, no body part and no cast shadow of the
viewer enters frame at any time. NO MIRROR in either room, and THE GLAZED CABINET NEVER RETURNS A FACE —
it reflects only the window and the room. No photographs, no portraits, no dolls, no toys, no legible text
anywhere in frame. Exactly ONE tree branch through exactly ONE window opening. Nothing is touched or moved.
Exactly ONE hard cut, at 8.0 seconds. Photoreal. NON-IP. 16:9. 16s. SFX only. NO CGI. Cinematic.
```

---

# 08 · KITCHEN · 14s · 2:32

```
SCENE CONTEXT
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. No body, no hands, no arms, no feet, no shadow of
the viewer at any point. A person walks into the kitchen of the flat. Everything is in place and everything
is long dead. One continuous 14-second take, no cuts.


[paste ENVIRONMENT LOCK]
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
0.0–3.0s — two steps in; the fridge and the table both come fully into frame; dust lifts where the feet
land.
3.0–7.0s — the body stops. The gaze travels slowly left to right across the fridge, the mould wall and the
shelves.
7.0–11.0s — the gaze settles on the table and the objects still standing on it.
11.0–14.0s — held. Dust in the window light and nothing else. One slow blink event.

PHYSICS
Floorboards and grit under each step. Dust lifts on footfall and hangs. The curled oilcloth moves only at
its lifted corner on the draught. Nothing on the shelves moves. Nothing is touched.

LIGHTING
Overcast daylight from the window behind the table — the table edge and the objects on it are rim-lit
against it, the fridge corner sits two and a half stops under, the mould wall is the darkest value in
frame. No fill from the camera side.

AUDIO
Diegetic only — footfall on grit, breath, a slow irregular drip somewhere out of frame, wind at the window
opening, a small hard-surfaced room tone. No music. No narration. No voices.

STYLE
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, chipped enamel, rust bleed, mould bloom and curled oilcloth at material level, clean detail in
the dark corner, no jitter, no flicker.

POSITIVE CONSTRAINTS
Zero people visible. No hands, no arms, no feet, no body part and no cast shadow of the viewer enters frame
at any time. No mirror and no reflective surface that could return a face — the window glazing is gone, not
intact. No legible text or branding on any object or packaging. Exactly ONE fridge, never duplicated.
Nothing in the kitchen is touched or moved. Photoreal. NON-IP. 16:9. 14s. SFX only. NO CGI. Cinematic.
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


[paste ENVIRONMENT LOCK]
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
[paste STYLE PREFIX verbatim]

QUALITY
8K detail, pore-level skin around the eyes, brow and temple, individual lashes, iris fibre structure at
the closest framing, woven mask fabric texture, wet living eyes with catch-lights, no jitter, no flicker,
no identity drift between the first and last frame.

POSITIVE CONSTRAINTS
Exactly ONE person in the entire sequence and no one else anywhere. In SHOT A he is turned away and never faces camera. In SHOT B he faces camera and holds the lens for the whole shot — he never
looks away, never turns his head, never steps back, and his expression stays neutral throughout with no
smile and no widening of the eyes. THE MASK NEVER COMES OFF and never slips — everything below the eyes stays
covered for the entire shot, and the eyes and brow match the reference exactly at every distance in the
move. The green stays INSIDE the pupils only: no glow on the skin, no light cast on the face, no light in the air, no
lens flare, no particles, no rays. Both eyes change identically and at the same rate. The catch-light stays
in both eyes throughout. Exactly ONE confinement structure on the horizon, never duplicated. No vehicles,
no aircraft, no lit windows, no smoke. Exactly ONE hard cut, at 3.0 seconds. Photoreal. NON-IP. 16:9. 20s.
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

[paste GEO-BASEMENT]

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
[paste STYLE PREFIX verbatim]

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

[paste GEO-BASEMENT]

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
scream contains no language. (The scream is written here so the body performs it — throat, tendons, chest,
shoulders. The generated audio itself is discarded and replaced in post.)

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
[paste STYLE PREFIX verbatim]

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

| # | Piece | Source | Len | Film time | What the audience gets | VO |
|---|---|---|---|---|---|---|
| 1 | `WIDE` | 09 | 3s | 2:46 | Him tiny, the reactor stacked behind him | — |
| 2 | `A1` | 09 | 5s | 2:49 | The approach starts | VO-09 @ 2:50 |
| 3 | `B1` | 10 | 7s | 2:54 | Cut away. A basement. She works, never looks up | VO-10 @ 2:55 |
| 4 | `A2` | 09 | 4s | 3:01 | Back to him — closer than we left him | — |
| 5 | `B2` | 10 | 9s | 3:05 | The marks surface on her skin | VO-11 @ 3:07 |
| 6 | `A3` | 09 | 8s | 3:14 | Back to him, closest — eyes above the mask, held, and the pupils go green | — |
| 7 | `B3` | 11 | 13s | 3:22 | Push to the mirror. The copy walks in. Nobody reacts | VO-12 @ 3:24 |
| 8 | `B4` | 11 | 7s | 3:35 | She lifts her head. The scream. **CUT TO BLACK** | VO-13 @ 3:36 |

**Runs out at 3:42.** Two seconds of held black, then the end card.

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

| Pass | Generations | Why |
|---|---|---|
| **1** | 11, 09 | Two identical faces in one frame, and the push to his eyes. The hardest things in the film — prove them first, while there is budget to solve them. |
| **2** | 10, 06, 03 | The characters and the basement. Second-hardest. |
| **3** | 01, 02, 07, 08 | POV walking and interiors. |
| **4** | 04A, 04B, 05A, 05B | Held frames where almost nothing moves. Cheapest, lowest risk, generate last. |

This is the order to **generate** in, not the order of the film. The film runs 01 → 11.

# ITERATION LOG

| Gen | v | What changed from previous | Verdict |
|---|---|---|---|
| | | | |
