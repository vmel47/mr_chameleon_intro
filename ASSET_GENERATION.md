# MR. CHAMELEON — ASSET GENERATION · PRESERVED PROMPT CANDIDATES

> **FULL RESET:** all prompts in this file are old candidates, not active approvals. Every character,
> location, prop, starting frame and reference asset must be generated again and tracked in
> `GENERATION_DATABASE.md`.

Prompts for building every asset in the film. **Nothing in `SHOTLIST_PROMPTS.md` gets generated until everything here is `LOCKED`.**

## MODEL ROUTING

| Asset | Model | Notes |
|---|---|---|
| Character sheets | **Soul 2.0**, aspect 16:9, quality 2k | Soul ID on. **No reference images anywhere in this project** — every identity is carried by its descriptor. |
| Location sheets | **Soul Cinema**, aspect 16:9, quality 2k | 3/4 angle, never frontal |
| Prop sheet (the signs) | **Nano Banana Pro**, 1:1 or 4:3, 2k–4k | |
| Wardrobe / mask variants | **Nano Banana Pro** point change, then masked back onto the original by hand | Never re-run a full sheet through a model twice |

## THE RULES THAT BREAK THINGS IF IGNORED

1. **Follow one template, not two.** The character prompts below are the Lira 3-panel template as written — three panels, all with heads, a palette line and a tech block at the end. Mixing it with techniques from other pipelines is what produced the malformed first attempt.
2. **The tech block is not optional.** Without a camera and lens named at the end, the model has no photographic anchor and drifts to illustration. Use the *clean digital* register — no film grain, no heavy desaturation — so the sheet stays neutral and does not carry a look into every scene.
3. **The sheet stays neutral.** Grey backdrop, one soft directional light, real pores, no retouch, no grade. The cinema look lives in the locations and the video prompts. Bake it into the sheet and the character carries it everywhere and stops reacting to new light.
4. **An image never runs through a model twice in full.** Mask, wardrobe, marks — point changes only, composited back onto the original by hand. Two full passes and the face turns plastic and symmetrical, and dead texture kills the acting in video later.
5. **Never write** `character reference sheet` or `painterly` — both trigger illustration. Say `film character sheet` and `studio photographs`. **Never write** `rule of thirds` on a sheet.

---

# 1 · CHARACTERS

> **Fast path, try this first.** **Cinema Studio AI Cast** builds a character reference sheet automatically
> — it is a standalone tool on Higgsfield, all parameters set in its own UI, no prompt needed. If it gives
> a usable sheet, take it and skip the prompts below. The prompts are for when you need full control.

**Built on the Lira character-sheet template exactly.** Earlier drafts of this file merged that template
with a different one and produced garbage — specifically a headless front figure, which the Lira template
does not use, and a missing tech block, without which the model has no idea it is meant to be shooting a
photograph. Both are fixed below.

**Platform parameters:** Soul 2.0 · aspect 16:9 · quality 2k · Soul ID on. Aspect and quality go in the UI,
never in the prompt text.

---

## 1.0 · AI CAST INPUT

**Keep it short.** The first attempt at this file ran ~350 words of anatomy and produced a monster: giant
flesh flaps where the ears should be, a bodybuilder physique, and no clothing at all. Lira's own rule is
`a tight 80–150-word prompt beats a scattered 400-word one`, and this is why.

```
A tall, solidly built man — broad shoulders, an even natural frame, ordinary proportions,
clearly strong but not a bodybuilder. 185 cm, 88 kg.

Dark brown hair cut short — trimmed close at the sides and back, never touching the collar.
No long hair. A high forehead. Thick
straight dark eyebrows set low and almost level. Deep-set dark brown eyes with heavy upper
lids. A straight nose. Full lips, mouth closed. Wide cheekbones, a square jaw. Pale skin with
visible pores and light stubble. No glasses. A calm, neutral, unsmiling face.

He wears a thin faded khaki cotton-canvas jacket, sun-bleached almost to grey, worn open,
one pocket torn and hand-stitched back on; a dark grey long-sleeved shirt underneath with
the sleeves pushed up the forearm; heavy canvas trousers, dirty at the knee, tucked into
short black rubber boots; a flat canvas bag on a worn leather strap across the chest.
Everything faded to a different shade, nothing matches, nothing is new, no logos.
```

