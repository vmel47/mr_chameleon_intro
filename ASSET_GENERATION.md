# MR. CHAMELEON — ASSET GENERATION

Prompts for building every asset in the film. **Nothing in `SHOTLIST_PROMPTS.md` gets generated until everything here is `LOCKED`.**

## MODEL ROUTING

| Asset | Model | Notes |
|---|---|---|
| Character sheets | **Soul 2.0**, aspect 16:9, quality 2k | Soul ID on. Reference photo attached where noted |
| Location sheets | **Soul Cinema**, aspect 16:9, quality 2k | 3/4 angle, never frontal |
| Prop sheet (the signs) | **Nano Banana Pro**, 1:1 or 4:3, 2k–4k | |
| Wardrobe / mask variants | **Nano Banana Pro** point change, then masked back onto the original by hand | Never re-run a full sheet through a model twice |

## THE THREE RULES THAT BREAK THINGS IF IGNORED

1. **The character sheet is deliberately boring.** Neutral grey backdrop, flat even light, real pores, no retouch, **no film grain, no cinematic lens, no colour grade**. The cinema look lives in the locations and the video prompts. Bake it into the sheet and he carries it into every scene and stops reacting to new light.
2. **The front full-body figure has no head.** On wide shots the model pulls the face from the small blurry full-body figure instead of the portrait. Remove that head and there is exactly one place the face can come from.
3. **An image never runs through a model twice in full.** Mask, coat, dust — point changes only, composited back onto the original by hand. Two full passes and the face turns plastic and symmetrical, and dead texture kills the acting later in video.

---

# 1 · CHARACTERS

## 1.1 `@char_MC_mr_chameleon_face` — identity master (unmasked)

**Generate this first.** It is never seen in the film. It exists so that the eyes and brow stay identical across every masked shot, and so the Soul ID has a full face to lock onto.

**Model:** Soul 2.0 · 16:9 · 2k · **attach the reference photo** · Soul ID: create

```
Three studio photographs of the same man arranged side by side on a flat neutral mid-grey studio
backdrop, a film character sheet: a full-body front photograph on the left with the head cropped out of
frame above the shoulders, a full-body back photograph in the middle, and a large close-up portrait
photograph on the right turned slightly to three-quarter view. The same real person in all three,
consistent across panels. Soft directional studio lighting from one side, gentle natural shadow falloff,
clean neutral look, no styling.

The man: tall and athletically built, broad through the shoulders and chest, lean at the waist, standing
with a naturally low and grounded centre of gravity. Dark brown hair, short at the sides and longer on
top, swept back and slightly to one side, the hairline set back at the temples so the forehead reads
high and square. Long sideburns running past the ear. Thick straight dark eyebrows set low and close to
the eye, one sitting a fraction lower than the other. A single deep vertical furrow between the brows,
present even at rest. Deep-set dark brown eyes with heavy hooded upper lids. A straight narrow nose with
a defined tip. Full lips with a sharply cut upper lip line. Broad flat cheekbones, a wide jaw, a slightly
heavy chin. Pale skin with visible pores and a faint stubble shadow along the jaw and upper lip. A
neutral unsmiling resting face that reads slightly tired and completely calm.

Wardrobe, consistent in all panels: a plain dark grey long-sleeved base layer and plain dark trousers.
Nothing else — no jacket, no bag, no accessories.

On the left panel he stands straight facing camera in a neutral pose, arms relaxed at the sides, feet
shoulder width, the frame cut across the top of the shoulders so no head is visible. In the middle panel
the same standing pose seen from directly behind, full figure head to feet. On the right panel a large
close-up head-and-shoulders portrait turned to three-quarter view, eyes to camera, mouth closed, a clear
catch-light in each pupil.

Clean dry skin, natural skin tones, even exposure, sharp focus on the face.
```

**Rules:** no "character reference sheet" and no "painterly" in the prompt — both trigger illustration. No rule of thirds on sheets. Check the catch-lights before accepting: dark eyes without a reflection in the pupil read dead, and no video model can act with a dead face.

## 1.2 `@char_MC_mr_chameleon` — the film version (masked, dressed)

Built as a **point change on the locked master**, not a new generation.

**Model:** Nano Banana Pro, edit on the master sheet · then composite back by hand with a mask

```
Edit the image: dress the man and add a face mask, changing nothing about the face above the eyes.

CHANGE:
Add a dark grey technical half-mask covering the nose, mouth, chin and jaw, with its top edge sitting
just under the lower eyelids. Matte woven fabric with a soft moulded shape over the nose bridge, an
elastic strap disappearing behind the ear, worn and slightly dusty. Not a medical mask, not a
respirator cartridge, no valves, no filters, no branding.
Dress him in a faded olive-grey softshell field jacket, hood down, storm flap over the zip, no
insignia and no logos anywhere; a dark grey base layer at the collar; washed olive-khaki cargo
trousers gathered into scuffed black nylon-and-leather boots; thin dark gloves. Everything worn,
dust-loaded at the shoulders and thighs, colours desaturated toward concrete and birch bark.

PRESERVE EXACTLY:
- The eyes, brow, forehead, hairline, hair and ears — pixel for pixel
- The eye colour, the hooded lids, the furrow between the brows, the catch-lights
- Head angle and gaze direction in every panel
- Body proportions, stance and the position of every limb
- The headless crop on the left panel
- Neutral grey backdrop, flat lighting, all existing shadows
- Colour grade, palette, contrast, grain, falloff

ONLY CHANGE: the clothing and the addition of the half-mask. 100% identical otherwise.
```

