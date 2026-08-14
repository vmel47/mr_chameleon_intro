# 04A · ПАНОРАМА ГОРОДА · 20s · без персонажа

Единственный кадр фильма, где камера не на земле. Людей нет, ходьбы нет, взгляда нет — **одна непрерывная
горизонтальная панорама с постоянной скоростью**.

Сюда ложится `VO-03` на **+4.0s**: *"My favourite city. You are more beautiful than I remember you."*

---

# 1 · ЛОКАЦИЯ

Если найдёшь хорошее реальное аэрофото Припяти — прикладывай его как **IMAGE 1** и пропускай генерацию,
это точнее. Тогда в промпте добавь ту же оговорку, что и в 03A: брать место, **не брать погоду, ракурс и
время суток**.

Если фото нет — генерим. Этот тег потом работает ещё и атмосферным якорем для интерьеров, так что он нужен
в любом случае.

**Модель:** Higgsfield **Soul Cinema** · aspect **16:9** · quality **2k** · тег `@loc_MC_pripyat_city`

```
Wide high aerial cinematic film still of Pripyat, the abandoned Soviet nuclear town in the Chernobyl
exclusion zone, photographed today from about fifty metres up — high above the treetops but below the roofs
of the tallest blocks, so the tall buildings still rise against the sky rather than being looked down onto.
Camera level and horizontal, looking out across the town, not tilted down at it. This is a real, specific
place as it stands now.

THE TOWN. Rows of abandoned residential blocks stretching away across the whole width of frame — five-storey
and nine-storey precast concrete panel buildings, and several sixteen-storey towers standing higher than the
rest with large blank end walls. Flat rooflines, regular grids of empty black window openings, no glass
anywhere, panel joints streaked black with forty years of rain, rusted balcony rails, birch growing on roof
edges and out of balconies. One tower carries a large faded coat-of-arms panel on its end wall, chalky and
half gone.

THE FOREST. This is the important part: the town is not standing in open ground, it is drowning. Continuous
dense forest fills every street, every courtyard and every gap between the buildings, in full new-green
leaf, its canopy reaching the second and third floors. From this height the streets are not visible at all —
only the roofs and upper floors of the blocks emerging out of an unbroken green canopy, like buildings
standing in a lake. No open ground anywhere except a few pale patches of cracked square.

THE HORIZON. Far beyond the town, small and hazy, the low silver arch of the reactor confinement structure
sits on the skyline, unmistakable in silhouette but distant and quiet. Beyond and around it, flat forest to
the edge of the world.

Late spring afternoon at one o'clock under half broken cloud, soft sun high and three-quarters behind, warm
rim along the roof edges and the tops of the canopy, façades a stop and a half under so the window openings
read as flat black voids. Soft-edged shadows all falling the same way. Strong aerial haze thickening with
distance so the far blocks go pale and flat.

Palette of 60% new-growth green, 30% weathered concrete grey and pale sky, 10% rust-orange oxidised metal.
Neutral daylight white balance around 5600K, natural saturation, medium contrast, even exposure corner to
corner.

Rule of thirds. Empty deserted town, no people, no vehicles, no working lights, no smoke, no aircraft, no
contrails, no birds.

Shot on ARRI Alexa Mini LF with ARRI Signature Prime lens, clean modern digital cinematic capture, crisp
natural detail, minimal fine grain, soft cinematic falloff, hyperrealistic photographic detail.
```

**Что проверить в результате**

| Симптом | Что делать |
|---|---|
| Взгляд сверху вниз, крыши плашмя | Усилить `camera level and horizontal, looking out across the town, not tilted down at it` |
| Между домами видны улицы и открытая земля | Главная ошибка. Усилить `the streets are not visible at all, only roofs and upper floors emerging out of an unbroken green canopy` |
| Город выглядит целым, жилым | Усилить `every window an empty black opening, no glass anywhere` |
| Саркофаг слишком крупный, лезет в центр | Усилить `small and hazy on the skyline, distant and quiet` |
| Нет дымки, всё одинаково резко | Усилить `strong aerial haze so the far blocks go pale and flat` — без неё нет глубины |

---

# 2 · ВИДЕО

**Модель:** Seedance 2.5 · 16:9 · **20s** · референс: `@loc_MC_pripyat_city`