### WARDROBE LAW — one summer outfit, worn for the whole film

The action is a **hot early-summer afternoon**. Nothing quilted, nothing lined, nothing heavy.

The look is a man who walks long distances through an abandoned zone and does not want to be noticed —
**not** an outdoor catalogue and **not** a soldier. It comes from three things:

1. **Natural fabrics only** — cotton canvas, cotton shirting, leather strap, rubber boots. The first
   version said `softshell`, `technical fabric` and `low-profile pack`, and that single word `softshell`
   is what made the result look like modern European outdoor gear.
2. **Nothing matches.** Jacket one shade, shirt another, trousers a third. A matching olive set reads as
   a uniform or a product shot, which is exactly what came out the first time.
3. **Rubber boots, not boots.** Short black rubber boots are the zone detail — wet grass, contamination —
   and they are the single strongest signal against a tactical read.

### What broke the long version — do not put these back

| Wording | What it produced |
|---|---|
| `long straight sideburns running down past the ear` | The model read it as ear geometry and grew a flesh flange off the side of the head |
| `heavy trapezius`, `deep chest`, `thick forearms with visible tendon and vein` | Named muscle groups render literally, as an anatomy plate — bodybuilder, not a person |
| `slightly tired`, shadows under the lids, two separate facial creases | Aging cues stack. Each one reads small; four together add fifteen years |
| A 350-word block | Past roughly 150 words every extra clause dilutes attention and whole sections drop out — the wardrobe was the first thing to go |

**General principle:** describe a person the way a casting note would, not the way an anatomy textbook
would. Simple shapes and plain words. The model already knows what a man looks like.

**No mask at this stage** — the sheet is built on the full face so the identity locks, and the mask goes on
afterwards as a point change (1.2).

**Do not paste into AI Cast:** the three-panel description, the grey backdrop, the studio lighting line,
the ARRI tech block, the palette, or any aspect ratio. AI Cast handles all of it in its own UI.

**If AI Cast strips the clothing again**, it is a body-base tool and will not dress a character. Go to the
manual Soul 2.0 route in 1.1, where the wardrobe is part of the sheet prompt itself.

---

## 1.1 `@char_MC_mr_chameleon_face` — identity master, dressed, no mask (manual Soul 2.0 route)

**Generate this first.** It never appears in the film — the mask is on him in every shot. It exists so the
Soul ID locks onto a complete face, and so his eyes and brow stay identical everywhere the mask covers the
rest.

```
Three studio photographs of the same man arranged side by side on a flat neutral mid-grey studio
backdrop, a film character sheet: full-body front photo on the left, full-body back photo in the middle,
close-up portrait photo on the right, the same real person in all three, consistent across panels. Soft
directional cinematic studio lighting from one side, gentle natural shadow falloff, clean neutral
cinematic look.

The man: tall and solidly built — broad shoulders, an even natural frame, ordinary proportions,
clearly strong but not a bodybuilder. 185 cm, 88 kg.

Dark brown hair cut short — trimmed close at the sides and back, never touching the collar.
No long hair. A high forehead. Thick
straight dark eyebrows set low and almost level. Deep-set dark brown eyes with heavy upper
lids. A straight nose. Full lips, mouth closed. Wide cheekbones, a square jaw. Pale skin with
visible pores and light stubble. No glasses. A calm, neutral, unsmiling face.

Wardrobe, strictly identical in all panels: a buttoned dark olive-green canvas field jacket with a neat collar; a dark charcoal crewneck shirt underneath; matching dark olive tactical cargo trousers tucked into dark brown leather hiking boots; a dark brown leather strap across the chest holding a compact canvas messenger bag. Clean, practical, unified outdoor outfit with no logos, no torn fabric, no mismatched shades.

On the left panel the man stands straight facing the camera in a neutral pose, arms relaxed at the sides,
full figure head to feet. In the middle panel the same standing pose is seen from behind, full figure
head to feet. On the right panel a close-up head-and-shoulders portrait, calm neutral expression, mouth
closed, eyes to camera with a clear catch-light in each pupil, the skin real and unretouched.

Muted palette of 60 percent dark olive green, 30 percent neutral mid-grey backdrop, 10 percent dark leather and charcoal. Clean neutral studio photographic capture with a standard spherical normal-lens character,
crisp natural detail, minimal fine grain, soft optical falloff, hyperrealistic photographic
detail, natural living skin tones, medium contrast, true-to-life modern colour, no heavy desaturation.
```