**Then:** open the original master and the edited version in any editor with masks, and paint only the clothing and mask region of the edit onto the original. The skin around the eyes must be the master's original texture. This is the pass that keeps the face alive.

**Wardrobe logic — why this and not a hazmat suit.** He is not protecting himself from the zone; he lives in it and it does not frighten him. The clothing is about not being noticed: muted, unbranded, unmilitary, the colour of wet concrete and birch. Someone who has walked many kilometres already and is walking home calmly and steadily. The mask reads as habit, not as safety equipment.

## 1.3 `@char_MC_employee` — the lab worker

**Model:** Soul 2.0 · 16:9 · 2k · Soul ID: create

```
Three studio photographs of the same woman arranged side by side on a flat neutral mid-grey studio
backdrop, a film character sheet: a full-body front photograph on the left with the head cropped out of
frame above the shoulders, a full-body back photograph in the middle, and a large close-up portrait
photograph on the right turned slightly to three-quarter view. The same real person in all three,
consistent across panels. Soft directional studio lighting from one side, gentle natural shadow falloff,
clean neutral look, no styling.

The woman: ordinary build, medium height, unremarkable and entirely believable as someone who has worked
the same job for years. Mid-brown hair pulled back and pinned, a few strands loose at the temple. Plain
face, no makeup, tired around the eyes, slightly dry skin with visible pores and a faint natural flush
across the cheekbones. Grey-blue eyes with a clear catch-light in each pupil. A closed, neutral, slightly
absent expression — she is thinking about something else.

Wardrobe, consistent in all panels: a plain white cotton medical coat, buttoned, slightly grey with age
and pressed flat; a plain light blue medical mask pulled down and sitting loose under her chin so the
whole face is open; plain dark trousers and flat closed shoes underneath.

On the left panel she stands straight facing camera in a neutral pose, arms relaxed at the sides, the
frame cut across the top of the shoulders so no head is visible. In the middle panel the same standing
pose seen from directly behind. On the right panel a large close-up head-and-shoulders portrait turned to
three-quarter view, eyes to camera, mouth closed, the mask visible under the chin.

Clean dry skin, natural skin tones, even exposure, sharp focus on the face.
```

## 1.4 `@char_MC_employee_civil` — the copy in the mirror

Built as a **point change on the locked `@char_MC_employee` sheet**, so the face is guaranteed identical.

```
Edit the image: change only the clothing.

CHANGE: Replace the white medical coat and the medical mask with ordinary everyday civilian clothes —
a plain dark knit sweater over a collared shirt, and plain dark trousers. No coat, no mask anywhere in
frame, nothing medical, nothing institutional.

PRESERVE EXACTLY:
- The face, pixel for pixel — every feature, the skin texture, the catch-lights
- The hair, exactly as pinned, including the loose strands
- Head angle, gaze direction and expression in every panel
- Body proportions, stance and the position of every limb
- The headless crop on the left panel
- Neutral grey backdrop, flat lighting, all existing shadows
- Colour grade, palette, contrast, grain, falloff

ONLY CHANGE: the clothing. 100% identical otherwise.
```

> **Why this is a separate tag and not an adjective.** In generation 11 both versions stand in the same mirror at the same time. Written as one tag with "in ordinary clothes" attached, the model mixes the states between takes — you get two coats, or two sweaters, or the coat on the wrong one. Two tags, one face, one wardrobe each.

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

**All Soul Cinema · 16:9 · 2k · shot in 3/4, never frontal.** Each carries an anchor object and one light logic.

**Every location prompt ends with the `ENVIRONMENT LOCK` from `STYLE_PREFIX.md`, pasted word for word, plus this tail.** This is what makes twelve separately generated places read as one city at 1:00 PM — and it has to hold even when no reference image is attached. `@loc_MC_basement` is the only exception: it gets the basement light line instead.

```
[TAIL] Palette of 60% new-growth birch and grass green, 30% weathered concrete grey and pale sky,
10% rust-orange oxidised metal. Empty deserted place, no people anywhere, no vehicles, no lit windows,
no intact glazing. Vegetation growing through every hard surface. Cinematic film still, natural film
texture, no grain stacking.
```

```
[BASEMENT LIGHT — replaces the ENVIRONMENT LOCK for @loc_MC_basement only]
No daylight of any kind. One dim overhead fixture directly above the work table, everything else falling
away two stops into shade. Palette of 60% dead institutional green-grey, 30% deep shade, 10% the cold
white of enamel and glass.
```

