# AI FILM PIPELINE — UNIVERSAL HANDBOOK

**What this is.** A project-agnostic method for building an AI-generated film or video with Seedance 2.0 + Soul Cinema + the image-edit models. It contains no story, no characters, no settings — only the working system. Any agent or human picking up any project can read this and know how the work is organised.

**Where it came from.** Distilled from a published feature-film production brief (95 min, fully generated, 15 people, ~14 days of generation). Every rule here exists because a shot failed without it.

**Relationship to the skills.** Three skills carry the prompt-writing craft in depth:

| Skill | Owns |
|---|---|
| `lira-image-prompts` | Image prompts — model routing, palettes, tech blocks, surgical edits |
| `cinedance-video-prompts` | Video prompts — the block skeleton, optics, blocking, physics, lighting |
| `acting-performance` | The performance layer — objectives, beats, eye life, voice, business |

This handbook holds what the skills do **not**: pipeline order, asset architecture, naming, sheet construction, the GEO map, style prefix, iteration discipline, and post. When they overlap, the skills win on prompt wording; this handbook wins on process.

---

# 0. THE PIPELINE

Work in this order. Skipping a stage costs more than doing it.

```
1. Script & narrator pass       → locked text, VO separated from visuals
2. Asset design                 → who/where/what exists, as a tag list
3. Asset generation             → character sheets, location sheets, prop sheets
4. Stress test                  → 10/10 recognisable, alone and together
5. Descriptor writing           → the text half of every asset, final wording
6. Constants                    → Style Prefix, GEO maps, voice prompts, acting profiles
7. Shotlist                     → per scene block: shot no., duration, full prompt
8. Batch generation             → scene by scene, surgical iteration, logged
9. Assembly                     → edit in parallel with generation, order pickups
10. Cleanup                     → defects, regenerations, before colour
11. Colour & sound              → unify, then refine; SFX from generation, music in post
```

**The one rule that saves the most money:** do not generate a single shot until every character, location and prop is locked and stress-tested.

---

# 1. THE ASSET MODEL

## 1.1 An asset is a pair

```
ASSET = descriptor (text)  +  reference (image)
```

The **descriptor** is a complete written description. It goes into every prompt that uses the asset, **word for word, never shortened, never paraphrased**. The **reference** is the image the model anchors on. Neither works alone.

The video model has no memory. Anything not re-described in this prompt does not exist in this shot.

## 1.2 Every state is its own asset

Do not describe a state inside a prompt. Split it.

```
@hero            base
@hero_wet
@hero_wounded
@hero_coat       wardrobe change
```

Same for locations — day, night and rain are three assets, not one asset with weather adjectives. Same for props: a hero object may need a full version for close-ups, a damaged version for a reveal, and a "concealed" version whose prompt forbids showing it and allows only a light leak.

Mixing states in one text makes the model mix them between shots. **Splitting states is cheaper than fighting the model.**

## 1.3 Tag dictionary

Every asset lives under a tag, and the same tag is used everywhere — documents, prompts, canvas, filenames. One dictionary for the whole project.

A workable convention:

```
@char_<PROJECT>_<Name>_v<N>        @char_HG_Roko_v3
@location_<n>_<slug>               @location_3_winter
@location_<slug>_<n>               @location_museum_4
@prop_<slug>_v<N>
```

Rules:

- Version tags are cheap; keep old versions, never overwrite a tag whose shots are already generated.
- Never invent a tag inside a prompt. If it is not in the dictionary, it does not exist.
- Never carry a stale tag from a previous shot into a new one.
- Maintain the dictionary as a single file in the project root, with tag → descriptor → reference path → status (draft / stress-tested / locked).

---

# 2. CHARACTER SHEETS

## 2.1 Structure — three images on one sheet

1. **Close-up of the face**, ideally a **large 3/4 portrait** (head turned slightly, not straight-on) — the model reads this best.
2. **Full body, front — with NO HEAD.**
3. **Full body, back.**

The headless front figure is not a mistake. On wide shots the model kept pulling the face from the small, blurry full-body figure. Remove that head and there is exactly one place the face can come from.

## 2.2 Keep the sheet deliberately boring

- Neutral grey background.
- Flat, even light.
- Real skin — visible pores, no retouch.
- **No film grain, no cinematic lens, no grade baked in.**

The cinema look belongs to the locations and the video prompts. Bake it into the sheet and the character carries that look into every scene and stops reacting to new light.

## 2.3 Generation and selection