```
EXACT 0 CHARACTERS — the city itself is the subject. No people anywhere, no bodies, no silhouettes, no
figures in any window or on any roof.

SCENE CONTEXT
One slow, unbroken horizontal pan across an abandoned city seen from the air. Nothing happens in it. It is
a portrait of a place, held long enough that the audience has to look at it.

ACTIVE REFERENCE
@loc_MC_pripyat_city for the place — take the rows of derelict precast concrete panel blocks and the taller
sixteen-storey towers, the empty black window openings, the streaked panel joints, the unbroken green
canopy drowning every street and courtyard, and the distant silver arch of the reactor confinement on the
horizon. Do not use it as a starting frame and do not inherit its exact composition — the shot is a moving
pan that travels well past the edges of that view in both directions.

CAMERA — the one thing this shot is
The camera is at a fixed height of about fifty metres, level and horizontal, looking out across the town
and never tilted down at it. It performs exactly ONE movement for the whole twenty seconds: a slow
horizontal pan, rotating on the spot at one constant rate.
It is ALREADY panning in the first frame, at full speed, with no ease-in. It is STILL panning in the last
frame, at exactly the same speed, with no ease-out and no settle. The take is a slice out of a longer
movement, not a movement with a beginning and an end.
The rate never changes: it never accelerates, never slows, never pauses, never hesitates and never reverses.
The height never changes. The horizon stays at the same place in frame from the first frame to the last.
There is NO drone push, NO fly-through, NO forward travel, NO orbit, NO arc, NO descent, NO ascent, NO
zoom, NO tilt, NO roll. The camera rotates and does nothing else.
It is a smooth mechanical pan head, not a handheld body — this is the one shot in the film that is NOT a
walking camera, so there is no step bounce, no sway and no gait. Only the faintest continuous air movement,
the amount a stabilised aerial camera has.

FORMAT MODE
ONE single continuous unbroken take. No cuts of any kind — no hard cut, no jump cut, no transition, no
dissolve, no change of camera position, no separate shots. Twenty seconds, one camera, one movement.

OPTICS
47° horizontal field of view — normal, no wide-angle bulge. Deep focus, everything sharp from the nearest
roof to the far horizon, softened only by aerial haze. No rack focus, no shallow depth of field, no lens
flare, no anamorphic streaks, no fisheye, no barrel distortion at the edges.

ENVIRONMENT
Season: late spring turning to early summer. Birch, poplar and grass in full new green, everything
overgrown, everything alive.
Sky: half broken cloud, slow-moving, with gaps of pale blue.
Sun: high and soft behind thin cloud, warm directional light sitting high and three-quarters behind, soft
warm rim on edges, camera side a stop and a half under.
Shadows: soft-edged and long, all falling the same way.
Air: strong aerial haze thickening with distance, the far edge of the town pale and flat.
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
The pan is already running. Horizon across the upper third and held there for the whole take. Below it,
rows of derelict apartment blocks stretching across the full width of frame, their roofs and upper floors
emerging from an unbroken green canopy that fills every gap between them — no street is visible, no open
ground, no bare earth. Two sixteen-storey towers stand higher than the rest with large blank streaked end
walls. Far off on the skyline, small and pale in the haze, the low silver arch of the reactor confinement.
Sky and half broken cloud above the horizon line.

ACTION TIMING
0.0–7.0s — the pan is already at speed. Blocks pass through frame one after another, each one emerging at
one edge and leaving at the other at the same steady rate. Between them, unbroken forest canopy. The
distant arch sits on the horizon and drifts slowly across.
7.0–14.0s — the middle of the town passes at exactly the same rate. Nothing new happens and nothing is
emphasised. More blocks, more canopy, more haze. One of the sixteen-storey towers crosses frame, its blank
end wall streaked and chalky.
14.0–20.0s — the far edge of the town and the flat forest horizon beyond it. The pan is still running at
the same rate in the final frame and does not slow, settle or stop.

PHYSICS
Cloud moves at cloud speed, far slower than the pan. The forest canopy moves on wind in slow travelling
waves across whole blocks of trees at once, never as individual leaves at this distance. The buildings are
dead static mass and do not move at all. Nothing else in the entire frame moves — no vehicles, no birds, no
smoke, no aircraft, no water, no falling debris.

LIGHTING
Full open afternoon daylight from above. Soft sun high and three-quarters behind: warm rim along every roof
edge and along the top of the canopy, façades turned toward camera a stop and a half under so the window
openings read as flat black voids. Aerial haze lifts the far distance and lowers its contrast. The light
level is constant across the whole take and never drops.

AUDIO
Diegetic environmental sound only — high open air, steady wind across an exposed height, the distant
massed rustle of a forest canopy far below, one or two very distant bird calls. No engine noise, no rotor
noise, no drone hum. No music. No narration. No voices. Nobody speaks.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary realism of an abandoned place, not a dressed set.
Cinematography: natural motivated light only; painterly composed frames; the frame is a held observation, not a flourish.
Lighting: Late spring afternoon at 1:00 PM under half broken cloud. Soft sun high and three-quarters behind — warm rim on every edge, camera side a stop and a half under, never blinding, no hard flare. Key light from sky only.
Color: 60:30:10 — 60% new-growth green, 30% weathered concrete grey and pale sky, 10% rust-orange oxidised metal.
Camera: Physical cine lens. 180° shutter motion blur.
Surfaces: Material-level realism — weathered precast concrete, streaked panel joints, chalky end walls, rusted steel, decades of dirt. Nothing looks recently placed.
Physics: Gravity and inertia respected — mass has real weight, correct contact shadows. No floating geometry.
Vegetation: Birch and poplar that have swallowed the town — canopy filling every street and courtyard, trees on roof edges and balconies, all of it moving on real wind in slow travelling waves.
Composition: Rule of thirds + golden ratio.
Continuity: Environment identical from the first frame to the last. No drift.
Technical: 24fps smooth motion. 8K detail. No jitter. No flicker. No vignette, no edge darkening, even exposure corner to corner.
Audio: Environmental SFX only. No music. No subtitles. No narration. No voices.

QUALITY
8K detail. Precast concrete, streaked joints and rust at material level. Clean cloud gradation, clean haze
gradient into the distance. No jitter, no flicker.

POSITIVE CONSTRAINTS
Zero people anywhere. Zero moving vehicles, zero lit windows, zero smoke, zero aircraft, zero contrails,
zero birds, zero drones in shot.
ONE continuous take with ZERO cuts.
The pan runs at ONE constant rate from the first frame to the last. It is already moving in the first frame
and still moving in the last. It never starts, never stops, never eases in, never eases out, never
accelerates, never slows, never pauses and never reverses.
The camera height never changes and the horizon stays at the same height in frame throughout. No push, no
fly-through, no forward travel, no orbit, no arc, no descent, no ascent, no zoom, no tilt, no roll. Rotation
only.
This is not a walking camera: no step bounce, no sway, no gait, no handheld motion.
Every building is derelict: flat rooflines, bare precast panels, every window an empty black opening with
no glass in any frame.
Forest fills every street and every courtyard — no visible roadway, no open ground, no bare earth between
the blocks.
Exactly ONE reactor confinement arch, far off on the skyline, small and pale in the haze, never brought
close and never centred.
Half broken cloud, never a clear cloudless sky.
Late spring, full new green. Not autumn, not winter, no bare branches, no brown canopy.
No vignette, no edge darkening, even exposure corner to corner.
Photoreal. NON-IP. 16:9. 20s. SFX only. NO CGI. Cinematic. Present tense. Short sentences.
```