| Tag | Prompt body (add `[TAIL]`) |
|---|---|
| `@loc_MC_forest` | *High three-quarter wide shot, camera at eye height looking diagonally down an overgrown path.* Dense mixed pine and birch forest inside an exclusion zone, tall bare trunks, deep leaf litter, low undergrowth, a single overgrown path running away toward a bright break in the treeline ahead. **Anchor: the break in the trees.** |
| `@loc_MC_pripyat_sign` | *Three-quarter wide shot from the roadside, camera at chest height, the sign angled across frame.* A freestanding Soviet concrete city sign standing alone on open ground, raised relief lettering and a date, weathered white surface, lichen crust in the letter troughs, rust bleed at the fixings, grass and birch saplings at the base, flat empty ground behind it. **Anchor: the slab.** |
| `@loc_MC_pripyat_entrance` | *Three-quarter wide shot along the road, camera at eye height.* A cracked asphalt approach road into an abandoned city, the surface split open by birch saplings, overgrown verges, the first derelict concrete apartment blocks rising behind a screen of mature trees. **Anchor: the roadway centre line.** |
| `@loc_MC_dk_energetic` | *High three-quarter wide shot, camera above head height looking diagonally down across the square.* A long modernist colonnaded Palace of Culture on a wide paved civic square, ruined façade, empty window openings, spalled concrete, moss on the steps, the paving broken open by birch saplings. **Anchor: the colonnade.** |
| `@loc_MC_pripyat_city` | *Aerial three-quarter view from fifty metres, looking diagonally down and across.* An abandoned Soviet city reclaimed by forest — rows of sixteen-storey and five-storey concrete blocks with empty window openings, mature birch and poplar filling every street and courtyard, a flat treeless horizon beyond with a vast arched steel confinement structure far off on it. **Anchor: the tallest block.** |
| `@loc_MC_park` | *Three-quarter wide shot, camera at standing height, the rides angled across frame.* An abandoned amusement park gone to forest — a Ferris wheel with yellow rusted cabins on an oxide-streaked steel frame, an open-sided bumper-car pavilion with painted steel cars rusted in place under a contact grid, rusted swing boats and a small carousel with a collapsed canopy, birch grown up through the asphalt everywhere. **Anchor: the Ferris wheel.** |
| `@loc_MC_home_area` | *Three-quarter wide shot from the courtyard, camera low looking slightly up at the façade.* The entrance and courtyard of a derelict concrete apartment block, spalled render, empty window openings, a dark entrance doorway, overgrown asphalt and birch saplings, an arched steel confinement structure visible far off on the horizon. **Anchor: the entrance doorway.** |
| `@loc_MC_home_stairs` | *Three-quarter interior view up the flight, camera at chest height.* A derelict Soviet apartment stairwell — torn-open mailboxes in the entrance hall, bare concrete flights with a steel handrail, plaster fallen across the treads, tall stairwell windows with all glazing gone. **Anchor: the half-landing window.** |
| `@loc_MC_home_appartment` | *Three-quarter interior wide, camera at chest height in the doorway.* A derelict Soviet three-room flat — a hallway with patterned wallpaper hanging in sheets, a bedroom with an iron bed frame and rotted mattress under the window, a living room with a glazed display cabinet and a rotted carpet where a window has been torn out and a mature tree branch has grown into the room, a small kitchen with a rounded enamel fridge and mould blooming above the sink. **Anchor: the torn-out window with the tree.** |
| `@loc_MC_basement` | *Three-quarter interior view, camera low at seated height, the table angled across frame.* A low windowless institutional basement room, painted brick walls, one closed steel door, a work table against the far wall with glass syringes, tubes and instrument trays on it, a mirror mounted on the wall directly above the table, one dim overhead fixture. **Anchor: the mirror.** *(Override the tail here: no daylight — one dim overhead source above the table, the room falling away into deep shade at the edges.)* |
| `@loc_MC_school` | *Three-quarter interior wide, camera low at desk height.* An abandoned Soviet school interior — a gymnasium with a buckled sprung wooden floor, wall bars and a rusted goal frame; and a classroom of wooden desks in rows under fallen plaster and scattered paper, tall windows, peeling green wall paint. **Anchor: the window wall.** |
| `@loc_MC_shop` | *Three-quarter interior wide, camera at chest height along the racks.* An abandoned Soviet shop interior — empty steel shelving racks in rows, a tiled floor under plaster dust, a shopfront of empty window frames along one side, peeling cream paint. **Anchor: the shopfront.** |

**Reverse angles** — needed for `@loc_MC_home_appartment` and `@loc_MC_basement`. Two ways:
1. GPT Image 2, describing the **new object arrangement explicitly** — what was frame-right is now frame-left, object by object.
2. Better: generate a short video of the empty location with the camera walking slowly through it, screenshot the angle you need, then improve textures in Seedream 4.5 or NBP. A full location sheet out of one image.

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