**What changed and why, so it does not get re-broken:**

| Was | Now | Reason |
|---|---|---|
| Front figure cropped headless | Full figure head to feet, all three panels | The headless trick belongs to a different template. Here it produces malformed bodies. |
| No tech block | Clean neutral studio photograph, normal spherical lens character | The model receives a visible photographic anchor without tying identity assets to a prestige camera brand. The clean register deliberately carries no scene grade. |
| No palette line | 60/30/10 | Lira's template requires one. |
| 350 words of anatomy | ~110 words, plain casting-note language | Named muscle groups render as an anatomy plate; ear and sideburn geometry grew flesh flaps; stacked aging cues added fifteen years; and past ~150 words the wardrobe simply dropped out. |

**Do not add** the words `character reference sheet` or `painterly` — both trigger illustration. **Do not add** `rule of thirds` — sheets are exempt. **Check the catch-lights** before accepting: dark eyes with no reflection in the pupil read dead, and no video model can act with a dead face.

**If wide shots later pull a blurry face** from the small full-body figure instead of the portrait, regenerate the sheet with the front figure cropped above the shoulders. Use that as a fix for an observed problem, not as a default.

---

## 1.2 `@char_MC_mr_chameleon` — the film version, masked

Point change on the locked master. **Nano Banana Pro**, then composite back by hand.

```
Edit the image: add a face mask to the man in all three panels.

CHANGE: Add a dark charcoal technical half-mask covering the nose, mouth, chin and jaw, its top edge
sitting just under the lower eyelids. Matte woven fabric, a soft moulded shape over the nose bridge,
an elastic strap running back behind the ear, worn and lightly dusted. Not a medical mask, not a
respirator — no valves, no filters, no cartridges, no branding. In the back panel only the strap and
the edge of the mask are visible past the jaw.

PRESERVE EXACTLY:
- The eyes, brow, forehead, hairline, hair, ears and the skin around the eyes — pixel for pixel
- The eye colour, the hooded lids, the furrow between the brows, the catch-lights
- Head angle and gaze direction in every panel
- All clothing, every fold, the pack, the boots, the gloves
- Body proportions, stance and the position of every limb in all three panels
- Neutral grey backdrop, the lighting, all existing shadows
- Colour grade, palette, contrast, grain, falloff

ONLY CHANGE: the addition of the half-mask. 100% identical otherwise.
```

**Then composite by hand.** Open the master and the edit side by side in any editor with masks and paint
only the mask region of the edit onto the master. The skin around the eyes must be the master's original
pixels. This is the pass that keeps the face alive — a full second pass through a model turns skin plastic
and symmetrical, and dead texture ruins the acting in video later.

**Wardrobe logic.** He is not protecting himself from the zone; he lives in it and it does not frighten
him. The clothing is about not being noticed — muted, unbranded, unmilitary, the colour of wet concrete
and birch. A man who has walked a long way and is walking home. The mask reads as habit, not as safety
equipment.

---

## 1.3 `@char_MC_employee` — the lab worker

**Soul 2.0 · 16:9 · 2k · Soul ID: create**

