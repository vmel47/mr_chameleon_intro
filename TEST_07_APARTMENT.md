# 07 · КВАРТИРА · 26 сек · один непрерывный кадр

Самая длинная генерация в фильме и единственная, где он заходит внутрь. Лестницу не показываем: мы
застаём его уже на верхней ступеньке, перед своей дверью.

**Хронометраж внутри кадра**

| Секунды | Что |
|---|---|
| 0–6 | Верхняя ступенька, дверь, толчок плечом, вход в прихожую |
| 6–14 | Его комната, **прямо**. Восемь секунд, самая длинная остановка |
| 14–20 | Зал, **слева**. Вросшее дерево |
| 20–26 | Кухня, **справа**. Кадр заканчивается здесь |

`VO-06` на **+8s**, `VO-07` на **+15s**, `VO-08` на **+22s**.

---

# 0 · КАК ЭТО НАЗЫВАЕТСЯ

Ты спрашивал, как называется то, что надо отрисовать. Два разных документа, и нужны оба:

**Floor plan** (поэтажный план) — вид сверху, стены, двери, окна, подписи комнат, метраж. Технический
чертёж. По нему сходится геометрия: где лево, где право, куда открывается дверь, где окно с деревом.
Когда на нём нарисован маршрут камеры, это называется **floor plan with camera blocking**.

**Location reference sheet** — лист с видами самой локации, уже как фотографии. Из него берётся вид.

**План не является референсом для Seedance.** Он нужен мне и тебе, чтобы не путаться и чтобы все картинки
комнат били друг с другом. В видеозапрос он не идёт.

---

# 1 · ПЛАНИРОВКА — по твоему плану

Планировка взята с плана, который ты дал. Прежнюю мою раскладку отменяю.

| Помещение | Где от входа | Метраж |
|---|---|---|
| Прихожая и коридор | сразу за дверью, идёт вдоль низа плана | ~4 м² |
| **Его комната** | **ПРЯМО, центральная** | 10 м² |
| **Зал** | **СЛЕВА**, самая большая | 17 м² |
| **Кухня** | **СПРАВА**, окно на фасад | 7 м² |
| Санузел раздельный | справа, между коридором и кухней | ~3 м² |

**Порядок обхода:** прямо в свою комнату → налево в зал → направо в кухню. Кадр заканчивается на кухне.

**Окно с деревом — в зале**, в самой большой комнате слева. Квартира на третьем этаже: это то самое окно,
в которое на фасаде вошёл толстый сук.

---

# 2 · RESEARCH И ЧТО СТАВИМ В КОМНАТЫ

Research показал, что квартиры Припяти вынесены мародёрами почти подчистую. Но ты прислал фотографии, где
мебель есть, и **правильно — берём твой вариант**, потому что голая коробка не пугает. Компромисс: мебели
немного, она вся сломанная и никем не поставленная, а не расставленная как в интерьере.

**Что дали твои фотографии — это важнее списка предметов.** Там очень конкретный визуальный регистр, и он
советский до мелочи. Стены выкрашены в две зоны: **бирюзово-голубая масляная панель до пояса и извёстка
выше**. Краска сходит крупными закрученными чешуйками, и пол засыпан бледно-голубой и белой крошкой — это
самая узнаваемая фактура на всех трёх снимках. Окна не выбиты: белые деревянные рамы стоят, створки
распахнуты вкривь. По полу и по ступеням идёт яркий зелёный мох. Лестничные перила крашены бирюзой, краска
пузырится, металл проржавел насквозь оранжевыми потёками.

Это и стало блоком `DECAY REGISTER`, он теперь стоит в каждом промпте.

**Про референсы, чтобы больше не путаться.** Фотография — это направление, а не образец для копирования.
Взял из неё регистр: двухцветная покраска, крошка на полу, мох, бирюзовые перила. Не взял состояние
конкретных окон — на одном снимке рама целая, и я по глупости записал это как правило. Так не бывает.
**Окна теперь разные и обязаны спорить между собой:** где-то рама со стеклом, где-то рама без стекла,
где-то проёма нет вообще. Даже в одной комнате соседние окна разные.

**Что где стоит.** Ниже коротко, а в самих промптах это развёрнуто в мелочах — раз референс туда не
вложить, все детали с твоих снимков переписаны словами.

**Его комната, 10 м², прямо.** Угол с двумя окнами, рамы стоят, створки распахнуты вкривь, одна с грязным
стеклом. Обои сошли почти начисто — голая серая штукатурка в разводах. Кровать разобрана временем: спинка
стоит у одной стены, изножье лежит у другой, панцирная сетка провалилась почти до пола, полосатый матрас
сполз и лопнул. Чугунная батарея под окном, краска сошла в ржавчину. Слева остатки стола — шпон отходит
пластами, одной ножки нет, стол сидит на углу; рядом опрокинутый стул, ножками вверх, сиденье выгнило.
Справа шкаф и тумба, дверцы сорваны, полки голые. Паркет ёлочкой разошёлся, местами выломан до битумного
основания. По полу разбухшие книги и тетради, тряпичная игрушка, один детский ботинок, крошка краски.
В сыром углу яркий зелёный мох прямо по паркету.

**Зал, 17 м², слева.** Дерево через проём, крона внутри, под ней паркет ушёл во мхи. Сервант с выбитыми
стёклами. Провалившийся диван. **Старый советский телевизор** на полу: деревянный корпус, скруглённый серый
экран, экран треснул, задняя крышка снята и потроха вынуты.

**Кухня, 7 м², справа.** Стены в две зоны: бирюзовая масляная панель до пояса, извёстка выше, граница
проведена от руки. Бирюза сходит крупными чешуйками. Плита отодвинута от стены и стоит косо, будто её
начали двигать и бросили: белая эмаль сбита до чёрного чугуна, дверца духовки приоткрыта на просевшей
петле, **одна чугунная конфорочная решётка лежит на полу в метре, вверх ногами**. Холодильник в том же
состоянии, дверца распахнута и не закрывается. Эмалированный таз на полу. Стол под окном с рваной клеёнкой,
на подоконнике мутные молочные бутылки. С потолка свисает голый провод от лампы. Пол засыпан бирюзовой и
белой крошкой, поверх лежат длинные рейки от обвалившегося карниза.

**Площадка.** Бирюзовые перила из простых вертикальных прутьев, краска пузырится и отходит, сталь
проржавела насквозь — оранжевые потёки идут по прутьям и пятнают бетон под ними. Поручень протёрт до
голого металла сверху, там где по нему водили рукой. Стены так же в две зоны, краска сходит крупными
закрученными чешуйками. Ступени засыпаны голубой крошкой, по сырым краям идёт яркий мох. Внизу пролёта
брошенная эмалированная ванна.

