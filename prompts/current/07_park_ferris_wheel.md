# 07 · ПАРК, КОЛЕСО ОБОЗРЕНИЯ · 14s · ОДНА ГЕНЕРАЦИЯ

Второй кадр парка, и он простой. Он идёт по открытой площадке, держит колесо во взгляде и не отпускает его.
Колесо растёт, потому что он подходит. Больше в кадре не происходит ничего.

**Ход, коллайдер, физика и оптика шага взяты один в один с ДК «Энергетик» и с `05A`.** Не переписывал —
там это отработало, и трогать не за чем. Отличие ровно одно: там взгляд поворачивался один раз, здесь он не
поворачивается вообще, он просто прилипает к колесу.

**Генерация локации отменена.** Есть настоящая фотография — она и есть `@Image 1`. Прежний запрос в
GPT Image 2 не нужен, кредиты не тратим.

**Модель:** Seedance 2.5 · 16:9 · **14s**
**Референс один: `@Image 1`** — фотография колеса с разметкой. Линия по земле — направление движения,
линия в воздухе — направление камеры.

**Почему красная линия лезла в кадр, а синяя нет.** Красная нарисована ПО ЗЕМЛЕ, вдоль плит. Для модели это
читается как разметка на асфальте — вещь, которая в реальности бывает, поэтому она её честно рисует. Синяя
висит в воздухе над деревьями, объектом быть не может, и модель её отбрасывает сама.
Поэтому лечение не «запретить стрелку» ещё раз, а **описать, что на земле есть вместо неё**. В конце промпта
стоит блок `THE GROUND IS BARE`, где перечислено, чем покрыт пол площадки, и сказано, что это всё. Плюс
слово «стрелка» из инструкций убрано вообще — теперь это `the marked direction of travel`, чтобы не
подсказывать модели картинку, которую мы не хотим видеть.
И отдельный запрет на текст: ты подписал на картинке «Направление» — кириллица тоже отлично уезжает в кадр.

**Оптика шире, чем в `05A`, и это единственный расчёт во всём промпте.** На 47° колесо в двадцать шесть
метров влезает по высоте только со ста метров, а за четырнадцать секунд шага он проходит двадцать два —
рост вышел бы двадцать процентов, глазом не читается. На 62° старт с семидесяти пяти метров, финиш с
пятидесяти трёх, колесо растёт в полтора раза. И фотография сама снята широким, так что кадр с ней сойдётся.