- Faces come from **Soul Cinema** — best skin texture, but creative: one prompt returns several different faces.
- **Pick the most believable, not the most beautiful.** A beautiful-but-fake face reveals its fakeness in video, when it is too late.
- **Check the eyes.** Even dark eyes need a catch-light in the pupil. Without it the face is dead and no video model can act with a dead face.

## 2.4 Point changes — clothes, scars, blood, dirt

Workflow:

1. Make the point change on the original sheet in **Nano Banana Pro** or **Seedream 4.5**.
2. Bring the changed region back onto the **original** by hand, with a mask, in any editor.
3. Only the changed part lands on top; everything else keeps its original texture.

**The rule behind it: an image never runs through a model twice in full.** Every full pass destroys texture and drifts colour. After two passes the face turns symmetrical, plastic and lifeless — and dead texture ruins the acting later in video.

## 2.5 Stress test — the gate before locking

- Ten generations, different poses, different light.
- The character must be recognisable **ten times out of ten**.
- Test them **next to other assets** and **in the light of the real scenes ahead**. A hero stable alone often breaks when sharing frame with someone.
- If it fails: the problem is the **description**, not the model. Rewrite the words and test again.

---

# 3. LOCATION SHEETS

- **Shoot the sheet in 3/4, never frontal.** A frontal "pretty picture" becomes flat wallpaper on wides, and past its edges the model invents new surroundings every time. A 3/4 view gives depth to read and covers nearly a full circle of angles.
- **Leave an anchor in every location** — a column, a lamp, a tree, a bench — and tie all staging to it. *"The hero at the lamp, facing the door"* works; *"the hero in the room"* is a lottery.
- **One light logic.** One source, one direction of shadows. Never two suns. Otherwise every new angle re-invents the lighting.
- **The look lives here.** Grade, era, atmosphere and texture are baked into the location asset — this is what the colourist later refines instead of inventing.

## 3.1 Reverse angles — two methods

1. **Direct:** generate a corner of the same space in GPT Image 2 or Nano Banana Pro, matching the soft focus of the original.
2. **Camera walk (stronger):** generate a video of the **empty** location with the camera slowly walking through the space — the video model draws the other sides consistently with the sheet. Screenshot the angle you need, pass it to Seedream / NBP with a prompt to improve texture and lighting. A full location sheet out of a single image.

---

# 4. REFERENCES INSIDE A PROMPT

**Name the role of every reference.** If you do not, the model decides for you and decides wrong — it copies the composition instead of the face, or the face instead of the palette.

```
@hero for character reference — <state anchors relevant to this shot>
@second for character reference — <state anchors>
@loc_x for location reference — take only the space and the texture: <materials, key features>.
Do not use as a starting frame, do not inherit the composition, the angle or the grade.
```

That inheritance ban on location references is mandatory, every time.

References are **assets only** — characters and locations. Not style boards, not mood images.

---

# 5. THE PROMPT SKELETON

A rigid skeleton, in this order. Omit a block only when it genuinely does not apply.

```
SCENE CONTEXT                 — "EXACT N CHARACTERS — NO DUPLICATES"; what happens, who is in shot, take length
ACTIVE REFERENCES             — tags with roles named
LOCATION MAP                  — the geography of the place in words
FIRST FRAME AND SPATIAL BLOCKING — who stands where in frame one
FORMAT MODE                   — one take or hard cuts, duration, real time
OPTICS                        — lens and focus plan
CAMERA                        — how the camera behaves, and what it never does
ACTION TIMING                 — the action beat by beat, in seconds
PHYSICS                       — weight, contact, inertia of everything that moves
LIGHTING                      — one source logic, where it comes from
AUDIO                         — voice descriptors, exact lines, SFX only
CHARACTER ACTING              — state, want, what is hidden, body rhythm, what changes
STYLE                         — the Style Prefix, pasted word for word
QUALITY                       — detail and stability requirements
POSITIVE CONSTRAINTS          — every count and ban, written as what IS in frame
```

**The character-count header is not a formality.** The model loves to add extra people and clone furniture. Only those whose references are in the prompt exist in the frame — and set pieces get direct bans: *"exactly ONE bench, NEVER render a second one."*

**Length is not the enemy — an overloaded beat is.** Full prompts of 3,000–4,000 words are normal. Keep each timing beat to **three sentences maximum**.

---

# 6. THE GEO SPATIAL LAYOUT BLOCK

The single most expensive early failure: characters teleport, swap places, the camera jumps to the wrong side. The model does not remember who stood where in the previous shot.

**The cure:** a floor plan in a few lines, written **once per scene** and pasted into **every shot of that scene without changes**. No heroes, no action — only the place.