```
Three studio photographs of the same woman arranged side by side on a flat neutral mid-grey studio
backdrop, a film character sheet: full-body front photo on the left, full-body back photo in the middle,
close-up portrait photo on the right, the same real person in all three, consistent across panels. Soft
directional cinematic studio lighting from one side, gentle natural shadow falloff, clean neutral
cinematic look.

The woman: ordinary build, medium height, entirely believable as someone who has worked the same job for
years. Mid-brown hair pulled back and pinned, a few strands loose at the temple. Plain face, no makeup,
tired around the eyes, slightly dry skin with visible pores and a faint natural flush across the
cheekbones. Grey-blue eyes. A closed, neutral, slightly absent expression — she is thinking about
something else.

Wardrobe, consistent in all panels: a plain white cotton medical coat, buttoned, gone slightly grey with
age; a plain light blue medical mask pulled down and sitting loose under her chin so the whole face is
open; plain dark trousers and flat closed shoes.

On the left panel the woman stands straight facing the camera in a neutral pose, arms relaxed at the
sides, full figure head to feet. In the middle panel the same standing pose is seen from behind, full
figure head to feet. On the right panel a close-up head-and-shoulders portrait, mouth closed, eyes to
camera with a clear catch-light in each pupil, the mask visible loose under the chin, the skin real and
unretouched.

Muted palette of 60 percent off-white cotton, 30 percent neutral mid-grey backdrop, 10 percent pale
medical blue. Clean neutral studio photographic capture with a standard spherical normal-lens character,
crisp natural detail, minimal fine grain, soft optical falloff, hyperrealistic photographic
detail, natural living skin tones, medium contrast, true-to-life modern colour, no heavy desaturation.
```

---

## 1.4 `@char_MC_employee_civil` — the copy in the mirror

Point change on the locked `@char_MC_employee` sheet, so the face is guaranteed identical.

```
Edit the image: change only the clothing, in all three panels.

CHANGE: Replace the white medical coat and the medical mask with ordinary everyday civilian clothes —
a plain dark knit sweater over a collared shirt, and plain dark trousers. No coat and no mask anywhere
in frame, nothing medical, nothing institutional.

PRESERVE EXACTLY:
- The face, pixel for pixel — every feature, the skin texture, the catch-lights
- The hair, exactly as pinned, including the loose strands
- Head angle, gaze direction and expression in every panel
- Body proportions, stance and the position of every limb in all three panels
- Neutral grey backdrop, the lighting, all existing shadows
- Colour grade, palette, contrast, grain, falloff

ONLY CHANGE: the clothing. 100% identical otherwise.
```

> **Why a separate tag.** In generation 11 both versions stand in the same mirror at the same time. Written
> as one tag with "in ordinary clothes" attached, the model mixes the states between takes — two coats, or
> two sweaters, or the coat on the wrong one. Two tags, one face, one wardrobe each.

---

## 1.5 `@char_MC_employee_signs` — the marked state

The marks arrive **during** generation 10, so they cannot be baked into the base sheet. This asset is the
**target end state** — what she must look like at 16.0s — so the video prompt has something exact to aim at
instead of the model inventing a pattern per take.

Built as a **point change on the locked `@char_MC_employee` sheet**.

```
Edit the image: add a fine geometric pattern beneath the skin of the exposed neck, hand and forearm.

CHANGE: Across the side and back of the neck, the back of the working hand and the forearm inside the
cuff, bring up a dense fine geometric pattern that sits BENEATH the surface of the skin — a tight
regular lattice of interlocking hexagons and fine parallel gratings, small in scale and high in
frequency, following the curve of the muscle and tendon underneath. It reads as a tonal shift of the
skin itself, like a watermark held up to the light. Low contrast. No colour of its own. No light of
its own.

PRESERVE EXACTLY:
- The face, pixel for pixel, and the skin of the face completely unmarked
- The hair, the coat, the mask under the chin, every fold of fabric
- Head angle, gaze direction and expression in every panel
- Body proportions, stance and the position of every limb
- The headless crop on the left panel
- Neutral grey backdrop, flat lighting, all existing shadows
- Colour grade, palette, contrast, grain, falloff

ONLY CHANGE: the pattern under the skin of the neck, hand and forearm. 100% identical otherwise.
```

**The pattern never reaches her face.** Neck, hand, forearm only — the face stays clean so the audience
reads a person, not a creature.

---

# 2 · THE PROP

