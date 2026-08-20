# MR. CHAMELEON — ASSET REGISTRY

One dictionary of names for the whole project. Same tags in documents, prompts, canvas and filenames.
Nothing gets generated as video until every tag below is `LOCKED`.

**Status values:** `TODO` → `DRAFT` → `TESTED` (10/10 recognisable) → `LOCKED`

---

## CHARACTERS

| Tag | What | Sheet notes | Status |
|---|---|---|---|
| `@char_MC_mr_chameleon` | The narrator, as seen in the film: muted field clothing, dark half-mask covering everything below the eyes. Athletic build, 185 cm, 88 kg. Stillness in the body — he never fidgets. | Point change on `@char_MC_mr_chameleon_face`: mask + wardrobe, composited back by hand. | TODO |
| `@char_MC_employee` | Lab worker. White medical coat, medical mask pulled down under the chin, face open. Soviet-era institutional look. | Same 3-panel structure. | TODO |
| `@char_MC_employee_civil` | **Same face as `@char_MC_employee`, ordinary civilian clothes, no coat, no mask.** This is the double in the mirror. | Point change only: wardrobe swapped on the original sheet via NBP/Seedream, masked back onto the original by hand. Face texture must be pixel-identical to `@char_MC_employee`. | TODO |
| `@char_MC_employee_signs` | Same woman, same coat — with the marks surfaced under the skin of the neck, hand and forearm. The **target end state** for generation 10. | Point change on the locked base sheet. Face stays completely unmarked. | TODO |
| `@char_MC_mr_chameleon_face` | Identity master, unmasked. **Never appears in the film.** Exists so the Soul ID locks a full face and the eyes never drift under the mask. | Built first, from the descriptor alone — no reference image. Everything else is a point change on it. | TODO |

> `@char_MC_employee_civil` is **not optional**. The mirror scene shows two identical faces in one frame. Written as one tag with a wardrobe adjective, the model mixes the states between shots.

**Face rule for this film:** he wears the half-mask in every single shot and it never comes off. Nothing below the eyes is ever seen. The film's one close look at him is the push in the ending — and what it arrives at is his eyes above the mask, not a face. This is deliberate: there is no face to reveal, and the audience never gets one.

---

## LOCATIONS

All location sheets shot in **3/4, never frontal**. Each carries an anchor object and one light logic.