```
GEO SPATIAL LAYOUT (locked across every shot — pure spatial map):
— <LANDMARK A> = <what it is, where it sits>
— <LANDMARK B>: <position relative to A, in metres>
— <KEY ZONE>: <position, distance from landmark>
— 180° AXIS: camera ALWAYS stays on the <named> side — it NEVER crosses the line.
— LIGHT: <source> comes from <direction>, <what it does to silhouettes> from the camera's perspective.
```

How to read and write it:

- **Sides exist only from the camera.** Use `frame-left` / `frame-right`. The model does not understand "to the left of the hero."
- **Positions come from landmarks and metres**, not adjectives: "at the altar", "three metres away".
- **State which side the camera stands on and which line it never crosses.** This keeps every cut on one axis.
- **After every cut, name again who stands where and where they look.** The model has no memory of the previous shot.
- **Give static dialogue a corner, not the whole room.** Less space = less freedom to misplace people.
- **GEO is only the map.** The *look* still comes from the location asset — its descriptor and reference go into the prompt next to the map.

---

# 7. THE FIRST-SECOND WIDE

**The first second of every scene is a wide shot** with no lines and no action. The model "photographs" the arrangement — who stands where, what lies where, where the light comes from — and holds it in every following shot. Remove that second and characters start swapping places.

- **Hack:** have someone utter one short sound ("hm") during that second — it helps the video model treat the wide as a separate shot.
- **The wide does not have to be silent.** If the shot answers a previous one, feed the **tail of the previous clip's line** into that first second. The actor then answers the right thing in the right tone, and the two clips glue at the seam.

```
FIRST FRAME AND SPATIAL BLOCKING
SHOT 1 (~1.0s) — a wide that FIXES THE POSITIONS and does nothing else: <blocking>.
No camera move, no action beat.

AUDIO
Over that first second, the tail of the previous clip's line arrives on <NAME>'s lips: "<...>"

ACTION TIMING
1.0s onward — <NAME> answers into the same rhythm: "<line>"
```

Cost: one second of runtime. Saving: hours of reshoots.

---

# 8. WORDING RULES

- **Positive form only.** The model ignores *"does NOT fall on his back"*, or does the opposite. Write *"falls on his stomach."* Every ban in POSITIVE CONSTRAINTS is phrased as what IS in the frame.
- **Present tense. Short sentences.**
- **The character is in frame from frame one**, and never looks into the camera unless asked.
- **Never write age, in any language.** The content filter tightens sharply the moment it reads something that could be a minor. Give role, clothes, action instead.
- **Keep a ban dictionary** of words the model punishes, and their replacements. Start it on day one and grow it per project:

| Avoid | Use |
|---|---|
| dark | low key |
| jolting | rapid motion |
| *(add every word that caused a bad generation)* | |

- **Complex action never sits in the middle of the timing.** Open the prompt with it: *"he is ALREADY mid-swing, the door ALREADY cracking."* The approach to the action is a separate shot.
- **Technical tags close the prompt:** `Photoreal. NON-IP. [aspect ratio]. [duration]s. SFX only. NO CGI. Cinematic.`

---

# 9. THE STYLE PREFIX

One constant block, written once per project, **pasted word for word at the end of every prompt**. Editing it in one place updates every shot.

Template — replace the values, keep the field structure:

```
Style: <resolution/format>. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic.
Cinematography: <camera philosophy>; <light philosophy>; <composition philosophy>.
Lighting: <natural/practical rule> — <key direction>, <camera side>, <atmosphere>. Key light from <sources> only.
Color: 60:30:10 — dominant / secondary / accent.
Camera: Physical cine lens. 180° shutter motion blur.
Skin: Pore-level realism — vellus hair, asymmetric moles, capillary flush, pore-shadow matching on-set light.
Acting: micro-pauses before reactions, precise eye-line, wet living eyes with catch-lights, visible breath and chest rise.
Physics: Gravity and inertia respected — mass has real weight, correct contact shadows. No floating props.
Composition: Rule of thirds + golden ratio. Every person moving from frame one.
Continuity: Characters, props, environment identical across every cut. No identity drift.
Technical: 24fps smooth motion. <detail level>. No jitter.
Audio: Environmental SFX only. No music. No subtitles.
```

**`SFX only. No music.` is mandatory.** Music belongs to post; a generated soundtrack only obstructs the edit.

---

# 10. ACTING IN THE PROMPT

Full craft lives in the `acting-performance` skill. The production-level essentials:

**Write behaviour, not feelings.** A living scene is a character who wants something, something is in the way, and he acts to get it. Emotion is born out of that fight. Give a goal and an obstacle, and change how he fights across the scene: he jokes → it fails → he pushes → it fails → he begs. Every change is a visible event — a pause, a posture shift, a tempo change. Same behaviour all the way through plays flat.

**Write physics, not adjectives.** On emotion words — *sad, angry, shocked* — the model improvises and goes shallow. Describe muscle and body: a tremble, a jaw clenched and flexing, cheekbones drawn tight, a light exhale through the nose.

**Layer intention.** One line of inner monologue per stretch of action, marked `INNER (unspoken)` — what the character thinks and wants.

**Phased blinking** — the cheapest sign of a living face:
`one lazy blink → a quick DOUBLE-BLINK → one HARD reset-blink`

**Gaze.** Always a clear direction, or explicit darting. Micro-expressions are what read as life.

**The micro-life rule for static shots:** one visible micro-event every one to two seconds — the breath lifts the chest, a nostril moves, a brow tenses and releases.

**Describe stillness as held tension, never as a freeze.** Phrases like *"nobody moves"* freeze the frame literally.

**Three things that separate a living shot from a dead one:**

1. The reaction starts **before** the other line ends — the listener gets the point mid-sentence and his face already answers. After an important event, give a fraction of a second to take it in before speaking.
2. **Emotion does not switch off.** After a heavy moment the breath is still uneven, the hands not steady. That tail carries into the next clip and stitches the cuts together.
3. **Hands are busy.** A character does not "have a conversation" — he fixes, counts, pours, and talks over it. The strongest accent in a scene is the moment he **stops** that work because of what he just heard.

State goes in `ACTION TIMING` as muscle; intention goes in `CHARACTER ACTING` as want, concealment, rhythm, and what changes across the shot. The words *exhausted* and *angry* should never need to appear.

---

# 11. VOICE AND DIALOGUE

**The voice is locked in pre-production**, before any dialogue is written: register, tempo, accent, manner. It is pasted into the audio field **verbatim, every time**, and never changes.

```
Voice: <register and timbre>; <pacing>; <accent/origin>; <emotional manner under pressure>.
```

Stress-test the voice the same way as the look. If it drifts between generations, harden the wording.

**Every dialogue line is built the same way:**

```
voice descriptor → the line in quotes → the physical action → the facial reaction
```

Hard rules:

- **Speech lives only in the AUDIO block.** Not one word of dialogue inside the action blocks.
- **Everyone speaks ONLY the line in quotes.** Whoever has no line stays completely silent. The model loves to add its own "uhm"s, chuckles and whole phrases — block it explicitly.
- A *"half-laugh"* written in the action is a **facial expression, with no sound.**
- **Write the mix:** voices clean and close to the microphone, ambience under them, ambience dips when someone speaks.
- **Rare or invented names get a phonetic transcription**, or the model mangles them.
- **Seam tricks:** feed the tail of the previous line into the wide of a dialogue; and open every new generation with the line that closed the previous one — the emotion crosses the seam with the text.

---

# 12. NARRATION / VOICE-OVER

Narration is **not** a generation instruction. Keep it out of the prompts entirely.

- Maintain a **separate VO file** (or a clearly separated section) with the narrator's lines, each carrying its **timecode** and the shot number it sits over.
- The shotlist references VO by ID only: `VO-07 @ 1:12`.
- Prompts carry only diegetic sound. `No narration` belongs in the audio constraints unless narration is genuinely diegetic in that shot.
- Record VO in post over the locked edit; never generate it inside a clip.

---

# 13. FIRST-PERSON / POV SEQUENCES

When a project leans on first-person, treat POV as its own discipline:

- **The camera is a body, not a tripod.** Breath-driven micro-motion, head-turn latency, the small settle after a turn. Handheld language, never gimbal, never drone.
- **Show the frame's own body** — hands, forearms, shoulder edge, the occasional blur of a nose or hood edge. A POV with no body reads as a floating camera.
- **Eye-height and lens must match the human read**, not a cinematic wide. Nothing about the framing should be "composed" beyond what a person's gaze would do.
- **Blink events** as light-level punctuation.
- **Look motivation.** Every pan is a decision — toward something or away from something. Write the reason, not just the direction.
- **Fewer characters in frame means the burden shifts to environment behaviour and sound.** Where a project shows the character rarely and shows his *experience* instead, the acting budget moves into camera behaviour, breath, hands and world reaction.

---

# 14. RECURRING PROBLEM SOLUTIONS