## 2.1 `@prop_MC_signs` — the pattern reference

This is the **look library** for the marks: a texture and behaviour reference, not an object that appears
in frame. It is what `@char_MC_employee_signs` is built from, and what every video prompt describing the
marks is written against.

**Model:** Nano Banana Pro · 4:3 · 2k · this is a **texture and behaviour reference**, not an object

```
A photorealistic macro photograph of a section of adult human forearm and the side of a neck, lit by one
soft directional light, on a plain dark background. Across the skin runs a dense fine geometric pattern
that sits BENEATH the surface rather than on it — a tight regular lattice of interlocking hexagons and
fine parallel gratings, high frequency, small in scale, following the curve of the muscle and stretching
where the tendon lifts. The pattern is barely there: a tonal shift of the skin itself, like a watermark
held up to the light, visible only where the light rakes across. It has no colour of its own and gives
off no light.

The skin is real and unretouched — visible pores, fine vellus hair, a natural flush, the pattern reading
through all of it rather than over it.

Photorealistic macro photography, clean dry skin, natural skin tones, shallow depth of field, single
soft key light with smooth falloff, plain matte dark background.
```

**Behaviour rules — copy these into every video prompt that uses the marks:**

| The marks ARE | The marks are NOT |
|---|---|
| Structure under the skin, deforming with the body | An overlay, projection or screen effect |
| Geometric, tiled, high frequency, regular | Letters, numerals, glyphs, any alphabet, any script |
| Low contrast, tonal, almost a watermark | Glowing, emissive, coloured, green |
| Visible only at raking light angles | Lighting the room or casting shadow |
| On skin only | On clothing, walls, objects or in the air |

**Where the look comes from.** The geometric imagery reported under psychedelics — what researchers call *form constants*: lattices, gratings, honeycombs, spirals, webbing. People describe it as "like the code in The Matrix", and that comparison is the *feeling* to hit, not the design to copy. The moment it becomes readable characters the film turns into a superhero VFX reel.

---

# 3 · LOCATIONS

**Soul Cinema · 16:9 · 2k · every sheet shot in 3/4, never frontal.**

## THE RULE THAT FIXES ALL OF THESE

**Name the real place.** Pripyat is one of the most photographed locations on earth and the model knows it —
the panel-block layout, the Palace of Culture, the yellow Ferris wheel, the crests on the rooftops. An
early draft of this file said `an abandoned Soviet city` and got a generic Eastern European ruin. Saying
`Pripyat, Ukraine` gets Pripyat.

Real places are not IP. Name them. Name the street, the building, the ride.

**No reference images are needed for any location in this film.** Every one of these is either a real place
the model knows or a generic interior. A reference would actually hurt: almost every real photograph of the
zone is shot in autumn under flat grey, and it will drag its season and sky in and break the environment
lock. **The only case for attaching one** is if the concrete keeps coming out too clean after three or four
tries — then attach a photo and add this line, nothing else:

```
Take only the material and surface texture from the reference — precast concrete panel seams, spalled
render, rust streaking. Do not inherit the season, the sky, the foliage colour, the composition, the
angle or the grade.
```

## TWO CONSTANTS — paste both at the end of every location prompt below

```
[ENVIRONMENT LOCK — copy from STYLE_PREFIX.md]
```

```
[LOCATION TAIL]
Palette of 60 percent new-growth birch and grass green, 30 percent weathered concrete grey and pale sky,
10 percent rust-orange oxidised metal. Empty deserted place, no people anywhere, no vehicles, no lit
windows, no intact glazing, no modern signage. Vegetation growing through every hard surface. Cinematic
film still, natural film texture, no grain stacking.
```

The basement is the only exception — it gets the `[BASEMENT LIGHT]` block instead of the environment lock:

```
[BASEMENT LIGHT]
No daylight of any kind. One dim overhead fixture directly above the work table, everything else falling
away two stops into shade. Palette of 60 percent dead institutional green-grey, 30 percent deep shade,
10 percent the cold white of enamel and glass.
```

---

## 3.1 `@loc_MC_forest`