---

# 3 · ЧЕМ ЭТОТ КАДР ОТЛИЧАЕТСЯ ОТ ВСЕХ ОСТАЛЬНЫХ

Во всех предыдущих генерациях камера была телом: походка, качка, коллайдер, поворот шеи. **Здесь всего
этого нет и быть не должно** — поэтому из промпта убраны блоки `COLLIDER` и `GAZE`, а в констрейнтах прямо
написано, что это не идущая камера.

Вместо них главный блок — `CAMERA`, и он почти весь состоит из запретов. Причина простая: слово «аэросъёмка»
тянет за собой весь дроновый штамп — разгон, облёт, набор высоты, наезд, блик в объектив. Здесь нужно
ровно одно движение с постоянной скоростью, которое **уже идёт в первом кадре и всё ещё идёт в
последнем**. Кадр должен читаться как вырезка из более длинного движения, а не как законченный проезд.

Вторая вещь, которая ломает этот кадр чаще всего, — между домами появляются улицы и открытая земля. Тогда
город выглядит просто пустым. Нужно, чтобы он выглядел **утонувшим**: сплошная зелень до второго-третьего
этажа, улиц не видно вообще, торчат только крыши. Это прописано и в локации, и в видео, и в констрейнтах.

---

# 4 · ОЧЕРЕДЬ ДАЛЬШЕ

| Ген | Что | Локация |
|---|---|---|
| **04B** | Три статичных интерьера: спортзал, класс, магазин | `@loc_MC_school`, `@loc_MC_shop` |
| **05A** | Парк: колесо и машинки | `@loc_MC_park` |
| **05B** | Парк: качели и общий план | `@loc_MC_park` |
| **07** | Комната и зал | `@loc_MC_home_appartment` |
| **08** | Кухня | `@loc_MC_home_appartment` |

Дальше идут четыре генерации подряд, где **вообще ничего не движется**, кроме пыли, листа на сквозняке и
ветра снаружи. Это самая дешёвая и самая надёжная часть съёмки — и одновременно та, где легче всего
получить мёртвую картинку вместо неподвижной. Разница в том, что в неподвижном кадре что-то одно всё-таки
шевелится.