```
EXACT 0 CHARACTERS VISIBLE — STRICT FIRST-PERSON POV. No body, no hands, no arms, no shoulders, no feet
and no cast shadow of the viewer enters frame at any moment. We only ever see what he sees.

SCENE CONTEXT
He walks across the open paved clearing in the abandoned amusement park in Pripyat, toward the derelict
Ferris wheel. He is already walking and already looking at it when the shot begins, and he keeps looking at
it for the whole take. He does not slow down, does not stop, does not react and never looks away. He walks
this way often.

@Image 1 — THE MAIN REFERENCE. The whole look of this shot comes from here.
@Image 1 is a photograph of the actual place. Take everything visual from it: the location, the materials,
the light, the weather, the season, the greenery, the colour, the sky. It is the master reference and it
governs how the shot looks.

What is in it, so it is not lost:
A lattice steel Ferris wheel about twenty-six metres high, standing alone in a clearing. Its rim and spokes
are a fine web of thin girders and tie rods. Painted lemon yellow, now chalky and sun-bleached, rust
bleeding down from every bolted joint. A ring of open gondolas hangs from the rim, each a small box with a
curved yellow sunshade roof and a plain bench seat; they hang dead still and several sit slightly askew on
seized pivots. The central hub is a heavy rusted casting with a radiating pattern of tie rods. Two braced
A-frame lattice legs, rust-brown, carry it down to squat concrete footings with grass and saplings tight
around their bases.
Around it: birch and poplar saplings and young trees, six to twelve metres tall, grown up through the
paving on both sides and closing in behind the wheel, their crowns crossing in front of its lower gondolas.
The clearing floor: large cracked concrete paving slabs, heaved and split, grass and moss through every
joint, low weeds spreading in from the edges.
Sky: deep blue with broken white cumulus, brightest behind the wheel. Bright summer afternoon, sun fairly
high, strong clear light, crisp shadows. That weather and that light are the ones to use.

THE COLOURED LINES ON @Image 1 ARE A DIAGRAM DRAWN ON TOP OF THE PHOTOGRAPH. THEY ARE NOT IN THE PLACE.
@Image 1 has bright coloured lines and a handwritten word added onto it afterwards, in an image editor, to
explain the shot. They are not paint, not tape, not a road marking, not a sign, not an object and not part
of Pripyat. They do not exist there and they must not exist in the video. Read them, then render the scene
as if they had never been drawn.

THE LINE ON THE GROUND GIVES THE DIRECTION OF TRAVEL. He walks in that direction, along that line, across
the open cracked paving. The very first frame is already on that line and already moving along it, and he
keeps going in that direction to the end of the take. It gives the line and the direction; it does not mark
where the shot starts or stops.
THAT DIRECTION PASSES THE WHEEL ON ITS RIGHT — IT DOES NOT GO INTO IT. This matters and it is easy to get
wrong. The direction does not aim at the middle of the wheel and does not aim at the gap between its legs.
It aims a little to the RIGHT of the whole structure, so that if he kept walking he would pass alongside the
wheel and go on past it, leaving it on his left. He never walks into the ring, never walks between the two
legs, never walks underneath the hub and never arrives at the base.
He also does not veer off into the trees. The line threads the open paving BETWEEN the clump of saplings at
the foot of the wheel and the treeline down the right-hand side of the clearing — through the gap, on the
bare slabs, clear of both.

THE LINE IN THE AIR GIVES THE DIRECTION THE CAMERA LOOKS — up and onto the Ferris wheel, from the very
first frame to the very last, never anywhere else.
Read it as the aim, not as a path: he does not walk along it. He walks the ground line while looking in the
air-line direction, and because he is converging past the wheel the two directions stay close together as
he goes.

Do not inherit the camera position of @Image 1 — the camera in this shot is a walking person at eye level,
about 1.7 metres from the ground, moving along the red line.

ENVIRONMENT — matching @Image 1
Season: full summer green, everything overgrown, everything alive.
Sky: deep blue with broken white cumulus, drifting slowly.
Sun: fairly high, strong and clear.
Shadows: crisp shadows of the saplings across the cracked paving, all falling the same way.
Air: light haze thickening with distance, pollen drifting in the bright gaps.
Time: early afternoon.

COLOUR AND GRADE
Neutral daylight white balance, approximately 5600K. No warming filter, no cooling filter, no colour cast
of any kind.
Natural saturation — foliage reads true green, concrete reads neutral grey, the sky reads deep blue, the
gondolas read chalky pale yellow. No teal-and-orange, no bleach bypass, no film emulation LUT, no stylised
grade.
Exposure held constant across the whole shot: mid-tones open and clearly readable, highlights in the sky
retained and never clipped, shadows dark but never crushed to black.
Medium contrast. Bright, clear, natural summer daylight, recorded the way an ordinary camera records it.
NO VIGNETTE. No edge darkening, no corner falloff, no lens shading — even exposure corner to corner.

FIRST FRAME AND SPATIAL BLOCKING
Already walking, and ALREADY LOOKING AT THE FERRIS WHEEL. The shot does not begin on the ground or on the
trees and then find the wheel — it begins with the wheel already in view and already the subject.
THE WHEEL STANDS AT THE CENTRE OF FRAME, about seventy-five metres away, whole, occupying roughly half the
height of the picture, with clear sky above it and the crowns of the saplings crossing its lower third. The
camera is already tipped slightly up along the blue arrow, so the top of the wheel sits comfortably inside
the frame with sky above it, and the near paving sits low in the picture.
Young trees down both sides of the frame. Cracked paving running away from the bottom edge toward the wheel.
Broken cumulus in the blue above.
No empty establishing beat and no held opening frame: the walk is already in progress in the first frame.

FORMAT MODE
ONE single continuous unbroken take. No cuts of any kind — no hard cut, no jump cut, no transition, no
dissolve, no change of camera position, no separate shots. The whole fourteen seconds is one uninterrupted
walk from one camera.

MOTION CONTINUITY — the most important technical requirement
The whole take is ONE evenly flowing movement. The forward travel runs at one constant velocity from the
first frame to the last: it never surges, never hitches, never stalls, never pauses and never repeats a
piece of movement it has already made.
NOTHING JUMPS. No snap, no jolt, no stutter, no hop, no teleport, no sudden reposition, no frame that does
not follow continuously from the frame before it. The camera never returns to a position it has already
left. It never re-frames itself back toward the composition of the reference image, and it never re-anchors
to the reference partway through the shot — the reference sets the look, not a pose to keep coming back to.
There are no waypoints, no marks to hit and no staged beats. The motion is one smooth continuous curve from
beginning to end, not a series of steps between positions.
The approach is monotonic: the distance to the wheel only ever decreases. It never grows, never holds,
never backs off, never resets to its opening size.

OPTICS
62° horizontal field of view — moderately wide, matching the way @Image 1 is photographed, so the whole
twenty-six-metre wheel reads against the sky from a normal walking distance. Deep focus: the near paving and
the top of the wheel are both sharp. No rack focus, no shallow depth of field, no lens flare, no anamorphic
streaks, no fisheye, no barrel distortion at the edges.
THE FOCAL LENGTH NEVER CHANGES. There is no zoom of any kind at any moment. The wheel grows in frame ONLY
because he is walking toward it.

CAMERA PATH — where he walks
He walks along the marked direction of travel, across the open cracked paving, in ONE straight
line that runs PAST the wheel on its right-hand side — not at it, not into it, not between its legs. He
starts about seventy-five metres from it and is about fifty-three metres from it in the last frame —
roughly twenty-two metres of ground covered over the fourteen seconds, at one unbroken walking pace. He does
not reach the wheel and does not stop, and the wheel is still well ahead of him when the take ends.
The line is straight for the whole take. He never curves toward the wheel, never drifts left to line himself
up with it, never steps off the paving into the saplings on either side.
Eye level of a walking adult, about 1.7 metres from the ground.

CAMERA ORIENTATION — where it points
THE CAMERA IS LOCKED ON THE FERRIS WHEEL FOR THE ENTIRE TAKE. This is a LOOK-AT on the wheel, not a fixed
heading: the aim follows the wheel so that it stays at the centre of frame from the first frame to the last.
There is no pan, no sweep, no turn of the head and no glance anywhere else, and there is no moment where
the wheel drifts off centre.
Because he walks PAST the wheel on its right rather than straight at it, the aim swings a very small amount
to the LEFT over the fourteen seconds — a few degrees in total, spread evenly, far too slow to read as a
movement. That drift exists only to keep the wheel centred while he passes it. It is not a pan and it is
not a turn, and it is the only horizontal change in the whole shot.
Vertical: tipped up along the blue arrow, and the tilt rises very slightly as the wheel gets closer and
taller in frame, just enough to keep the top of it inside the picture. This is ONE continuous, barely
perceptible change spread evenly over the whole fourteen seconds. It is NOT a head-lift, NOT a look-up, NOT
a tilt that happens at any one moment — it is only what keeping your eyes on something tall does while you
walk toward it.
Roll: none. The horizon stays level for the whole take. No tilt of the frame at any point.

WHAT GROWS
This is the whole content of the shot: the wheel gets BIGGER, continuously, from the first frame to the
last. At the start it occupies about half the height of the frame. By the end it occupies about three
quarters of it, and the individual gondolas, the rust streaks and the tie rods have become clearly readable
where they were a fine yellow web before. Every second it is slightly larger than the second before, and
the growth never stops and never reverses.
The saplings at the sides of frame slide outward past the edges as he advances. The paving at the bottom of
frame flows toward the camera at one even rate.

CAMERA
The camera is a walking body moving at a slow, calm, unhurried gait, not a rig: gentle vertical rise and
fall on each stride, small lateral sway, organic imperfect correction after every step. It never stabilises
into a glide. No push, no zoom, no dolly, no arc, no orbit. It follows the marked direction in ONE straight line
across the clearing and never turns off it.
The pace is constant from the first frame to the last and is exactly the same unhurried pace as every other
walking shot in this film.

COLLIDER — the camera is a body, not a flying camera
The camera has a physical body attached to it. The body is never seen, but it occupies space and it has
mass, and nothing in the world passes through it.
Do not place anything in the path. Do not invent branches or obstacles in front of the camera — the paving
ahead stays clear, and the vegetation lives at the sides of frame.
But the saplings and the tall weeds grow close to the route, and if one does end up in the path — a branch,
a clump of grass, a young stem — it reacts. It bends, shakes and folds away where the unseen body meets it,
and it recovers a beat later. It is never passed through as if it were not there.
Grass and weeds underfoot bend and flatten where each step lands, then spring back after the foot lifts,
one beat behind the walk. Dust and pollen lift from the ground where the foot lands.
No arms, no hands, no shoulders and no part of him ever enters frame while this happens.

PHYSICS
Weight transfer on every slow step: heel contact, mass settling, toe push-off. Consistent footfall bounce on
hard uneven concrete paving, with a slightly different tilt where a slab has heaved. Wind moves the grass in
travelling waves and the birch leaves on a separate faster frequency. Cloud moves at cloud speed.
NOTHING ON THE FERRIS WHEEL MOVES. The wheel does not rotate by a single degree. The gondolas do not swing,
do not rock, do not sway and do not creak into motion — they are seized solid and have not moved in forty
years, and not one of them shifts at any point in the shot. No cable sways, no metal turns. The machinery
has been seized for forty years and the wind moves only the vegetation. Every apparent change in the wheel
is produced by the walk alone, by perspective.

LIGHTING
Bright summer afternoon daylight. Sun fairly high and strong, sky deep blue behind the wheel with broken
white cumulus, the lemon yellow of the gondolas catching the light where it strikes them and going
grey-green in shade, so the lattice reads as fine rusted lines against bright sky and leaves. Crisp shadows
of the saplings travelling across the paving as he walks. The light level is constant across the whole take
and never drops. No bloom, no lens flare, no god rays, no light with no source in the scene.

AUDIO
Diegetic environmental sound only — footsteps on hard cracked concrete paving and grass, a long steady wind
through heavy summer foliage, one loose piece of metal ticking somewhere high in the structure, sparse
distant bird calls, drifting insects. No creaking ride, no turning machinery, no music, no fairground sound
of any kind. No narration. No voices. Nobody speaks.

STYLE
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic. Documentary
realism of an abandoned place, not a dressed set.
Cinematography: floating immersive camera that lives inside the scene; natural motivated light only;
painterly composed frames, strong silhouettes against the light.
Lighting: bright summer afternoon under broken cumulus, sun fairly high, strong clear key from the sky only.
Color: 60:30:10 — 60% new-growth green, 30% weathered concrete grey and deep sky blue, 10% rust-orange and
faded lemon yellow.
Camera: physical cine lens. 180° shutter motion blur.
Surfaces: material-level realism — corroded lattice steel, chalky flaking paint, rust bleeding from joints,
moss in sheets, heaved cracked concrete, leaf litter.

QUALITY
8K detail. Corroded lattice steel, moss, chalky paint and rust at material level. Clean cloud gradation. No
jitter, no flicker. No warping, no morphing geometry, no melting structure, no text or watermarks anywhere
in frame.

ACTION TIMING
0.0–5.0s — walking across the open paving toward the wheel at an unhurried, calm, leisurely cinematic pace,
the camera on the wheel and staying there. The wheel stands whole at the centre of frame, half the height of
the picture, sky behind it, sapling crowns crossing its base. Grass and weeds at the frame edges run in the
breeze. The wheel itself does not move at all.
5.0–10.0s — still walking, same pace, same line, camera still on the wheel. It is noticeably larger now: the
gondolas have separated into individual boxes and the rust down the legs is readable. Cloud drifts behind
the structure. Nothing else changes.
10.0–14.0s — still walking, same pace, camera still on the wheel. It now fills about three quarters of the
frame height and stands over the view; the near leg reads as heavy rusted lattice, individual gondolas hang
askew and dead still, the hub is a clear rusted casting. The shot ends mid-stride, still walking, still
approaching, with no slowing and no settling into a final composition.

POSITIVE CONSTRAINTS
ONE continuous take. No cuts.
The camera is on the Ferris wheel from the first frame to the last and never looks anywhere else. The wheel
stays at the centre of frame the whole time.
HE WALKS PAST THE WHEEL ON ITS RIGHT. He never walks into the ring, never between the legs, never under the
hub, never up to the base, and never off the paving into the trees on either side. One straight line,
through the gap on the right, all the way to the last frame.
THE WHEEL ONLY EVER GETS BIGGER. It never shrinks, never holds the same size, never resets.
The growth comes from walking, never from a zoom. The focal length is fixed.
The upward tilt is one continuous, barely perceptible rise across the whole take, never a single lift.
The whole wheel stays inside the frame — the top is never cropped off.
The wheel is motionless. Not one gondola moves. Grass and clouds move; the machine does not.
The walk is the same unhurried pace as every other walking shot in this film and never changes.
No people, no animals, no vehicles, no lights, no fences, no barriers, no tourist markers, no graffiti, no
fresh paint, no reconstruction.
The paving is bare weathered concrete with grass in the joints and nothing else on it. No painted line, no
coloured stripe, no marking, no lettering anywhere in the picture.
THE GROUND IS BARE, AND THIS IS THE SINGLE EASIEST THING TO GET WRONG.
The floor of this clearing is plain weathered concrete slabs — grey, cracked, heaved, with grass and moss
growing up through every joint, low weeds creeping in from the edges, patches of dry lichen, and the shadows
of the saplings falling across it. THAT IS EVERYTHING THAT IS ON IT.
There is NO painted line on the ground. No stripe, no band, no streak, no strip of colour, no arrow, no
arrowhead, no chevron, no road marking, no lane marking, no tape, no rope, no path picked out in any colour.
Nothing magenta, nothing pink, nothing red, nothing blue lies on the paving or floats in the air. The
diagram drawn on the reference is not a physical object and does not appear in a single frame.
NO TEXT ANYWHERE IN FRAME. No words, no letters, no Cyrillic, no handwriting, no caption, no label, no
signage, no watermark, no subtitle — nothing written on the ground, on the structure or over the picture.
Photoreal. NON-IP. 16:9. 14s. SFX only. NO CGI. Cinematic. Present tense. Short sentences.
```