```
A three-quarter wide view along an overgrown path through the forest of the Chernobyl Exclusion Zone
outside Pripyat, Ukraine, camera at eye height looking diagonally down the route. Dense mixed pine and
silver birch, tall bare trunks, deep leaf litter, low undergrowth, the path barely readable under grass
and saplings. Ahead the trees thin toward a bright break in the treeline.
```

**Anchor:** the break in the trees ahead.

---

## 3.1B `@loc_MC_duga_fragment` — OPTIONAL

> Only needed if the Duga shot in `OPTIONAL_SHOTS.md` is used. Not part of the film's spine.

**A fragment, never the object.** This is the Duga over-the-horizon radar array outside Pripyat — but it is
only ever seen as a piece of itself, close, through trees. The full silhouette is the spoiler: anyone who
recognises that profile knows where the film is set, and the reveal at the city sign dies. Shown as a
fragment it reads as *something enormous and man-made, unexplained* — which builds the unease instead of
spending it.

```
A three-quarter view from an overgrown forest track, camera at chest height among the trees, looking
diagonally up and past a huge rusted steel lattice structure standing among the trunks. Only a fragment of
it is visible: one enormous latticed leg of riveted steel angle, wider than a tree, rising straight up and
out of the top of frame, with a section of fine steel mesh and cable strung between it and the next leg
further back. A square concrete anchor block sits in the grass at its foot, cracked and mossed over. Pine
and birch stand hard against it and in front of it on every side, occluding it in every direction.

The structure is far too large to fit the frame and its extent is never visible. No horizon, no clearing,
no wide view, no skyline. Rust has bled down the steel in long streaks; the paint is gone; young trees
have grown up through the lattice itself.

Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything overgrown, everything alive.
Sky: bright mostly sunny pale blue with a few small separated soft-white clouds and large blue gaps; never overcast.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft warm rim on edges, camera side a stop and a half under.
Shadows: softly defined and readable, all falling the same way.
Air: light haze thickening with distance, pollen drifting in bright gaps.
Time: 1:00 PM, early afternoon daylight.

Palette of 60 percent new-growth birch and grass green, 30 percent weathered steel grey and pale sky,
10 percent rust-orange oxidised metal. Empty deserted place, no people anywhere, still air. Cinematic film
still, natural film texture, no grain stacking.
```

**Anchor:** the single lattice leg and its concrete foot.

**The three bans that keep it a fragment** — without these the model draws the whole array every time:

```
Only a fragment of the structure is ever visible. The full silhouette is NEVER shown, the structure NEVER
reads as a recognisable shape, and its horizontal extent is NEVER visible. Trees occlude it on all sides
at all times. No wide view, no clearing, no skyline, no distant view of the whole.
```

---

## 3.2 `@loc_MC_pripyat_sign`

```
A three-quarter view from the roadside of the concrete city sign of Pripyat, Ukraine — the white
wedge-shaped monument on the approach road from Chernobyl, the word ПРИПЯТЬ in tall raised relief letters
across the top slab and the year 1970 on the lower panel. Camera at chest height, the sign angled across
frame. Weathered white concrete, lichen crust in the letter troughs, rust bleed at the fixings, grass and
birch saplings grown up around the base, flat empty ground and treeline behind it.
```

**Anchor:** the slab itself. **Note:** no flowers, no wreaths, no tourist markers, no modern signage.

---

## 3.3 `@loc_MC_pripyat_city`

```
An aerial three-quarter view over Pripyat, Ukraine — the abandoned city beside the Chernobyl nuclear power
plant, seen today. Camera fifty metres above the ground, looking diagonally down and across the rooftops.
Rows of sixteen-storey and five-storey precast concrete panel blocks, every window opening empty and black,
render spalled off in patches, rust streaks running from the balconies; the Soviet crests still mounted on
the roofs of the tall blocks; the Polissya Hotel and the Palace of Culture Energetik on the central square
in the middle distance. Mature birch and poplar forest has grown through every street and courtyard, canopy
reaching the third and fourth floors, so the streets read as green corridors instead of roads. On the flat
horizon three kilometres away, the vast pale steel arch of the New Safe Confinement over reactor four.
```