**Crowds.** One "crowd character" asset with a stated range of heights and clothing. One or two lead extras get their own assets for close-ups. On medium shots state the number directly — "20+" — or the model gives you three people in one take and a hundred in the next.

**Transitions between two spaces** hold on a threshold: both location assets in one prompt, and the seam is a doorway with a light contrast across it — *"a warm amber room, a cold blue corridor beyond the arch."* The contrast explains the palette change and forgives small geometry errors.

**Giants and scale** live on scale anchors: a size comparison in every prompt plus a human figure to measure against. Without both, the model quietly shrinks the giant toward human height. Write it as a law with visible proof:

```
POSITIVE CONSTRAINTS
THE SCALE LAW — VISIBLE PROOF IN THE PICTURE: <subject> stands <N> METRES tall — <what is lost out of frame>,
<a body part compared to a known object>, and <human> at his foot reaches <landmark on the body>.
In every frame the silhouette is at least <N> TIMES the height of the human figure beside it, and the frame
cannot hold both extremes at once. A <subject> that reads as a large man = failed shot.
```

**Furniture and prop cloning.** Direct numeric bans in POSITIVE CONSTRAINTS, phrased positively: *"exactly ONE X"*, *"FIVE broken Y, never re-rendered as intact, never multiplied."*

---

# 15. ITERATION DISCIPLINE

- **Generate in batches, scene by scene.**
- **Change one line per iteration.** Everything else stays word for word. Rewrite a prompt in full and you lose the parts that worked.
- **Log every iteration:** prompt version, what changed, verdict. Without the log you cannot repeat a good shot.
- **The 10–15 rule:** if a shot has not come together in ten to fifteen iterations, the problem is not the wording. **Simplify the shot** — split it in two, remove an action, change the angle.
- **Give the model less freedom.** A corner instead of a room. An anchor instead of open space. A map instead of guesswork. One action per shot.

---

# 16. FILE ORGANISATION

```
/PROJECT
  README.md                     — what this project is, current status, who owns what
  ASSET_REGISTRY.md             — the tag dictionary: tag → descriptor → reference → status
  STYLE_PREFIX.md               — the constant, single source
  SCRIPT.md                     — locked script
  NARRATION.md                  — VO lines with timecodes and shot IDs
  BAN_DICTIONARY.md             — words the model punishes, and replacements
  /descriptors                  — one file per asset, full descriptor text
  /geo                          — one GEO SPATIAL LAYOUT per scene
  /shotlists                    — one file per scene block: shot no., duration, full prompt
  /assets                       — sheets and references, filenames = tags
  /log                          — iteration log per scene
  /out                          — accepted generations
```

**Descriptors and the Style Prefix live as constants.** One edit updates every shot at once. Shotlists reference constants; they never inline a copy that can drift.

---

# 17. POST-PRODUCTION

- **Edit in parallel with generation.** The editor assembles scenes as they arrive and orders what is missing — "need a cutaway to the hands", "need a wider one". A reshoot costs minutes, so the edit should shape production, not wait for it.
- **Generations always feel slow.** Cut more aggressively than feels right, and plan to trim the first and last half-second of every clip — the edges drift.
- **Cleanup pass after picture lock, before colour.** AI material carries defects invisible while working and obvious on a big screen: extra fingers, boiling textures, fake text on signs. Retouch small defects frame by frame; regenerate fully broken shots from the saved final prompt with one line changed. First priority: close-ups of faces and hands.
- **Colour starts with unification.** Every generation arrives with its own built-in grade; bring neighbouring shots of a scene to one look first. The look itself was baked into the location assets in pre-production — the colourist refines, never invents.
- **Voices come from the generations.** Clean them: noise removal, timbre evened between clips, voice placed in the space. Studio re-record only when a clip has no usable voice.
- **Sound design and music are built in post on top of continuous ambiences.** One shared atmosphere glues generated shots into one space, even where the picture drifts.

---

# 18. THE FIVE RULES

1. **Assets first.** No shot before every character, location and prop is locked and stress-tested. This saves more than everything else combined.
2. **Describe everything, every time.** The model has no memory. The descriptor goes into every prompt, word for word, never shortened.
3. **Change one thing at a time.** A prompt is a working mechanism. One line per iteration, everything into the log.
4. **Give the model less freedom.** A corner instead of a room, an anchor instead of open space, a map instead of guesswork, one action per shot.
5. **If a shot will not come together — simplify the shot, not the words.** Split it in two, remove an action, change the angle.

The pipeline does not need a large team to work. It needs the rules followed. It scales down to one person.