| Tag | What | Anchor | Status |
|---|---|---|---|
| `@loc_MC_forest` | Dense pine/birch forest inside the zone, full new green, low undergrowth, an overgrown path. | The gap in the trees ahead | TODO |
| `@loc_MC_duga_fragment` | **OPTIONAL** — only if the Duga shot in `OPTIONAL_SHOTS.md` is used. A fragment of the Duga radar array among the trees — one lattice leg and a section of mesh, never the full silhouette. Seen before the city sign, so it must stay unrecognisable. | The lattice leg and its concrete foot | TODO |
| `@loc_MC_forest_pripyat_sign_path` | The route from the forest to the city sign. Must be generated again; old asset is visual orientation only. | The road running away between the trees | TODO |
| `@loc_pripyat_sign_2` | The concrete "ПРИПЯТЬ 1970" city sign on the right-hand verge. Must be generated again; old asset is visual orientation only. | The sign slab itself | TODO |
| `@loc_MC_pripyat_city` | Master reference for the whole city — texture, palette, atmosphere, era. Used as an atmosphere anchor in interior clips and for the aerial panorama. | Skyline of 16-storey blocks | TODO |
| `@loc_MC_pripyat_street` | A long street **inside** the city: a row of six or more panel blocks receding down the LEFT side, forest and nothing else down the RIGHT, wide cracked asphalt with saplings through every seam. Replaces the old `pripyat_entrance` — the approach road is already covered by generations 02 and 02B's opening. | The receding row of blocks | TODO |
| `@loc_MC_dk_energetic` | The Palace of Culture "Energetik" on the central square, ruined façade, colonnade. | The colonnade | TODO |
| `@loc_MC_park` | The amusement park — Ferris wheel, bumper-car pavilion, swings and carousel, moss and birch growing through the asphalt. | The Ferris wheel | TODO |
| `@loc_MC_home_area` | The courtyard and façade of his residential block, seen from outside. Reactor 4 sarcophagus on the horizon. | The entrance doorway | TODO |
| `@loc_MC_home_stairs` | The stairwell — entrance hall, mailboxes, concrete flights to the second floor. | The second-floor landing door | TODO |
| `@loc_MC_home_appartment` | The three-room flat: his room, the living room, the kitchen. Soviet furniture untouched for decades, a tree branch grown in through the broken living-room window. | The broken window with the tree | TODO |
| `@loc_MC_basement` | Low institutional basement room ~7 m deep. Closed steel door in the far wall; work table against the LEFT wall with the mirror mounted above it. Dim overhead fixture, no daylight. | The mirror above the table | TODO |
| `@loc_MC_basement_rev` | The same room from **CAMERA POSITION 2**: behind the worker and half a metre to her left, looking over her shoulder into the mirror. Generation 11 depends on it. | The mirror, filling the upper frame | TODO |
| `@loc_MC_school` | Abandoned Soviet school — gymnasium with buckled sprung floor, and a classroom of desks under fallen plaster. | The window wall | TODO |
| `@loc_MC_shop` | Abandoned Soviet shop — empty steel shelving racks, tiled floor, shopfront of empty window frames. | The shopfront | TODO |

## PROPS

| Tag | What | Status |
|---|---|---|
| `@prop_MC_signs` | The pattern **look library** — a texture and behaviour reference for the marks, not an object that appears in frame. `@char_MC_employee_signs` is built from it, and every video prompt describing the marks is written against it. | TODO |

---

## THE ENVIRONMENT LOCK

Every location except the basement is generated under the **same** season, sky and sun — see `STYLE_PREFIX.md`. Late spring into early summer, half broken cloud, soft sun high and three-quarters behind the subject, 1:00 PM (early afternoon).

**Generate all the daylight locations back to back in one sitting.** The whole point is that twelve separately generated places read as one city at 1:00 PM. Come back a week later and the palette will have drifted.

The reactor confinement is not its own tag — it lives inside `@loc_MC_pripyat_city` and `@loc_MC_home_area` as a horizon element, because it is only ever seen at distance.

**State splits:** none needed. One weather, one hour, one film. If a night or rain version is ever required it becomes a **separate tag**, never an adjective inside a prompt.

---

## REFERENCE ROLE LINES (paste into prompts)

```
@char_MC_mr_chameleon for character reference — muted field clothing, a dark half-mask covering the lower
face up to just under the eyes; <posture and state anchors relevant to this shot>
@char_MC_employee for character reference — white coat, mask pulled down under the chin, face open
@char_MC_employee_civil for character reference — the same face, ordinary civilian clothes, no coat, no mask
@char_MC_employee_signs for character reference — the same woman and coat, with the marks surfaced under the
skin of the neck, hand and forearm; her face completely unmarked

@loc_MC_<x> for location reference — take only the space and the texture: <materials, key features>.
Do not use as a starting frame, do not inherit the composition, the angle or the grade.
```

---

## STRESS TEST GATE

Before any tag moves to `LOCKED`:

- 10 generations, different poses, different light → recognisable 10 out of 10
- `@char_MC_employee` and `@char_MC_employee_civil` tested **in the same frame** — this is the hardest shot in the film
- `@char_MC_mr_chameleon` tested in broken-cloud exterior daylight and against a concrete façade — the mask must never slip or change shape
- Every daylight location tested against two others side by side: same season, same sky, same sun direction
- Every face carries a catch-light in the pupil

If a test fails, rewrite the descriptor. Not the model.