**Anchor:** the tallest block with the rooftop crest.

---

## 3.4 `@loc_MC_pripyat_entrance`

```
A three-quarter view along the approach road into Pripyat, Ukraine, camera at eye height in the middle of
the roadway looking diagonally down its length. Cracked asphalt split open by birch saplings growing
through it, the verges gone to tall grass and young trees, the first five-storey precast concrete panel
blocks of the city standing up behind a thick screen of poplar and birch ahead.
```

**Anchor:** the centre line of the road.

---

## 3.5 `@loc_MC_dk_energetic`

```
A high three-quarter wide view across the central square of Pripyat, Ukraine, camera above head height
looking diagonally down at the Palace of Culture Energetik — the long modernist civic building on the
square, its tall glazed façade empty of glass, the concrete relief panels spalled, the wide steps mossed
over. The Polissya Hotel stands further along the same square. The paving of the square is broken open by
birch saplings growing through it in every direction.
```

**Anchor:** the façade of the Palace of Culture.

---

## 3.6 `@loc_MC_park`

```
A three-quarter wide view of the abandoned amusement park in Pripyat, Ukraine — the fairground that never
opened. Camera at standing height, the rides angled across frame. The yellow-cabined Ferris wheel on its
oxide-streaked steel frame; the open-sided bumper-car pavilion with painted steel cars rusted in place on a
metal floor under the contact grid; the swing boats seized on their frames and the small paratrooper
carousel with its canopy partly collapsed. Birch and poplar grown up through the asphalt everywhere,
between and underneath all of it.
```

**Anchor:** the Ferris wheel.

---

## 3.7 `@loc_MC_home_area`

```
A three-quarter view from the courtyard of a residential block in Pripyat, Ukraine, camera low and looking
slightly up at the façade. A nine-storey precast concrete panel building, render spalled off in patches,
every window opening empty and black, balconies rusted and sagging, a dark entrance doorway at the base.
The courtyard asphalt is broken open by birch saplings and tall grass. Far off on the flat horizon, the
vast pale steel arch of the New Safe Confinement over reactor four.
```

**Anchor:** the entrance doorway. **Note:** the arch stays small and distant — it is a horizon element, never the subject.

---

## 3.8 `@loc_MC_home_stairs`

```
A three-quarter interior view up a stairwell in a Pripyat apartment block, camera at chest height on the
half-landing looking up the flight. Torn-open steel mailboxes in the entrance hall below, bare concrete
flights with a plain steel handrail, plaster fallen in sheets across the treads, tall stairwell windows
with every pane gone and green daylight coming through them.
```

**Anchor:** the half-landing window.

---

## 3.9 `@loc_MC_home_appartment`

```
A three-quarter interior wide view inside a derelict three-room flat in a Pripyat apartment block, camera
at chest height in the hallway doorway. Patterned Soviet wallpaper hanging off the walls in sheets, parquet
lifted and buckled, a padded torn entrance door behind. Through the doorways: a small bedroom with an iron
bed frame and rotted mattress under the window and a veneered wardrobe; a living room with a glazed display
cabinet, a rotted carpet and a window opening partly torn out where a mature tree branch has grown into the
room over a floor of leaf litter; a small kitchen with a rounded enamel fridge and dark mould blooming
above the sink.
```

**Anchor:** the torn-out window with the tree.

---

## 3.10 `@loc_MC_school`

```
A three-quarter interior wide view inside an abandoned school in Pripyat, Ukraine, camera low at desk
height. A classroom of wooden desks in rows under decades of fallen plaster and scattered paper, peeling
green and cream wall paint, a boarded blackboard wall, tall windows with every pane gone and birch visible
outside them. Beyond, through the doorway, the school gymnasium with its sprung wooden floor lifted and
buckled across the room and a rusted goal frame standing on it.
```

**Anchor:** the window wall. **Note:** no legible text on the blackboard, no dolls, no toys, no gas masks staged in frame.

---

## 3.11 `@loc_MC_shop`