**Что проверить в `05B`**

| Симптом | Что делать |
|---|---|
| Колесо не растёт, размер стоит | Главное. Усилить `THE WHEEL ONLY EVER GETS BIGGER` и `every second it is slightly larger than the second before` |
| Растёт зумом, а не шагами | Усилить `THE FOCAL LENGTH NEVER CHANGES`, `grows in frame ONLY because he is walking` |
| Колесо уезжает вбок из центра | Потерян look-at. Усилить `This is a LOOK-AT on the wheel, not a fixed heading` |
| Резкий подъём головы в одном месте | Усилить `NOT a head-lift, NOT a look-up, NOT a tilt that happens at any one moment` |
| Верх колеса срезан | Усилить `The whole wheel stays inside the frame — the top is never cropped off` |
| Он идёт прямо в кольцо, под колесо | Усилить `THE LINE PASSES THE WHEEL ON ITS RIGHT — IT DOES NOT GO INTO IT` и `never walks between the two legs` |
| Свернул в кусты справа | Усилить `threads the open paving BETWEEN the clump of saplings at the foot of the wheel and the treeline` |
| Подворачивает к колесу по ходу | Усилить `The line is straight for the whole take. He never curves toward the wheel` |
| Он идёт по синей стрелке, вбок | Усилить `Read the blue arrow as the aim, not as a path` |
| Колесо крутится, гондолы качаются | Усилить `NOTHING ON THE FERRIS WHEEL MOVES`, `seized solid`, `not one of them shifts` |
| Камера облетает колесо | Усилить `no arc, no orbit`, `ONE straight line` |
| Походка пружинит | Формулировка та же, что в 03A и 05A — там отработала. Не переписывать |
| Дёрганье раз в пару секунд | Блок `MOTION CONTINUITY` стоит для этого; если осталось — вынести его в самый конец и продублировать |
| В кадре стрелки, красная полоса на плитах | Запрет теперь стоит трижды, последний раз отдельным блоком `NO ARROWS IN THE PICTURE` в самом конце. Если всё равно лезет — давать референс без нарисованных стрелок и описывать путь словами |
| Картинка не похожа на фото | `@Image 1` потерял вес. Усилить `THE MAIN REFERENCE. The whole look of this shot comes from here` |

---