Источники: [Максим Мирович, квартиры Припяти](https://maxim-nm.livejournal.com/697184.html) ·
[Новини.live, брошенные квартиры](https://lifestyle.novyny.live/ru/story/pustye-i-zhutkie-kak-vygliadiat-zabroshennye-kvartiry-v-pripiati-foto-11518.html) ·
[Photobash, Pripyat interiors](https://www.photobash.org/pripyat-interiors)

---

# 3 · ФАСАД — дерево не отрисовалось

Дом снаружи в целом хорош, надо доделать одно. **Nano Banana Pro**, референс — сгенерированный фасад.

```
Same photograph, same building, same camera, same light, same yard. One change only. Do not move the camera,
do not change the framing, the architecture, the balconies, the windows, the grass, the sky or the time of
day. Everything not named below stays exactly as it is.

GROW A TREE INTO THE BUILDING. Beside the entrance, hard against the façade, stand a MATURE TREE with a
heavy dark trunk and LOWER LIMBS AS THICK AS A LEG — real structural branches, not thin whippy twigs. It
rises up the wall past the first and second floors and its crown reaches the THIRD FLOOR.
ONE THICK LIMB HAS GROWN THROUGH A THIRD-FLOOR WINDOW: the window is an opening with no glass and no frame,
and the limb passes over the sill and continues inside. The foliage is packed into that opening so densely
that the room behind CANNOT BE SEEN AT ALL — no interior, no depth, no black void, just leaves filling the
opening edge to edge.
The crown presses flat against the wall and MASKS SEVERAL NEIGHBOURING WINDOWS AND BALCONIES on the second
and third floors, some hidden completely, some half covered, so a whole part of the façade is unreadable
behind it. Branches lie across balcony railings and push between them.
The trunk is clearly rooted in the overgrown yard, with a visible bend or fork in it so the tree is easy to
recognise again in another shot. It reads as forty years of unchecked growth against a wall.

Everything else unchanged. No people, no animals, no vehicles, no repairs, no text, no watermark.
Photorealistic cinematic film still, matching the detail, grain, light and colour of the reference exactly.
```

---

# 4 · LOCATION SHEET — Soul Cinema, шесть панелей, без референсов

Всё, что на твоём референс-борде, перенесено сюда словами: Soul Cinema картинок не принимает, поэтому
каждая фактура с борда описана вручную — двухзонная покраска, цветочные обои по бирюзовому полю, шкафы,
разобранные до голых корпусов, опрокинутый стул, рваные занавески, чугунные батареи, крашеные перила,
дерево, выросшее внутри комнаты.

**Модель:** Higgsfield **Soul Cinema** · 16:9 · 2k · референсов нет
**Тег результата:** `@sheet_MC_home`

```
Six photographs of one and the same place, arranged as a clean grid on a single page — a film location sheet
for a five-storey Soviet apartment block in Pripyat and for one flat inside it, forty years after the city
was evacuated. Top row: three panels side by side. Bottom row: three panels side by side. Each panel is a
photograph with a thin neutral border and a small plain English caption beneath it.

THIS IS ONE PLACE SEEN SIX TIMES, NOT SIX PLACES. One building, one flat, one afternoon. The same weather,
the same light, the same palette, the same wall colours, the same wallpaper pattern, the same floors and the
same degree of decay carry over from panel to panel. A viewer must be able to walk from panel one to panel
six without ever doubting it is the same address.

THE LAYOUT OF THE FLAT, WHICH THE PANELS MUST AGREE WITH. The front door opens into a short hallway that
runs across the flat. STRAIGHT AHEAD from the front door is HIS ROOM, ten square metres, one window.
On the LEFT is the LIVING ROOM, seventeen square metres, the largest room, two windows and a recessed
loggia. On the RIGHT is the KITCHEN, seven square metres, one window, and past it a bathroom and a separate
toilet behind two narrow doors. Nothing in any panel may contradict this arrangement.

THE MATERIAL OF THIS RUIN — the same in every interior panel.
Walls are painted the Soviet way, in two zones: a band of dull TURQUOISE or blue oil paint from the floor to
just above waist height, chalky white lime above it, and a straight hand-painted line between them. That
paint has failed everywhere — it lifts in large curled flakes, some still clinging at one edge, most already
fallen — leaving pale grey plaster showing through in irregular islands.
Where wallpaper survives it is a small faded floral print on a pale turquoise or grey ground, hanging away
in long torn sheets with yellowed newspaper and bare render beneath.
Ceilings have lost their whitewash in patches to the bare concrete slab, with black damp streaks running
from every window and every corner.
Floors: herringbone parquet in the rooms, lifted and sprung apart with patches of blocks missing down to the
dark bitumen bedding; buckled linoleum in the kitchen and hallway, lifting in bubbles and torn back in
strips. Over all of it a thick fall of plaster and pale paint flakes, drifted into the corners, with long
wooden laths lying where the ceiling trim came down.
Furniture survives only as carcasses: brown veneered Soviet wardrobes and wall units with their doors gone
and their shelves fallen through, an empty drawer sitting on the floor a metre from the desk it came out of,
a red-brown wooden chair lying on its side in the debris with the seat rotted out.
Under every window a ribbed cast-iron radiator, still on its brackets, its paint gone to rust down every rib.
At the side of some windows a curtain rotted to hanging threads.
GREEN IS COMING IN: bright moss across the floor in the damp corners and under the windows, grass rooted in
the parquet, creeper over the sills.

PANEL 1, captioned BLOCK — EXTERIOR. A three-quarter wide view of the building from the overgrown yard,
camera at the eye level of a person standing in the grass, the façade running diagonally away toward a
vanishing point in the right third, never square on, never a flat elevation. A five-storey precast concrete
panel block, coarse pale grey-white render, black rain streaks down every panel joint, green algae in the
wet runs. THE BALCONIES ARE MIXED AND IRREGULAR: continuous vertical columns recessed into the wall, one per
stairwell, and roughly half of them enclosed by the residents themselves in mismatched timber and thin metal
glazing frames, panes of different sizes, some bays filled with flat painted sheet instead of glass,
everything slightly out of true; the rest open with plain rusted railings. Never a pattern, never a tidy
row. An entrance about a third of the way along, NOT at the corner: a plain doorway under a flat concrete
canopy carried on two square posts, worn steps, a faded number plate. The yard swallowed by long green grass
and birch saplings, a rusted steel swing frame standing half buried in the growth, a trodden path leading to
the entrance.
AND ONE TREE: a mature tree hard against the façade beside that entrance, heavy dark trunk, lower limbs as
thick as a leg, grown up the wall to the THIRD FLOOR, its crown pressed flat against the concrete and
masking several windows, and ONE THICK LIMB PASSING STRAIGHT INTO A THIRD-FLOOR WINDOW OPENING, the foliage
packed into it so the room behind cannot be seen. Make it distinct and memorable: it appears again inside.

PANEL 2, captioned LANDING. A concrete stair landing on the third floor, camera at eye level looking at the
door of the flat, a flight of bare concrete steps running up beside it with their nosings crumbled to the
aggregate. A steel balustrade of plain vertical bars under a flat handrail, PAINTED TURQUOISE, the paint
blistered and lifting and the steel rusted through beneath, so the balustrade reads as bands of pale
turquoise broken by long orange-brown runs of rust that bleed down the bars and stain the concrete under
them; the handrail worn bare and rusted along its top where hands used to run. The walls in the same two
zones, coming away in large curled flakes, and the treads and the floor covered in the fallen pale blue and
white chips. Bright green moss along the damp edges of the steps. A chipped white enamel bath abandoned at
the bottom of the flight.
THE DOOR OF THE FLAT, closed: a Soviet padded entrance door, its brown vinyl covering split and hanging in
strips off the boards beneath, the upholstery studs half gone and the rest rusted, the timber frame swollen
out of square so the door no longer sits flush in its rebate. A dead bell button, a small metal flat number.
Cold grey light from a broken stairwell window out of frame: the darkest panel of the six.

PANEL 3, captioned HALLWAY. Standing just inside the front door, camera at eye level, looking down the short
narrow hallway with all three doorways visible at once. STRAIGHT AHEAD an open doorway into a small bedroom
with daylight beyond it. ON THE LEFT an open doorway into the largest room, the brightest of the three, with
green leaves visible inside it. ON THE RIGHT an open doorway into a small kitchen, and past it two narrow
doors, one hanging open on a single hinge. A wooden coat rail still screwed to the wall with nothing on it.
A fallen shoe rack. A built-in cupboard above the front door, its doors sprung open and empty. Buckled
linoleum underfoot beneath a drift of plaster and paint flakes. The hallway has no window of its own and all
its light is borrowed, so the three doorways read as three bright openings in a dark space.

PANEL 4, captioned HIS ROOM. The small bedroom straight ahead from the front door, about ten square metres,
seen from its doorway at eye level, the whole room readable from wall to wall. A window in the outer wall,
white-painted wooden frame still in place, one leaf swung open at an angle and one still holding a dirty
pane, a curtain rotted to threads at the side, a ribbed cast-iron radiator beneath it, green tree crowns
outside and hard afternoon light coming through.
UNDER THE WINDOW A BED TAKEN APART BY TIME: a dark red-brown lacquered headboard panel standing against one
wall with the varnish crazed and lifting, its matching footboard fallen flat against another wall, and
between them an iron frame whose sprung wire base sags almost to the floor with the coils showing, a filthy
striped ticking mattress slipped half off it and split open.
ON ONE SIDE the remains of a desk: chipboard with the veneer lifting off in sheets, one leg gone so it sits
down on its corner, drawers pulled out, one of them standing empty on the floor a metre away. A red-brown
wooden chair lying on its side in the debris, the seat rotted out of it. ON THE OTHER SIDE a brown veneered
wardrobe broken down to a bare carcass, doors gone, shelves fallen through and leaning against it.
ON THE FLOOR, among the fallen plaster and laths: swollen books and school exercise books, an old cloth toy
gone grey and shapeless, a single child's shoe. Bright green moss has taken the damp corner in a thick vivid
patch, growing over the parquet and up the base of the wall.
Daylight from the single window rakes across the room and dies quickly in the corners. Dust hangs in it.

PANEL 5, captioned LIVING ROOM. The largest room, on the left of the hallway, about seventeen square metres,
seen from its doorway at eye level, AND A LIVING TREE HAS GROWN INSIDE IT.
One window is completely gone — no glass, no frame, no sash, only the raw opening — and a THICK TREE LIMB,
as thick as a leg, runs in through it, over the sill and down into the room. THE TRUNK AND CROWN STAND
INSIDE THE ROOM AND FILL NEARLY HALF ITS VOLUME: heavy green summer foliage against the ruined walls,
branches spread across the ceiling and pressed into the corner, daylight coming through the leaves and
falling as broken green light across the floor. The bark is real bark, dark and textured. This is a full
grown tree standing in a domestic room, and it must read as completely real.
The second window of the room still has its white-painted frame with one dirty pane in it, untouched, which
makes the missing one worse. A ribbed cast-iron radiator under it.
DIRECTLY BENEATH THE BRANCHES a collapsed sofa, its springs through the fabric and the fabric gone to grey
felt, fallen leaves and debris piled on the seat. Against the side wall a Soviet sideboard broken down to
its carcass, the glass smashed out of the upper doors, the shelves fallen through. AN OLD SOVIET TELEVISION
on the floor beside it: a boxy wooden-cased set with a round-cornered grey screen, the screen cracked, the
back panel off and the guts pulled out, dust thick on top of it. A fallen curtain rail.
The last of the floral wallpaper hangs off in long tongues, and where it has gone the bare grey render shows
with black water streaks running from ceiling to floor. THE PARQUET IS COMING APART and from under the tree
moss and grass spread out across it in a thick bright green carpet, rooted between the blocks. The loggia
doorway beyond, its glazing gone, full of blown leaves.
THIS IS THE SAME TREE AS IN PANEL 1 — same species, same leaf, same bark, same thickness of limb, seen now
from inside the third-floor window it entered. The light in here is the brightest in the flat and it is
green, filtered through the leaves. This is the strongest image on the sheet.

PANEL 6, captioned KITCHEN. The small kitchen on the right of the hallway, about seven square metres, seen
from its doorway at eye level. A window in the outer wall, white wooden frame still in place but the glass
gone from most of it, the empty sashes standing open at an angle, green outside, a ribbed cast-iron radiator
beneath it.
THE TWO-ZONE PAINTING IS AT ITS STRONGEST IN THIS ROOM: the band of dull turquoise oil paint to just above
waist height and chalky white lime above, the line between them straight and hand-painted, the turquoise
failed in wide patches and lifting in big curled flakes down to the grey plaster. A small faded red plate
still fixed to the wall at head height.
THE GAS STOVE STANDS PULLED OUT FROM THE WALL AND SLIGHTLY ASKEW, standing free on the floor as if someone
started to move it and gave up: a white enamel Soviet cooker with four burners and an oven door, the enamel
chipped through to black iron along every edge and streaked with rust, the oven door hanging half open on a
sagging hinge, the hob furred with dirt. ONE HEAVY CAST-IRON BURNER GRATE HAS COME OFF AND LIES ON THE FLOOR
a metre away, upside down.
A REFRIGERATOR beside it in the same state: small and rounded, its white enamel gone yellow and
rust-streaked, the door hanging wide open and unable to close, the inside black with mould, the shelves bare
and the rubber seal perished and hanging. A wall cupboard with its doors sprung open above an empty worktop.
A small table under the window with a torn oilcloth cover, a chipped white enamel basin sitting on the floor
beside it, and on the sill two or three cloudy glass milk bottles with dried residue caked in the bottom. A
bare wire hanging from a hole in the ceiling where the light was.
THE FLOOR IS BURIED under lifting linoleum, paint flakes, plaster and fallen laths. GREEN GROWTH HAS COME IN
THROUGH THE WINDOW: creeper over the sill, down the wall and starting across the worktop.

OUR WEATHER AND OUR COLOUR — the same in every panel, and not negotiable.
A bright late-spring afternoon, everything outside in full new green, the sky pale blue with soft broken
white cumulus spread evenly across it, the sun fairly high and a little behind the building so a warm rim
sits on the roof edge and the tops of the grass. Indoors, daylight only, entering through the windows, soft
and directional, with fine dust hanging in it. No artificial light anywhere, nothing switched on, no lamp,
no torch. Nothing wintry: no bare branches, no dead grass, no flat grey overcast, no cold blue cast.
Neutral daylight white balance around 5600K, natural saturation, medium contrast, even exposure corner to
corner, no vignette.
Palette: 60% new-growth green and grey-green damp plaster, 30% weathered concrete grey and brown rotted
timber, 10% turquoise flaking paint and rust-orange oxidised metal.

WINDOWS ARE MIXED, NEVER ALL THE SAME — some frames complete with dirty glass, some frames with the glass
gone, some bare openings with the frame torn out altogether. In one room a window can be whole while the one
beside it is empty. Decide each opening separately and let them disagree with each other.

Decay is heavy but STRUCTURALLY WHOLE: floors, ceilings and walls intact, nothing collapsed, no violence, no
smashed-up chaos, no fire damage. Nothing has been repaired and nothing has been vandalised — this is only
what forty years of rain, frost, damp, growth and quiet looting left behind. No graffiti, no fresh paint, no
new timber, no boarding, no tools, no barriers, no signage, no tourist markers.
Empty deserted building, still air, no people, no animals, no vehicles, no working lights.

PHOTOREALISM IS THE POINT. These are photographs of a real place that really exists, taken on a real camera
on a real afternoon — documentary realism, not concept art and not a set. Crisp natural detail, real
material behaviour in every surface: corroded steel, chalky flaking oil paint, swollen and delaminating
chipboard, damp plaster, moss, dust in the light. Minimal fine grain, soft cinematic falloff. No
illustration, no painting, no render, no 3D, no CGI, no game-engine look, no plastic surfaces, no smooth
digital cleanliness. No watermark, no logo and no text anywhere on the page except the six captions.
```

**Что проверить**

| Симптом | Что делать |
|---|---|
| Один кадр вместо шести | Soul плох на сетках. Усилить `Top row: three panels. Bottom row: three panels`; если не берёт — идти разделом `5`, отдельными промптами |
| Панели из разных квартир | Усилить `THIS IS ONE PLACE SEEN SIX TIMES` и перечень того, что переносится между панелями |
| Планировка не сходится | Усилить `Nothing in any panel may contradict this arrangement` |
| Серо и зимне | Усилить `OUR WEATHER AND OUR COLOUR ... not negotiable`, `nothing wintry` |
| Похоже на рендер или концепт-арт | Усилить блок `PHOTOREALISM IS THE POINT`, особенно `no plastic surfaces, no smooth digital cleanliness` |
| Дерева внутри нет или оно жалкое | Усилить `THE TRUNK AND CROWN STAND INSIDE THE ROOM AND FILL NEARLY HALF ITS VOLUME` |
| Дерево снаружи и внутри разное | Усилить `THIS IS THE SAME TREE AS IN PANEL 1` |
| Нет двухзонной покраски | Усилить `THE MATERIAL OF THIS RUIN` целиком |
| Комнаты пустые | Усилить списки предметов в панелях 4, 5, 6 |
| Обвалы перекрытий | Усилить `STRUCTURALLY WHOLE ... nothing collapsed` |

---

# 4B · ЛИСТ ПО РЕФЕРЕНС-БОРДУ — GPT Image 2

**Два референса, в этом порядке:**
`@Image 1` — твой референс-борд, коллаж из настоящих фотографий припятских квартир и подъездов
`@Image 2` — план квартиры

**Что на борде и почему это важно назвать.** Модель видит коллаж как одну картинку и без указаний
попытается воспроизвести коллаж. Поэтому в промпте прямо перечислено, что оттуда собирать: две лестницы —
одна с бирюзовыми стенами, другая с красно-оранжевыми перилами; комнаты с цветочными обоями по бирюзовому
полю; двухзонная покраска стен; разобранные шкафы и стенки, оставленные корпусами; опрокинутый стул на
цветочных обоях; окна с рваными занавесками и чугунными батареями под ними; фасад пятиэтажки с качелями во
дворе; **и два кадра, где дерево выросло прямо внутри комнаты** — это ровно наш зал, и на них надо
опереться.

**Модель:** GPT Image 2 · 16:9 · quality high
**Тег результата:** `@sheet_MC_home`

```
Two references, two separate jobs. Read this first and obey it strictly.

@Image 1 IS A REFERENCE BOARD — a collage of many separate real photographs of abandoned Soviet apartment
blocks in Pripyat, pasted onto one page. IT IS A SOURCE OF MATERIAL, NOT A LAYOUT. Do not reproduce the
collage. Do not copy any of its frames. Do not output pictures of the same rooms from the same angles. Take
from it the MATERIAL TRUTH of this kind of ruin and then build new rooms with new camera positions from the
descriptions below.
What to harvest from it, specifically:
— the two-zone Soviet wall painting: a band of turquoise or blue oil paint from the floor to just above
waist height, chalky white lime above it, a straight hand-painted line between, the paint failing in wide
patches and lifting in large curled flakes down to grey plaster;
— the wallpaper: small faded floral prints on pale turquoise and grey grounds, hanging away in torn sheets;
— the stairwells: bare concrete steps, walls in blue and turquoise peeling everywhere, and painted steel
balustrades of plain vertical bars, some turquoise and some orange-red, the paint blistered and the steel
rusting through;
— the furniture as it survives: brown veneered Soviet wardrobes and wall-units broken down to bare
carcasses with their doors and shelves fallen out, a red-brown wooden chair lying on its side on a floor of
fallen plaster, an empty drawer sitting on the boards;
— the windows: white-painted wooden frames, some with dirty glass, some empty, rotted curtains hanging at
the side, a ribbed cast-iron radiator under every one;
— the floors: buckled linoleum and lifting parquet, everything under a thick fall of plaster and paint
flakes;
— AND THE MOST IMPORTANT ONE: the frames in which A LIVING TREE HAS GROWN INSIDE A ROOM — a real trunk and
crown standing in a domestic interior, green foliage against ruined walls, growth spreading over the floor.
That is exactly what the LIVING ROOM panel must be.

@Image 2 IS A FLOOR PLAN — A TECHNICAL DRAWING, NOT A PICTURE TO RENDER. Never reproduce it, never draw a
plan, never draw lines or labels, never put it in a panel. Use it for ONE thing: the geometry of the flat.
The front door opens into a short hallway running across the flat. STRAIGHT AHEAD is HIS ROOM, ten square
metres. On the LEFT is the LIVING ROOM, seventeen square metres, the largest, with a loggia. On the RIGHT is
the KITCHEN, seven square metres, and past it a bathroom and a separate toilet.

NOW BUILD THE SHEET.
Six photographs of one and the same place, arranged as a clean grid on a single page — a film location sheet
for a five-storey Soviet apartment block in Pripyat and for one flat inside it, forty years after the city
was evacuated. Top row: three panels side by side. Bottom row: three panels side by side. Each panel is a
photograph with a thin neutral border and a small plain English caption beneath it.
THIS IS ONE PLACE SEEN SIX TIMES, NOT SIX PLACES. One building, one flat, one afternoon, the same weather,
the same light, the same palette, the same degree of decay in every panel. A viewer must be able to walk
from panel one to panel six without ever doubting it is the same address. The wall colours, the wallpaper
pattern, the floor and the quality of light carry over from panel to panel.

PANEL 1, captioned BLOCK — EXTERIOR: a three-quarter wide view of the building from the overgrown yard,
camera at the eye level of a person standing in the grass, the façade running diagonally away toward a
vanishing point in the right third, never square on. A five-storey precast concrete panel block, coarse pale
grey-white render, black rain streaks down every panel joint, green algae in the wet runs. THE BALCONIES ARE
MIXED AND IRREGULAR: continuous vertical columns recessed into the wall, one per stairwell, roughly half of
them enclosed by the residents themselves in mismatched timber and thin metal glazing frames, panes of
different sizes, some bays filled with flat painted sheet instead of glass, everything slightly out of true;
the rest open with plain rusted railings. Never a pattern, never a tidy row. Windows mixed the same way.
An entrance about a third of the way along, NOT at the corner: a plain doorway under a flat concrete canopy
on two square posts, worn steps, a faded number plate. The yard swallowed by long green grass and birch
saplings, a rusted swing frame standing half buried in it, a trodden path to the entrance.
AND ONE TREE: a mature tree hard against the façade beside that entrance, heavy dark trunk, lower limbs as
thick as a leg, grown up the wall to the THIRD FLOOR, crown pressed flat against the concrete and masking
several windows, and ONE THICK LIMB PASSING STRAIGHT INTO A THIRD-FLOOR WINDOW OPENING with foliage packed
in so the room behind cannot be seen. Distinct and memorable: it appears again inside.

PANEL 2, captioned LANDING: a concrete stair landing on the third floor, camera at eye level looking at the
door of the flat, a flight of bare concrete steps running up beside it with their nosings crumbled to the
aggregate. A steel balustrade of plain vertical bars under a flat handrail, painted TURQUOISE, the paint
blistered and lifting and the steel rusted through beneath, so it reads as bands of pale turquoise broken by
long orange-brown runs of rust bleeding down the bars and staining the concrete under them; the handrail
worn bare on top where hands used to run. Walls in two zones, blue oil paint to waist height and lime
whitewash above, both coming away in large curled flakes, the treads and floor covered in the fallen pale
blue and white chips. Bright green moss on the damp edges of the steps.
THE DOOR OF THE FLAT, closed: a Soviet padded entrance door, its brown vinyl covering split and hanging in
strips off the boards beneath, upholstery studs half gone and rusted, the timber frame swollen out of square
so the door no longer sits flush. A dead bell button, a small metal flat number. Cold grey light from a
broken stairwell window: the darkest panel of the six.

PANEL 3, captioned HALLWAY: standing just inside the front door, camera at eye level, looking down a short
narrow hallway with all three doorways visible at once. STRAIGHT AHEAD an open doorway into a small bedroom
with daylight beyond. ON THE LEFT an open doorway into the largest room, the brightest of the three, green
leaves visible inside it. ON THE RIGHT an open doorway into a small kitchen, and past it two narrow doors,
one hanging open. A wooden coat rail still screwed to the wall with nothing on it. A fallen shoe rack. A
built-in cupboard above the front door, its doors sprung open and empty. Buckled linoleum underfoot beneath
a drift of plaster and pale paint flakes. The hallway has no window of its own, so the three doorways read
as three bright openings in a dark space.

PANEL 4, captioned HIS ROOM: the small bedroom straight ahead from the front door, seen from its doorway at
eye level, about ten square metres. A window in the outer wall, white-painted wooden frame still in place,
one leaf swung open and one holding a dirty pane, a rotted curtain hanging at the side, a ribbed cast-iron
radiator beneath it with its paint gone to rust, green tree crowns outside.
Walls in the small faded floral wallpaper, hanging away in long torn sheets with yellowed newspaper and bare
grey render beneath, and a band of turquoise oil paint surviving along the bottom.
UNDER THE WINDOW A BED TAKEN APART BY TIME: a dark red-brown lacquered headboard panel standing against one
wall with the varnish crazed and lifting, its matching footboard fallen flat against another, and between
them an iron frame whose sprung wire base sags almost to the floor with the coils showing, a filthy striped
mattress slipped half off it and split open.
ON ONE SIDE the remains of a desk, chipboard with the veneer lifting off in sheets, one leg gone so it sits
down on its corner, drawers pulled out — one of them sitting empty on the floor a metre away. A red-brown
wooden chair lying on its side in the debris, the seat rotted out. ON THE OTHER SIDE a brown veneered
wardrobe broken down to a bare carcass, doors gone, shelves fallen out and leaning against it.
THE FLOOR is herringbone parquet coming apart, patches of blocks gone down to the dark bedding, and over it
fallen laths, swollen books and school exercise books, an old cloth toy gone grey and shapeless, a single
child's shoe, and a thick fall of plaster and paint flakes. Bright green moss in the damp corner.

PANEL 5, captioned LIVING ROOM: the largest room, on the left of the hallway, about seventeen square metres,
seen from its doorway at eye level, AND A LIVING TREE HAS GROWN INSIDE IT — exactly as in the reference
frames where a tree stands in a domestic interior. One window is completely gone, no glass, no frame, no
sash, only the raw opening, and a THICK TREE LIMB as thick as a leg runs in through it, over the sill, down
into the room. THE TRUNK AND CROWN STAND INSIDE THE ROOM AND FILL NEARLY HALF ITS VOLUME: heavy green summer
foliage against the ruined walls, branches spread across the ceiling and pressed into the corner, daylight
through the leaves falling as broken green light on the floor. The bark is real bark, dark and textured.
The second window still has its white frame with one dirty pane in it, untouched, which makes the missing
one worse. A ribbed cast-iron radiator under it.
AROUND THE TREE: a Soviet sideboard broken down to its carcass against the side wall, glass smashed out of
the upper doors, shelves fallen through. A collapsed sofa sitting directly beneath the branches, its springs
through the fabric and the fabric gone to grey felt, debris and leaves piled on the seat. AN OLD SOVIET
TELEVISION on the floor beside it, a boxy wooden-cased set with a round-cornered grey screen, the screen
cracked, the back panel off and the guts pulled out, dust thick on top.
The last of the floral wallpaper hangs off in long tongues, black water streaks running ceiling to floor
where it has gone. THE PARQUET IS COMING APART and from under the tree moss and grass spread across it in a
thick bright green carpet, rooted between the blocks. The loggia doorway beyond, glazing gone, full of blown
leaves.
THIS IS THE SAME TREE AS IN PANEL 1 — same species, same leaf, same bark, same thickness of limb, seen now
from inside the third-floor window it entered. This is the strongest image on the sheet.

PANEL 6, captioned KITCHEN: the small kitchen on the right of the hallway, about seven square metres, seen
from its doorway at eye level. A window in the outer wall, white wooden frame in place but the glass gone
from most of it, the empty sashes standing open at an angle, green beyond, a ribbed cast-iron radiator under
it.
THE WALLS IN TWO ZONES, and this is the strongest thing in the room: a band of dull TURQUOISE oil paint from
the floor to just above waist height, chalky white lime above, the line between them straight and
hand-painted, the turquoise failed in wide patches and lifting in big curled flakes down to the grey
plaster. A small faded red plate still fixed to the wall at head height.
THE GAS STOVE STANDS PULLED OUT FROM THE WALL AND SLIGHTLY ASKEW, free on the floor as if someone started to
move it and gave up: a white enamel Soviet cooker, four burners and an oven door, the enamel chipped through
to black iron along every edge and streaked with rust, the oven door hanging half open on a sagging hinge.
ONE HEAVY CAST-IRON BURNER GRATE HAS COME OFF AND LIES ON THE FLOOR a metre away, upside down.
A REFRIGERATOR beside it in the same state: small, rounded, white enamel gone yellow and rust-streaked, its
door hanging wide open and unable to close, the inside black with mould, shelves bare, the rubber seal
perished. A wall cupboard with its doors sprung open above an empty worktop. A small table under the window
with a torn oilcloth, a chipped white enamel basin on the floor beside it, and on the sill two or three
cloudy glass milk bottles with dried residue caked in the bottom. A bare wire hanging from a hole in the
ceiling where the light was.
THE FLOOR IS BURIED: buckled linoleum lifting in bubbles and torn back in strips, and over it a thick
scatter of fallen turquoise and white paint flakes, plaster and long wooden laths. GREEN GROWTH HAS COME IN
THROUGH THE WINDOW: creeper over the sill, down the wall, starting across the worktop.

ACROSS ALL SIX PANELS — OUR WEATHER AND OUR COLOUR, WHICH IS NOT THE WEATHER IN THE REFERENCE BOARD.
Bright late-spring afternoon, everything outside in full new green, sky pale blue with soft broken white
cumulus, sun fairly high and a little behind the building. Indoors, daylight only, entering through the
windows, soft and directional, fine dust hanging in it. No artificial light anywhere, nothing switched on,
no lamp, no torch. Nothing grey and wintry, no bare branches, no flat overcast.
WINDOWS ARE MIXED, NEVER ALL THE SAME — some frames complete with dirty glass, some frames with the glass
gone, some bare openings with the frame torn out. In one room a window can be whole while the one beside it
is empty. Decide each opening separately and let them disagree with each other.
Decay: heavy but STRUCTURALLY WHOLE — floors, ceilings and walls intact, nothing collapsed, no violence, no
smashed-up chaos, no fire damage. Ceilings have lost their whitewash in patches to the bare slab with black
damp streaks. Nothing repaired and nothing vandalised: only forty years of rain, frost, damp, growth and
quiet looting. No graffiti, no fresh paint, no new timber, no boarding, no tools, no barriers, no signage.
Emptiness: empty deserted building, still air, no people, no animals, no vehicles, no working lights.
Palette: 60% new-growth green and grey-green damp plaster, 30% weathered concrete grey and brown rotted
timber, 10% turquoise flaking paint and rust-orange oxidised metal.
Neutral daylight white balance around 5600K, natural saturation, medium contrast, even exposure corner to
corner, no vignette.

Photorealistic cinematic film stills of a real abandoned building, documentary realism, crisp natural detail,
minimal fine grain, soft cinematic falloff. No illustration, no painting, no render, no 3D, no CGI, no
game-engine look. No watermark, no logo and no text anywhere on the page except the six captions.
```

**Что проверить**

| Симптом | Что делать |
|---|---|
| Выдал коллаж, повторил референс-борд | Главное. Усилить `IT IS A SOURCE OF MATERIAL, NOT A LAYOUT. Do not reproduce the collage` |
| Панели из разных квартир | Усилить `THIS IS ONE PLACE SEEN SIX TIMES` и `the wall colours, the wallpaper pattern, the floor and the quality of light carry over` |
| Серо и зимне, как на части фотографий борда | Усилить `OUR WEATHER AND OUR COLOUR, WHICH IS NOT THE WEATHER IN THE REFERENCE BOARD` |
| Дерева внутри нет или оно жалкое | Усилить `THE TRUNK AND CROWN STAND INSIDE THE ROOM AND FILL NEARLY HALF ITS VOLUME` и ссылку на кадры борда с деревом |
| Дерево снаружи и внутри разное | Усилить `THIS IS THE SAME TREE AS IN PANEL 1` |
| В панели нарисован план | Усилить `never put it in a panel` |
| Один кадр вместо шести | Усилить `Top row: three panels. Bottom row: three panels` |
| Обвалы перекрытий | Усилить `STRUCTURALLY WHOLE ... nothing collapsed` |

---

# 5 · ЗАПАСНОЙ ПУТЬ — те же кадры по отдельности

Референсов Soul Cinema не принимает, поэтому связность держится **дословным повтором**: в каждом промпте
стоит один и тот же блок `CONSISTENCY LOCK`, слово в слово, вместе с `DECAY REGISTER` внутри него. Ничего в
нём между промптами не менять, даже порядок слов — буквальное совпадение и есть механизм.

Второй приём — `SPATIAL CONTINUITY`: что за спиной камеры и что видно в проёмах. Это то, что позволит потом
собрать непрерывный проход.

**Модель:** Higgsfield **Soul Cinema** · 16:9 · 2k · референсов нет
**Планировка:** вход снизу, коридор поперёк; **прямо — комната 10 м²**, **слева — зал 17 м² с лоджией**,
**справа — кухня 7 м²**.

---

## 4.1 · ПЛОЩАДКА И ДВЕРЬ · `@loc_MC_home_landing`

```
Eye-level wide shot on a concrete stair landing inside an abandoned Soviet apartment block in Pripyat,
camera about 1.7 metres from the floor, standing on the top step and looking straight at the door of the
flat, the door filling the middle of frame.

THE LANDING: a concrete stair landing on the third floor. A Soviet padded entrance door, closed, its brown
vinyl covering split and hanging in strips off the boards beneath, the upholstery studs half gone and the
rest rusted, the timber frame swollen out of square so the door no longer sits flush in its rebate. A dead
bell button beside it, a small metal flat number screwed to the door.
THE STAIRS AND THE BALUSTRADE, and this is what makes the shot: a flight of bare concrete steps with their
nosings crumbled away to the aggregate, and along them a steel balustrade of plain vertical bars under a
flat handrail, all of it PAINTED TURQUOISE. That paint has blistered and lifted everywhere and the steel
beneath has rusted through, so the whole balustrade reads as bands of pale turquoise broken by long
orange-brown runs of rust that bleed down the bars and stain the concrete under them. The handrail is worn
bare and rusted along its top where hands used to run.
THE WALLS carry the same two-zone Soviet painting: a band of blue-grey oil paint from the floor to waist
height, chalky lime whitewash above, and both are coming off in LARGE CURLED FLAKES — some still clinging at
one edge, most already fallen — leaving pale grey plaster showing through in irregular islands.
THE STEPS AND THE FLOOR ARE COVERED IN THOSE FALLEN FLAKES, a scatter of pale blue and white chips lying
thick along every tread and drifted into the corners. BRIGHT GREEN MOSS has taken the damp edges of the
steps and the foot of the wall, growing in the water that runs down. A chipped white enamel bath or basin
lies abandoned on the floor at the bottom of the flight.
The light is cold and grey, coming from a broken stairwell window out of frame, and the top of the flight
goes into darkness: this is the darkest place in the film.

SPATIAL CONTINUITY: this is the third-floor landing, the stairs come up behind the camera. Beyond this door
lies the flat — a short hallway with three doorways off it — but the door is shut and none of it is visible.

CONSISTENCY LOCK — identical in every room of this apartment.
The building is a Soviet 1-464 series precast concrete panel block in Pripyat, abandoned forty years. This
flat is on the third floor. Bright late-spring afternoon outside, everything in full new green. Indoors,
daylight only, entering through the windows, soft and directional, fine dust hanging in it. No artificial
light anywhere, nothing switched on, no lamp, no torch.
DECAY REGISTER — the exact look of ruin in this flat, in every room.
Walls are painted in the Soviet two-tone way: a band of oil paint from the floor to waist height in dull
TURQUOISE-BLUE or green-blue, and lime whitewash above it. That paint has failed everywhere — it lifts in
large curled flakes, some still clinging, most fallen, and the floor is covered in a drift of pale blue and
white paint chips and plaster flakes, thick in the corners. Where the wallpaper survives it is a small faded
seventies floral print, hanging away in long tongues with yellowed newspaper beneath.
Ceilings have lost their whitewash in patches down to the bare concrete slab, with black damp streaks
running from every window and every corner.
Floors: herringbone parquet in the rooms, lifted and sprung apart, sheets of it missing; buckled linoleum in
the kitchen and hallway. Loose boards, torn strips of lino and fallen laths lie about.
WINDOWS ARE MIXED, NEVER ALL THE SAME. Room to room and opening to opening they differ: some still have
their white-painted wooden frames complete with dirty glass in them; some have the frame but the glass gone,
the sashes hanging open at odd angles or swung out on a single hinge; some are bare openings with the frame
torn out altogether and nothing but sky and leaves in them. In one room a window can be whole while the one
beside it is empty. The paint on every surviving frame is blistered off to bare grey timber. Decide each
opening separately and let them disagree with each other.
GREEN IS COMING IN: bright moss growing across the floor in the damp corners and under the windows, grass
and weeds rooted in the parquet, creeper over the sills.
Everything is soft, faded and quiet — no violence, no smashed-up chaos, no fire damage, no graffiti, no
fresh paint, no new timber, no boarding, no tools, no signage. Only forty years of rain, frost, damp,
growth and quiet looting. Heavy decay but STRUCTURALLY WHOLE: floors, ceilings and walls intact, nothing
collapsed.
Empty deserted interior, still air, no people, no animals, no vehicles, no working lights.
Palette: 60% grey-green damp plaster and faded wallpaper, 30% brown rotted timber and turquoise-blue flaking
paint, 10% living green from the growth coming in and rust-orange from the metal.
Neutral daylight white balance around 5600K, natural saturation, medium contrast, even exposure corner to
corner, no vignette.
Rule of thirds. Photorealistic cinematic film still of a real abandoned building, documentary realism, crisp
natural detail, minimal fine grain, soft cinematic falloff. No illustration, no painting, no render, no 3D,
no CGI, no game-engine look. No text, no watermark, no logo anywhere in frame.
```

---

## 4.2 · ПРИХОЖАЯ · `@loc_MC_home_hallway`

```
Eye-level wide shot standing just inside the front door of an abandoned Soviet three-room flat in Pripyat,
camera about 1.7 metres from the floor, looking straight ahead down a short narrow hallway, deep enough to
see all three doorways at once.

THE HALLWAY, about four square metres, no window of its own, all its light borrowed from the rooms, so the
three doorways read as three bright openings in a dark space.
STRAIGHT AHEAD, an open doorway into a small bedroom with daylight and part of a window beyond. ON THE LEFT,
an open doorway into the largest room, the brightest of the three, with green leaves visible inside it. ON
THE RIGHT, an open doorway into a small kitchen, and past it two narrow doors to a bathroom and a separate
toilet, one hanging open.
A wooden coat rail still screwed to the wall with nothing on it. A fallen shoe rack. A built-in cupboard
above the front door, its doors sprung open and empty. Buckled linoleum underfoot beneath a drift of plaster
and blue paint flakes.

SPATIAL CONTINUITY: the front door is immediately behind the camera. The bedroom is straight ahead, the
living room is on the left, the kitchen is on the right. These are the same three rooms photographed in the
other frames of this location.

CONSISTENCY LOCK — identical in every room of this apartment.
The building is a Soviet 1-464 series precast concrete panel block in Pripyat, abandoned forty years. This
flat is on the third floor. Bright late-spring afternoon outside, everything in full new green. Indoors,
daylight only, entering through the windows, soft and directional, fine dust hanging in it. No artificial
light anywhere, nothing switched on, no lamp, no torch.
DECAY REGISTER — the exact look of ruin in this flat, in every room.
Walls are painted in the Soviet two-tone way: a band of oil paint from the floor to waist height in dull
TURQUOISE-BLUE or green-blue, and lime whitewash above it. That paint has failed everywhere — it lifts in
large curled flakes, some still clinging, most fallen, and the floor is covered in a drift of pale blue and
white paint chips and plaster flakes, thick in the corners. Where the wallpaper survives it is a small faded
seventies floral print, hanging away in long tongues with yellowed newspaper beneath.
Ceilings have lost their whitewash in patches down to the bare concrete slab, with black damp streaks
running from every window and every corner.
Floors: herringbone parquet in the rooms, lifted and sprung apart, sheets of it missing; buckled linoleum in
the kitchen and hallway. Loose boards, torn strips of lino and fallen laths lie about.
WINDOWS ARE MIXED, NEVER ALL THE SAME. Room to room and opening to opening they differ: some still have
their white-painted wooden frames complete with dirty glass in them; some have the frame but the glass gone,
the sashes hanging open at odd angles or swung out on a single hinge; some are bare openings with the frame
torn out altogether and nothing but sky and leaves in them. In one room a window can be whole while the one
beside it is empty. The paint on every surviving frame is blistered off to bare grey timber. Decide each
opening separately and let them disagree with each other.
GREEN IS COMING IN: bright moss growing across the floor in the damp corners and under the windows, grass
and weeds rooted in the parquet, creeper over the sills.
Everything is soft, faded and quiet — no violence, no smashed-up chaos, no fire damage, no graffiti, no
fresh paint, no new timber, no boarding, no tools, no signage. Only forty years of rain, frost, damp,
growth and quiet looting. Heavy decay but STRUCTURALLY WHOLE: floors, ceilings and walls intact, nothing
collapsed.
Empty deserted interior, still air, no people, no animals, no vehicles, no working lights.
Palette: 60% grey-green damp plaster and faded wallpaper, 30% brown rotted timber and turquoise-blue flaking
paint, 10% living green from the growth coming in and rust-orange from the metal.
Neutral daylight white balance around 5600K, natural saturation, medium contrast, even exposure corner to
corner, no vignette.
Rule of thirds. Photorealistic cinematic film still of a real abandoned building, documentary realism, crisp
natural detail, minimal fine grain, soft cinematic falloff. No illustration, no painting, no render, no 3D,
no CGI, no game-engine look. No text, no watermark, no logo anywhere in frame.
```

---

## 4.3 · ЕГО КОМНАТА · `@loc_MC_home_room`

```
Eye-level wide shot from the doorway of a small bedroom in an abandoned Soviet flat in Pripyat, camera about
1.7 metres from the floor, looking straight into the room, the window on the far wall and the whole room
readable from wall to wall.

THE ROOM, about ten square metres, with a corner of two windows in the outer wall. Their white-painted
wooden frames are still in place, swung open on their hinges at odd angles, one leaf still holding a dirty
pane and the rest empty; the paint on them has blistered off to bare grey timber and the sills are rotted
soft. Beyond them, green tree crowns and hard afternoon light.
THE WALLS HAVE LOST THEIR WALLPAPER ALMOST ENTIRELY and stand as bare grey render, mottled with damp,
patched with the last torn scraps of paper still stuck to it. In the corners and under the windows the
plaster has gone dark and soft.
UNDER THE WINDOW A BED, and it is not made up — it is a bed taken apart by time. A dark red-brown lacquered
headboard panel stands against the right-hand wall, the varnish crazed and lifting; a matching footboard
panel leans flat against the left wall where it fell off. Between them the iron frame with its sprung wire
base sags almost to the floor, the springs and coils showing, and a filthy striped ticking mattress lies
half across it, slipped down at one end and split open.
A CAST-IRON RADIATOR under the window, thick ribbed sections, its white paint gone to rust down every rib,
still bolted to the wall on a bracket, a length of pipe running up beside it.
ON THE LEFT, the remains of a desk: a plain Soviet writing table, chipboard with the veneer lifting and
peeling off in sheets, one leg gone so it sits down on its corner, drawers pulled out and empty. A wooden
chair lies upended in the foreground, on its back with its legs in the air, the seat rotted out of it.
ON THE RIGHT, a tall wardrobe and a low cupboard, doors gone or hanging on a single hinge, bare shelves
inside, nothing on them.
THE FLOOR IS HERRINGBONE PARQUET AND IT IS COMING APART: whole patches of the blocks are gone, showing the
dark bitumen bedding and grit beneath, and the surviving blocks are lifted and sprung. Over it lie fallen
laths and boards, torn strips of paper, swollen books and school exercise books, an old cloth toy gone grey
and shapeless, a single child's shoe, and drifts of pale paint flakes.
IN THE DAMP CORNER, BRIGHT GREEN MOSS has taken the floor in a spreading patch, thick and vivid against all
the grey, growing right over the parquet and up the base of the wall.
Daylight from the single window rakes across the room and dies quickly in the corners. Dust hangs in it.

SPATIAL CONTINUITY: the hallway is directly behind the camera; the living room is off that hallway to the
left and the kitchen to the right, both out of frame here.

CONSISTENCY LOCK — identical in every room of this apartment.
The building is a Soviet 1-464 series precast concrete panel block in Pripyat, abandoned forty years. This
flat is on the third floor. Bright late-spring afternoon outside, everything in full new green. Indoors,
daylight only, entering through the windows, soft and directional, fine dust hanging in it. No artificial
light anywhere, nothing switched on, no lamp, no torch.
DECAY REGISTER — the exact look of ruin in this flat, in every room.
Walls are painted in the Soviet two-tone way: a band of oil paint from the floor to waist height in dull
TURQUOISE-BLUE or green-blue, and lime whitewash above it. That paint has failed everywhere — it lifts in
large curled flakes, some still clinging, most fallen, and the floor is covered in a drift of pale blue and
white paint chips and plaster flakes, thick in the corners. Where the wallpaper survives it is a small faded
seventies floral print, hanging away in long tongues with yellowed newspaper beneath.
Ceilings have lost their whitewash in patches down to the bare concrete slab, with black damp streaks
running from every window and every corner.
Floors: herringbone parquet in the rooms, lifted and sprung apart, sheets of it missing; buckled linoleum in
the kitchen and hallway. Loose boards, torn strips of lino and fallen laths lie about.
WINDOWS ARE MIXED, NEVER ALL THE SAME. Room to room and opening to opening they differ: some still have
their white-painted wooden frames complete with dirty glass in them; some have the frame but the glass gone,
the sashes hanging open at odd angles or swung out on a single hinge; some are bare openings with the frame
torn out altogether and nothing but sky and leaves in them. In one room a window can be whole while the one
beside it is empty. The paint on every surviving frame is blistered off to bare grey timber. Decide each
opening separately and let them disagree with each other.
GREEN IS COMING IN: bright moss growing across the floor in the damp corners and under the windows, grass
and weeds rooted in the parquet, creeper over the sills.
Everything is soft, faded and quiet — no violence, no smashed-up chaos, no fire damage, no graffiti, no
fresh paint, no new timber, no boarding, no tools, no signage. Only forty years of rain, frost, damp,
growth and quiet looting. Heavy decay but STRUCTURALLY WHOLE: floors, ceilings and walls intact, nothing
collapsed.
Empty deserted interior, still air, no people, no animals, no vehicles, no working lights.
Palette: 60% grey-green damp plaster and faded wallpaper, 30% brown rotted timber and turquoise-blue flaking
paint, 10% living green from the growth coming in and rust-orange from the metal.
Neutral daylight white balance around 5600K, natural saturation, medium contrast, even exposure corner to
corner, no vignette.
Rule of thirds. Photorealistic cinematic film still of a real abandoned building, documentary realism, crisp
natural detail, minimal fine grain, soft cinematic falloff. No illustration, no painting, no render, no 3D,
no CGI, no game-engine look. No text, no watermark, no logo anywhere in frame.
```

---

## 4.4 · ЗАЛ С ДЕРЕВОМ · `@loc_MC_home_living`

Главный кадр всей квартиры.

```
Eye-level wide shot from the doorway of the largest room of an abandoned Soviet flat in Pripyat, camera
about 1.7 metres from the floor, looking straight into the room.

THE ROOM, about seventeen square metres, the largest in the flat, with a recessed loggia opening off one
end, AND A TREE HAS GROWN INTO IT.
THE TREE IS THE SUBJECT. One window is completely gone — no glass, no frame, no sash, only the raw opening —
and a THICK TREE LIMB, as thick as a leg, runs in through it, over the sill and down into the room. THE
CROWN STANDS INSIDE THE ROOM AND FILLS NEARLY HALF ITS VOLUME: heavy green summer foliage against the ruined
walls, branches spread across the ceiling and pressed into the corner, daylight coming through the leaves
and falling as broken green light. The bark is real bark, dark and textured. Beneath it the parquet has
given way to a spreading carpet of bright moss and grass.
AROUND IT: a Soviet sideboard against the side wall, its glass smashed out of the upper doors, shelves bare.
A collapsed sofa with the springs through the fabric and the fabric gone to grey felt. AN OLD SOVIET
TELEVISION on the floor beside it — a boxy wooden-cased set with a round-cornered grey screen, the screen
cracked, the back panel off and the guts pulled out, dust an inch thick on top of it. A fallen curtain rail.
THE WALLS: the last of a small faded seventies floral wallpaper hangs off in long tongues with yellowed
newspaper beneath, and where it has gone the bare grey render shows, with black water streaks running from
the ceiling to the floor down every corner and under every window. THE FLOOR IS HERRINGBONE PARQUET AND IT
IS COMING APART — patches of blocks missing down to the dark bedding, the rest lifted and sprung — and from
under the tree the moss spreads out across it in a thick bright green carpet, with grass and weed rooted in
the gaps between the blocks. Fallen laths, plaster and pale paint flakes lie everywhere else. The second
window of the room still has its white-painted frame with one dirty pane in it, untouched, which makes the
missing one beside it worse.
The loggia doorway beyond, its glazing gone, full of blown leaves.
The light in here is the brightest in the flat and it is green, filtered through the leaves.

SPATIAL CONTINUITY: the hallway is behind the camera to the right; the bedroom and the kitchen open off that
same hallway. This tree is the same tree seen from outside growing up the façade into a third-floor window.

CONSISTENCY LOCK — identical in every room of this apartment.
The building is a Soviet 1-464 series precast concrete panel block in Pripyat, abandoned forty years. This
flat is on the third floor. Bright late-spring afternoon outside, everything in full new green. Indoors,
daylight only, entering through the windows, soft and directional, fine dust hanging in it. No artificial
light anywhere, nothing switched on, no lamp, no torch.
DECAY REGISTER — the exact look of ruin in this flat, in every room.
Walls are painted in the Soviet two-tone way: a band of oil paint from the floor to waist height in dull
TURQUOISE-BLUE or green-blue, and lime whitewash above it. That paint has failed everywhere — it lifts in
large curled flakes, some still clinging, most fallen, and the floor is covered in a drift of pale blue and
white paint chips and plaster flakes, thick in the corners. Where the wallpaper survives it is a small faded
seventies floral print, hanging away in long tongues with yellowed newspaper beneath.
Ceilings have lost their whitewash in patches down to the bare concrete slab, with black damp streaks
running from every window and every corner.
Floors: herringbone parquet in the rooms, lifted and sprung apart, sheets of it missing; buckled linoleum in
the kitchen and hallway. Loose boards, torn strips of lino and fallen laths lie about.
WINDOWS ARE MIXED, NEVER ALL THE SAME. Room to room and opening to opening they differ: some still have
their white-painted wooden frames complete with dirty glass in them; some have the frame but the glass gone,
the sashes hanging open at odd angles or swung out on a single hinge; some are bare openings with the frame
torn out altogether and nothing but sky and leaves in them. In one room a window can be whole while the one
beside it is empty. The paint on every surviving frame is blistered off to bare grey timber. Decide each
opening separately and let them disagree with each other.
GREEN IS COMING IN: bright moss growing across the floor in the damp corners and under the windows, grass
and weeds rooted in the parquet, creeper over the sills.
Everything is soft, faded and quiet — no violence, no smashed-up chaos, no fire damage, no graffiti, no
fresh paint, no new timber, no boarding, no tools, no signage. Only forty years of rain, frost, damp,
growth and quiet looting. Heavy decay but STRUCTURALLY WHOLE: floors, ceilings and walls intact, nothing
collapsed.
Empty deserted interior, still air, no people, no animals, no vehicles, no working lights.
Palette: 60% grey-green damp plaster and faded wallpaper, 30% brown rotted timber and turquoise-blue flaking
paint, 10% living green from the growth coming in and rust-orange from the metal.
Neutral daylight white balance around 5600K, natural saturation, medium contrast, even exposure corner to
corner, no vignette.
Rule of thirds. Photorealistic cinematic film still of a real abandoned building, documentary realism, crisp
natural detail, minimal fine grain, soft cinematic falloff. No illustration, no painting, no render, no 3D,
no CGI, no game-engine look. No text, no watermark, no logo anywhere in frame.
```

---

## 4.5 · КУХНЯ · `@loc_MC_home_kitchen`

```
Eye-level wide shot from the doorway of a small kitchen in an abandoned Soviet flat in Pripyat, camera about
1.7 metres from the floor, looking straight into the room with the window on the far wall.

THE KITCHEN, about seven square metres, with a window in the outer wall. The white-painted wooden frame is
still in place but the glass is gone from most of it, the empty sashes standing open at an angle, bare
branches and green beyond.
THE WALLS ARE PAINTED IN TWO ZONES, and this is the strongest thing in the room: a band of dull TURQUOISE
oil paint from the floor to just above waist height, and chalky white lime above it, the line between them
straight and hand-painted. The turquoise has failed in wide patches, lifting in big curled flakes and
falling away to the grey plaster beneath; the white above is blistered and streaked with damp. On one wall a
small faded red plate or sticker is still fixed at head height.
A CAST-IRON RADIATOR under the window, thick ribbed sections, paint gone to rust, still on its brackets.
THE GAS STOVE stands pulled out from the wall and slightly askew, standing free on the floor as if someone
started to move it and gave up: a white enamel Soviet cooker with four burners and an oven door, the enamel
chipped through to black iron along every edge and streaked with rust, the oven door hanging half open on a
sagging hinge, the hob top furred with dirt. ONE HEAVY CAST-IRON BURNER GRATE HAS COME OFF AND LIES ON THE
FLOOR a metre away, upside down.
A REFRIGERATOR beside it in the same state: a small rounded Soviet fridge, white enamel gone yellow and
rust-streaked, its door hanging wide open and unable to close, the inside black with mould, the shelves bare
and the rubber seal perished and hanging loose.
A small table under the window with a torn oilcloth cover, and a white enamel basin sitting on the floor
beside it, chipped to black at the rim. On the sill, two or three cloudy glass milk bottles with dried
residue caked in the bottom, and a chipped enamel mug. Cupboard doors sprung open above an empty worktop.
A bare wire hangs from a hole in the ceiling where the light was.
THE FLOOR IS BURIED: buckled linoleum lifting in bubbles and torn back in strips, and over all of it a thick
scatter of fallen turquoise and white paint flakes, plaster, and long wooden laths lying where the ceiling
trim came down.
GREEN GROWTH HAS COME IN THROUGH THE WINDOW: creeper over the sill, down the wall and starting across the
worktop.
Daylight from the single window is flat and even; the room is small enough that it reaches every corner.

SPATIAL CONTINUITY: the hallway is behind the camera; the bedroom is straight across that hallway and the
living room at its far end. Two narrow doors to a bathroom and a separate toilet are just outside this
doorway.

CONSISTENCY LOCK — identical in every room of this apartment.
The building is a Soviet 1-464 series precast concrete panel block in Pripyat, abandoned forty years. This
flat is on the third floor. Bright late-spring afternoon outside, everything in full new green. Indoors,
daylight only, entering through the windows, soft and directional, fine dust hanging in it. No artificial
light anywhere, nothing switched on, no lamp, no torch.
DECAY REGISTER — the exact look of ruin in this flat, in every room.
Walls are painted in the Soviet two-tone way: a band of oil paint from the floor to waist height in dull
TURQUOISE-BLUE or green-blue, and lime whitewash above it. That paint has failed everywhere — it lifts in
large curled flakes, some still clinging, most fallen, and the floor is covered in a drift of pale blue and
white paint chips and plaster flakes, thick in the corners. Where the wallpaper survives it is a small faded
seventies floral print, hanging away in long tongues with yellowed newspaper beneath.
Ceilings have lost their whitewash in patches down to the bare concrete slab, with black damp streaks
running from every window and every corner.
Floors: herringbone parquet in the rooms, lifted and sprung apart, sheets of it missing; buckled linoleum in
the kitchen and hallway. Loose boards, torn strips of lino and fallen laths lie about.
WINDOWS ARE MIXED, NEVER ALL THE SAME. Room to room and opening to opening they differ: some still have
their white-painted wooden frames complete with dirty glass in them; some have the frame but the glass gone,
the sashes hanging open at odd angles or swung out on a single hinge; some are bare openings with the frame
torn out altogether and nothing but sky and leaves in them. In one room a window can be whole while the one
beside it is empty. The paint on every surviving frame is blistered off to bare grey timber. Decide each
opening separately and let them disagree with each other.
GREEN IS COMING IN: bright moss growing across the floor in the damp corners and under the windows, grass
and weeds rooted in the parquet, creeper over the sills.
Everything is soft, faded and quiet — no violence, no smashed-up chaos, no fire damage, no graffiti, no
fresh paint, no new timber, no boarding, no tools, no signage. Only forty years of rain, frost, damp,
growth and quiet looting. Heavy decay but STRUCTURALLY WHOLE: floors, ceilings and walls intact, nothing
collapsed.
Empty deserted interior, still air, no people, no animals, no vehicles, no working lights.
Palette: 60% grey-green damp plaster and faded wallpaper, 30% brown rotted timber and turquoise-blue flaking
paint, 10% living green from the growth coming in and rust-orange from the metal.
Neutral daylight white balance around 5600K, natural saturation, medium contrast, even exposure corner to
corner, no vignette.
Rule of thirds. Photorealistic cinematic film still of a real abandoned building, documentary realism, crisp
natural detail, minimal fine grain, soft cinematic falloff. No illustration, no painting, no render, no 3D,
no CGI, no game-engine look. No text, no watermark, no logo anywhere in frame.
```

---

**Что проверить во всех пяти**

| Симптом | Что делать |
|---|---|
| Комнаты выглядят из разных квартир | `CONSISTENCY LOCK` разъехался. Сверить блоки посимвольно — они обязаны быть одинаковыми |
| Нет двухцветной покраски стен | Главная фактура с твоих фото. Усилить `a band of oil paint to waist height in dull TURQUOISE-BLUE, and lime whitewash above` |
| Пол чистый, без крошки | Усилить `the floor is covered in a drift of pale blue and white paint chips and plaster flakes` |
| Окна выбиты везде | Кроме зала окна целые по конструкции. Усилить `white-painted wooden frame still in place with the sashes standing open` |
| Комнаты пустые, мебели нет | Усилить списки предметов в каждой комнате |
| Мебель расставлена аккуратно | Усилить `sits down on one corner`, `lying on its back`, `standing slightly askew` |
| Разгром, битьё, пожар | Усилить `no violence, no smashed-up chaos, no fire damage` |
| Обвалы перекрытий | Усилить `STRUCTURALLY WHOLE ... nothing collapsed` |
| Похоже на рендер | Усилить `documentary realism`, `no render, no 3D, no game-engine look` |
| Кадр не от двери | Усилить `Eye-level wide shot from the doorway ... looking straight into the room` |

---

# 6 · ВИДЕО, 26 СЕК

Пишу после того, как вернутся локации — чтобы описывать реальные кадры, а не предполагаемые.