```
A three-quarter interior wide view inside an abandoned Soviet department store in Pripyat, Ukraine, camera
at chest height looking down the length of the racks. Empty steel shelving in rows, a tiled floor under
plaster dust and fallen ceiling panels, peeling cream paint, a long shopfront of empty window frames along
one side with green daylight coming through.
```

**Anchor:** the shopfront.

---

## 3.12 `@loc_MC_basement` — CAMERA POSITION 1

Uses `[BASEMENT LIGHT]`, **not** the environment lock. Not a real place — no name to give it.

```
A three-quarter interior view of a low windowless institutional basement room about seven metres deep,
camera low at seated height on the near side of the room, the work table angled across frame at
FRONT-LEFT. Painted brick walls, a bare concrete floor, a closed steel door in the far wall dead ahead six
metres away. Against the LEFT wall a work table with glass syringes, tubes and instrument trays on it, and
a mirror mounted on the wall directly above the table facing across the room. One dim caged fixture above
the table is the only light.
```

**Anchor:** the mirror above the table.

---

## 3.13 `@loc_MC_basement_rev` — CAMERA POSITION 2

**This one uses `@loc_MC_basement` as a reference** — the only place in the project where a reference is
required, because it has to be the *same room* from a different angle. Attach the locked basement sheet and
add the inheritance ban line.

```
The same low windowless basement room seen from a second camera position: standing height, on the room's
near side and half a metre to the LEFT of the work table, looking over toward the mirror on the LEFT wall
so the mirror fills the upper half of frame and the table sits below it. The closed steel door is out of
frame behind camera-right. Painted brick walls, bare concrete floor, one dim caged fixture above the table.

@loc_MC_basement for location reference — take only the room, the materials, the table, the instruments and
the mirror. Do not use as a starting frame, do not inherit the composition, the angle or the grade.
```

**Anchor:** the mirror, filling the upper frame.

**Alternative if this drifts:** generate a short video of the empty room with the camera walking slowly
across it, screenshot the angle you need, and clean the texture up in Nano Banana Pro. A second location
sheet out of one image.

---

## WHERE REFERENCES ARE ACTUALLY NEEDED

| Asset | Reference? |
|---|---|
| All eleven Pripyat locations | **No.** Naming the real place is stronger, and a real photo drags autumn in with it. |
| `@loc_MC_basement` | **No.** Generic interior, nothing to match. |
| `@loc_MC_basement_rev` | **Yes** — the locked `@loc_MC_basement` sheet. Same room, second angle. |
| Concrete looking too clean after 3–4 tries | Optional texture-only reference with the inheritance ban line above. |

---

# 4 · ORDER OF WORK

| Step | What | Gate |
|---|---|---|
| 1 | `@char_MC_mr_chameleon_face` | Stress test: 10 generations, different poses and light, recognisable 10/10. Catch-lights in every one. |
| 2 | `@char_MC_mr_chameleon` (mask + wardrobe point change) | The eyes and brow must be identical to the master at 100% zoom. |
| 3 | `@char_MC_employee` | Stress test as above. |
| 4 | `@char_MC_employee_civil` (wardrobe point change) | **Test both employee tags in one frame.** This is the hardest shot in the film — if the two faces drift here, fix it now. |
| 5 | `@prop_MC_signs` | Test the pattern on both a forearm and a neck, under raking and flat light. It must vanish under flat light. |
| 6 | `@char_MC_employee_signs` (pattern point change) | The face must stay completely unmarked. |
| 7 | All 12 locations | Each carries the ENVIRONMENT LOCK. Generate them **in one sitting, back to back** — the whole point is that they read as one 1:00 PM afternoon. Each must survive re-framing from three angles without inventing new geometry. |
| 8 | Reverse angles for the flat and the basement | For the basement, generate `CAMERA POSITION 2` from the GEO map as its own sheet — generation 11 depends on it. |
| 9 | → `SHOTLIST_PROMPTS.md` | Nothing generates before this line. |

**If a stress test fails, the problem is the descriptor, not the model.** Rewrite the words and test again.
