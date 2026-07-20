# Промты для портретов персонажей (аниме, чистые кадры)

Цель — **чистые отдельные картинки** каждого персонажа (без текста, имени и цифр на изображении, на нейтральном фоне): их можно и на сайт положить, и позже скармливать ИИ как референсы для манги/вебтуна.

## Как этим пользоваться — «якорь → вариации»

Главное — **консистентность**: один персонаж = одно лицо во всех кадрах. Чисто текстовые промты «плывут» (пять генераций = пять разных людей), поэтому:

1. Берёшь промт **«1. Лицо анфас»** персонажа → генеришь несколько раз → выбираешь ОДИН кадр, где он «тот самый». Это **якорь**.
2. Скармливаешь якорь в GPT **как картинку** и берёшь промт **«2. Полный рост»**, **«3…»** и т.д. — там вместо описания внешности уже стоит «тот же персонаж, что на картинке». Так лицо/волосы/тату не меняются.
3. Готовые кадры — на сайт (поле `cover` персонажа) и в архив референсов.

**Каждый кадр — без фона-сцены и без текста.** Данные каноничные (не то, что было на старых листах): Шин 185/91, Огата 211/84 и т.д.

### Копипаст-обёртка (добавляй к каждому промту)

- **[СТИЛЬ]** (в начало): `Clean modern TV anime illustration, in the visual tradition of Kuroko's Basketball, Haikyuu!! and Horimiya — crisp confident linework, soft cel-shading, expressive anime eyes, naturalistic colour palette. Strictly 2D anime — not 3D, not photorealistic, not Korean webtoon/manhwa.`
- **[ЧИСТО]** (в конец): `Plain neutral light-grey background, character only, no text, no letters, no numbers, no captions, no logo, no watermark, single clean view.`

Для видов 2–5, когда уже есть якорь, добавляй фразу `the same character as in the uploaded reference image, identical face, hair and tattoos` вместо повторного описания внешности.

### Негатив (для локального Stable Diffusion; в GPT не нужен)

```
lowres, worst quality, low quality, jpeg artifacts, blurry, signature, watermark, username, text, letters, caption, character sheet, turnaround, multiple views, frame, border, extra fingers, missing fingers, extra limbs, malformed hands, poorly drawn hands, poorly drawn face, deformed, bad anatomy, bad proportions, long neck, 3d, photorealistic, realistic, western comic, korean webtoon, manhwa, semi-realistic
```

Локальные чекпойнты/настройки для SD — в конце файла (если будешь генерить не в GPT).

---

# ПЕРСОНАЖИ НА САЙТЕ

## Оками Шин — 185 см / 91 кг · PF/центр-гибрид
**Внешность (для якоря):** teenage boy (~17, looks older), messy dark-grey hair, steel-grey eyes with a cold heavy stare, thin black rectangular glasses, scar above the left eyebrow, silver hoop earring in the left ear, sharp jawline, broad powerful heavyweight build (185 cm, dense muscle), geometric line tattoos and a wolf-head tattoo on the forearms (no hand/palm tattoos), thin wolf-fang pendant necklace.

1. **Лицо анфас (паспорт):** front-facing head-and-shoulders, neutral-cold expression, looking straight at the viewer, glasses on.
2. **Полный рост:** full body, standing, all-black outfit — hoodie, jeans, heavy boots, pendant visible at the collar, arms relaxed, cold expression.
3. **Фирменная поза:** mid-air in an explosive basketball dunk, black sportswear, muscles tensed, hair flying with motion, intense focused eyes, dramatic low angle.
4. **Момент:** sitting alone against a gym wall at night, glasses off in one hand, tired unguarded expression, moody blue rim-light.
5. **Деталь:** close-up of the hand and forearm showing the geometric line tattoos and wolf-head tattoo, high-detail ink linework.

## Оками Юки — 166 см · мать
**Внешность:** 37-year-old woman who looks younger, warm dark-chestnut hair in a low bun with loose strands framing the face, grey-green eyes, soft oval face, gentle smile with faint smile-lines, slender graceful build.

1. **Лицо анфас:** front-facing, gentle reassuring expression, soft warm light.
2. **Полный рост:** standing, cosy cream sweater and soft-grey skirt, calm posture, hands folded gently.
3. **Фирменная поза:** standing in a kitchen doorway, a light towel over one shoulder, calm steady posture, tired-but-warm expression — quiet strength.
4. **Момент:** sitting alone, hands in her lap, a rare unguarded flash of sadness before she catches herself.
5. **Деталь:** close-up of hands folding laundry, a simple silver ring, gentle domestic warmth.

## Оками Аой — ~128 см · сестра, 8 лет
**Внешность:** 8-year-old girl, dark ash-grey hair (same shade as her older brother) in two pigtails with bright-pink ties, big grey-blue eyes, round childlike face with chubby cheeks, bright contagious smile.

1. **Лицо анфас:** front-facing, big bright smile, cheerful.
2. **Полный рост:** standing in a bright-pink dress and sneakers, clutching a grey plush wolf against her chest.
3. **Фирменная поза:** her teasing gesture — pulling down one lower eyelid with a finger and sticking out her tongue, one foot lifted, playful.
4. **Момент:** sitting cross-legged, head tilted, staring intently at someone off-frame with unusually perceptive eyes for her age — reading a feeling.
5. **Деталь:** close-up of small hands hugging the worn grey plush wolf tightly.

## Сэо Харуки — 182 см · капитан, разыгрывающий
**Внешность:** 17–18-year-old boy, short neat black hair combed back, dark-brown clear composed eyes, mature symmetrical features (looks older than his age), lean athletic point-guard build.

1. **Лицо анфас:** front-facing, controlled composed expression.
2. **Полный рост:** standing in a perfectly pressed school uniform, disciplined upright posture.
3. **Фирменная поза:** in basketball uniform mid-command, one arm raised directing teammates, sharp focused captain's expression.
4. **Момент:** sitting alone on an empty gym floor after a loss, elbows on knees, mask of control dropped — genuinely tired and uncertain.
5. **Деталь:** close-up of hands gripping a basketball, knuckles a little rougher than expected for a "perfect" student.

## Ямагути Масаки — 186 см · тяжёлый форвард
**Внешность:** 17–18-year-old boy, dark-brown short messy just-off-practice hair, sharp dark-brown eyes that burn when angry, square jaw, thick eyebrows, powerfully built stocky muscular frame, thick neck, wide shoulders.

1. **Лицо анфас:** front-facing, intense guarded expression.
2. **Полный рост:** standing, disheveled untucked uniform with rolled-up sleeves, confrontational stance, arms crossed.
3. **Фирменная поза:** boxing out under the basket, aggressive powerful posture, gritted teeth, sweat visible.
4. **Момент:** alone in an empty gym at night, taking one final quiet shot just for himself, calm unguarded expression very unlike his usual intensity.
5. **Деталь:** close-up of a muscular calloused right hand and forearm gripping a basketball tightly.

## Такаги Широ — 199 см · центровой
**Внешность:** 17–18-year-old boy, pale ash-silver short neat hair (rare natural colour), light grey-blue eyes, a large face with unexpectedly soft gentle features, massively tall broad build, slightly hunched shoulders from shyness.

1. **Лицо анфас:** front-facing, calm quiet expression with a small rare warm smile.
2. **Полный рост:** standing, oversized hoodie and wide sweatpants, gentle-giant presence, shoulders slightly hunched.
3. **Фирменная поза:** standing fully upright and unhunched for once, blocking a shot at the rim with a massive wingspan, focused calm dominance.
4. **Момент:** sitting on the floor of a small home surrounded by several younger foster siblings, gentle protective posture, soft content half-smile.
5. **Деталь:** close-up of an enormous hand next to a basketball for scale, calm relaxed grip.

## Хаяма Даики — 190 см · лёгкий форвард
**Внешность:** 17-year-old boy, deep dark-blue hair with a metallic sheen (rare natural colour), long side-swept bangs near the eyes, dark grey-blue eyes, elegant symmetrical features, high cheekbones, slender long-limbed build with a dancer's grace.

1. **Лицо анфас:** front-facing, cool distant thoughtful expression.
2. **Полный рост:** standing, dark hoodie, slim jeans and a long dark coat, relaxed elegant posture.
3. **Фирменная поза:** mid-air in a rotating dunk that blends contemporary-dance movement with basketball, fluid graceful lines, hair and clothing flowing.
4. **Момент:** alone in an empty dance studio after practice, mid-dance movement, reflected in a wall mirror, quiet private moment.
5. **Деталь:** close-up profile — dark-blue hair strands falling over a focused eye, subtle metallic sheen, rim light.

## Хосино Кенто — 179 см · атакующий защитник
**Внешность:** 17-year-old boy, light-chestnut hair with golden highlights, messy beach-tousled texture with slightly wavy ends, warm brown eyes with a playful glint, open friendly face, natural easy smile that reaches his eyes.

1. **Лицо анфас:** front-facing, warm genuine smile.
2. **Полный рост:** standing, bright colourful hoodie (the only teammate who wears colour), jeans, baseball cap, relaxed easygoing stance, big grin.
3. **Фирменная поза:** mid jump-shot, explosive quick release, joyful determined expression, bright energy.
4. **Момент:** sitting alone on a bench, knee heavily bandaged after an injury, staring at the floor with his smile gone — quiet private sadness.
5. **Деталь:** close-up of warm brown eyes crinkled in a genuine easy smile, golden-highlighted hair falling loosely.

## Нагата Юто — 184 см · лёгкий форвард (запас)
**Внешность:** 17-year-old boy, neat black hair combed to one side, narrow calm dark-brown eyes, a symmetrical pleasant unremarkable face, average tidy athletic build.

1. **Лицо анфас:** front-facing, faint neutral smile.
2. **Полный рост:** standing in a neatly worn practice uniform, relaxed unassuming posture, holding a small food container.
3. **Фирменная поза:** mid defensive slide, solid dependable stance, focused calm concentration — steady fundamentals, nothing flashy.
4. **Момент:** in a home kitchen, carefully packing a homemade bento into a cloth wrap, quiet focused domestic moment.
5. **Деталь:** close-up of neatly arranged homemade onigiri in an open lunch box, faint steam.

## Огата Кэй — 211 см / 84 кг · центровой (1 курс)
**Внешность:** 16-year-old boy, pale near-white soft messy hair over the forehead, light-grey sleepy kind eyes, an elongated gentle face, extremely tall and thin lanky build, noticeably hunched shoulders from shyness.

1. **Лицо анфас:** front-facing, shy gentle expression, slightly hunched even in a headshot.
2. **Полный рост:** standing, oversized practice jersey and shorts, hunched, holding a rice ball, gentle giant.
3. **Фирменная поза:** standing fully upright for once — newfound confidence, unhunched, towering, calm determined blocking position under the rim.
4. **Момент:** sitting on a bench after practice, eating a fourth rice ball while looking mournfully at his own thin arms, gentle self-deprecating humour.
5. **Деталь:** close-up of a large hand holding a small rice ball, comedic scale contrast.

## Мацуи Соу — 175 см · разыгрывающий (1 курс)
**Внешность:** 16-year-old boy, thick dark-chestnut hair sticking up in every direction, big round light-brown eyes with a perpetually surprised look, round chubby-cheeked face, slightly protruding ears, the shortest and smallest build on the team.

1. **Лицо анфас:** front-facing, wide surprised eyes.
2. **Полный рост:** standing in an ill-fitting uniform (long sleeves, loose shorts), slightly clumsy off-balance stance.
3. **Фирменная поза:** mid basketball pass, body suddenly fluid and precise (completely unlike his clumsy off-court self), sharp focused eyes.
4. **Момент:** tripping over a gym bench, arms flailing comedically, wide-eyed mid-fall.
5. **Деталь:** close-up of messy thick hair sticking up at odd angles.

## Мория Кадзуя — тренер, ~45 лет
**Внешность:** 45-year-old man, short greying dark hair, stocky solid build, a weathered composed face, calm steady eyes that make people not want to ask him to repeat himself.

1. **Лицо анфас:** front-facing, neutral composed expression.
2. **Полный рост:** standing in a team tracksuit, whistle around the neck, arms crossed, authoritative stance.
3. **Фирменная поза:** mid-shout with a whistle raised to his mouth, sharp commanding gesture toward the court.
4. **Момент:** at the edge of the court, clipboard in hand, quietly watching one specific player with a calculating gaze.
5. **Деталь:** close-up of a whistle against a tracksuit collar, a weathered hand holding a clipboard nearby.

## Фудзивара Рэн — 195 см · уличный игрок, 20–21
**Внешность:** young man (20–21), dark almost-black hair shorter on the sides and longer on top, messy tousled texture, dark-brown eyes with a sharp playful squint, narrow face, light stubble, a quick slightly cocky grin, lean wiry explosive build.

1. **Лицо анфас:** front-facing, cocky playful grin.
2. **Полный рост:** standing, oversized streetwear hoodie, wide shorts, worn-out sneakers, backwards cap, a basketball under one arm, relaxed confident street stance.
3. **Фирменная поза:** mid-air in a powerful street-style dunk, wild free-spirited energy, motion streaks.
4. **Момент:** leaning against a chain-link fence, a basketball spinning on one finger, watching someone play with sharp assessing eyes.
5. **Деталь:** close-up of rough calloused hands gripping a worn, heavily-used outdoor basketball.

## Мидзусима Хана — одноклассница
**Внешность:** 16-year-old girl, light-blonde dyed straight shoulder-length hair, bright open expressive eyes, a warm easy smile, symmetrical youthful face, average height.

1. **Лицо анфас:** front-facing, warm open smile.
2. **Полный рост:** standing in a neatly-but-casually worn school uniform, relaxed confident posture, one hand on her hip.
3. **Фирменная поза:** mid-gesture during a debate-club argument, one hand raised, sharp confident expression.
4. **Момент:** leaning forward over a classroom desk toward someone off-frame, direct curious body language, unbothered easy expression.
5. **Деталь:** close-up of light-blonde hair catching afternoon sunlight, bright attentive eyes.

---

# ПОКА СКРЫТЫ НА САЙТЕ (`revealed:false`) — на будущее

## Оками Кэндзи — 182 см · отец (34)
**Внешность:** 34-year-old man, dark-grey short tousled hair (the shade his son inherited), a steel-grey heavy stare, hard weathered rugged features, an old scar above the left eye, tanned weather-beaten skin, strong wiry hunter's build, traditional Japanese-style tattoos on the arms (carp, dragon, wave motifs).

1. **Лицо анфас:** front-facing, warm-but-heavy steady stare.
2. **Полный рост:** standing, dark work jacket, thick trousers, heavy boots, old hunting vest, confident grounded stance.
3. **Фирменная поза:** crouched at the edge of a forest examining tracks in the dirt, focused hunter's instinct.
4. **Момент:** kneeling beside a young boy, a hand resting warmly on the child's shoulder, both looking out at a forest — quiet warm family moment.
5. **Деталь:** close-up of a forearm covered in traditional Japanese-style tattoos (carp, dragon, wave), weathered tanned skin.

## Кавамура Горо — 172 см · охотник (57)
**Внешность:** 57-year-old man, short coarse fully-grey hair with a few dark remnants, sharp narrow deep-brown eyes, a hard weathered deeply-lined face, a rare unexpectedly kind smile, short but wiry lean-muscular build.

1. **Лицо анфас:** front-facing, weathered, rare kind smile.
2. **Полный рост:** standing in a forest clearing, thick work jacket and trousers, heavy boots, old hunting vest, grounded solid stance.
3. **Фирменная поза:** setting a trap in the forest undergrowth, weathered hands working with practised precision.
4. **Момент:** sitting by a campfire at night, poking the fire with a stick, sharing a quiet unembellished story, firelight on his face.
5. **Деталь:** close-up of large weathered hands covered in old scars, calluses and burn marks.

## Кирю Масато — 180 см · попечитель (48, антагонист)
**Внешность:** 48-year-old man, dark hair with distinguished grey streaks always perfectly styled, sharp calm dark-brown eyes, groomed handsome mature features, a practised polished smile, a fit trim build.

1. **Лицо анфас:** front-facing, polished controlled smile.
2. **Полный рост:** standing in an expensive tailored dark suit, composed formal posture, hands clasped in front.
3. **Фирменная поза:** standing at a window over a city skyline, one hand in his pocket, calm calculating expression, quiet controlled power.
4. **Момент:** sitting at a polished desk, rubbing his thumb absently against his bare left ring finger, distracted for a moment.
5. **Деталь:** close-up of a well-groomed hand, thumb against a bare ring finger with a faint pale mark where a ring used to be.

## Нишимура Кодзи — 174 см · верный человек бати (45)
**Внешность:** 45-year-old man, dark hair greying at the temples kept short, warm brown eyes, a stocky good-natured face with laugh-lines, an easy genuine smile, solid build.

1. **Лицо анфас:** front-facing, warm genuine smile.
2. **Полный рост:** standing in simple casual clothes, relaxed friendly posture, holding a small wrapped food parcel.
3. **Фирменная поза:** sitting at a small table, sliding a wrapped rice ball across to someone off-frame, a warm inviting gesture.
4. **Момент:** laughing warmly mid-conversation, head tilted back, genuine unguarded joy.
5. **Деталь:** close-up of hands wrapping a pickled-plum rice ball in cloth, careful practised motion.

## Ватанабэ Сора — 180 см · верный человек бати (42)
**Внешность:** 42-year-old man, short black hair, dark-grey sharp eyes, an angular expressionless face, a composed neutral gaze, lean upright build with rigid posture.

1. **Лицо анфас:** front-facing, composed expressionless neutral gaze.
2. **Полный рост:** standing perfectly still, straight rigid posture, simple neat dark clothing.
3. **Фирменная поза:** standing by a window with arms crossed, facing slightly away, guarded closed-off posture.
4. **Момент:** standing perfectly still against a wall during a meeting, arms crossed, listening intently while giving away nothing.
5. **Деталь:** close-up of crossed arms and a rigid controlled posture, sharp tailored dark sleeve.

## Харада Кэн — 172 см · верный человек бати (58)
**Внешность:** 58-year-old man, short grey cropped hair, deep-set dark-brown eyes, a heavily time-worn weathered face, a slow deliberate expression, a slow-moving solidly-built older frame.

1. **Лицо анфас:** front-facing, slow deliberate weathered expression.
2. **Полный рост:** standing in simple traditional dark clothing, heavy grounded stance.
3. **Фирменная поза:** seated cross-legged, a hand raised mid-gesture as if about to speak, quiet unshakable authority.
4. **Момент:** pausing mid-sentence, gaze turned to the side as if carefully choosing his next word, deep contemplative stillness.
5. **Деталь:** close-up of a deeply lined weathered older face, eyes turned thoughtfully to the side.

## Мидзуно Такэси — 172 см · предатель (46)
**Внешность:** 46-year-old man, thinning dark messy hair, brown darting evasive eyes that never hold a gaze long, a puffy tired face with under-eye bags (looks older than his age), a slightly overweight soft build, a tense nervous posture.

1. **Лицо анфас:** front-facing, evasive darting eyes, uneasy expression.
2. **Полный рост:** standing in neat but cheap clothing that tries not to stand out, shoulders slightly hunched, tense.
3. **Фирменная поза:** glancing nervously over his shoulder while walking quickly, tense hurried body language.
4. **Момент:** sitting alone at a small restaurant counter late at night, hands wrapped tightly around a cup, anxious.
5. **Деталь:** close-up of nervous hands fidgeting with a napkin, slightly trembling.

## Судзуки Рэй — 190 см · предатель (44)
**Внешность:** 44-year-old man, short coarse dark hair, brown flat expressionless eyes that look at people like objects, a broad face with almost no visible emotion, a massive broad-shouldered heavy build.

1. **Лицо анфас:** front-facing, total emotional blankness, dull fixed eyes.
2. **Полный рост:** standing, plain practical dark clothing with nothing decorative, still emotionless stance.
3. **Фирменная поза:** standing immovable in a doorway, arms at his sides, completely still and unreadable, imposing physical presence.
4. **Момент:** sitting alone in a sparse room, staring at nothing, unsettling stillness.
5. **Деталь:** close-up of an enormous flat expressionless face, dull brown eyes.

## Хосино Рэй — 168 см · любовный интерес (15)
**Внешность:** 15-year-old girl, long straight deep-black hair with a faint blue sheen in a low ponytail, large calm thoughtful dark-brown eyes, a soft oval face, a gentle warm smile, a slender graceful figure.

1. **Лицо анфас:** front-facing, gentle calm smile.
2. **Полный рост:** standing, an oversized chunky-knit pastel-lavender sweater and a long soft skirt, calm poised stance.
3. **Фирменная поза:** sitting quietly reading a book by a window, calm composed posture, serene inner steadiness.
4. **Момент:** setting a cup of coffee down quietly next to someone without a word, gentle attentive expression.
5. **Деталь:** close-up of long black hair with a subtle blue sheen catching soft window light, calm dark eyes.

## Эгути Рэйто — 178 см · новичок-мажор (15, Year 2)
**Внешность:** 15-year-old boy, light-chestnut hair perfectly styled and clearly maintained, sharp amber-brown eyes with an appraising look, clean symmetrical almost-too-perfect features, average build with perfect posture.

1. **Лицо анфас:** front-facing, appraising slightly haughty look.
2. **Полный рост:** standing, custom-tailored school uniform, expensive limited-edition sneakers, confident chin-up stance.
3. **Фирменная поза:** mid point-guard move, trying hard to look effortlessly in control, a sharp determined expression more genuine than usual.
4. **Момент:** standing frozen, at a rare loss for words, uncertainty breaking through his usual polished confidence.
5. **Деталь:** close-up of perfectly styled light-chestnut hair and a pair of brand-new limited-edition sneakers.

## Танака Рю — 178 см · бывший человек бати (44)
**Внешность:** 44-year-old man, dark hair with grey at the temples in a short neat cut, calm slightly tired dark-brown eyes, rugged defined features, a small old scar on the chin, a solidly-built strong frame, tanned skin, strong hands.

1. **Лицо анфас:** front-facing, calm slightly tired steady expression.
2. **Полный рост:** standing, simple dark work trousers, shirt and jacket, a sturdy grounded stance.
3. **Фирменная поза:** standing in a doorway surrounded by several children of different ages, a protective steady presence.
4. **Момент:** sitting at a dinner table, speaking plainly and without excuses to someone across from him, direct honest expression.
5. **Деталь:** close-up of a strong weathered hand with faint old scars, resting on a wooden table.

## Сэо Такэси — отец Харуки (55)
**Внешность:** 55-year-old man, dark hair greying neatly, tall composed features, a strict evaluating gaze, always impeccably groomed.

1. **Лицо анфас:** front-facing, strict evaluating gaze.
2. **Полный рост:** standing in a sharp business suit, rigid formal upright posture.
3. **Фирменная поза:** standing across from a younger man, arms behind his back, radiating silent scrutiny.
4. **Момент:** sitting stiffly, a flicker of something softer crossing his usually strict face as he almost — but not quite — says he's proud.
5. **Деталь:** close-up of a sharply pressed suit collar and tie, composed jawline.

## Хосино Кэйта — отец Кенто (50)
**Внешность:** 50-year-old man, neat greying hair, serious composed features, appraising steady eyes, well-groomed, fit and trim.

1. **Лицо анфас:** front-facing, measured serious expression.
2. **Полный рост:** standing in smart-casual clothing, straight measured posture, hands clasped behind his back.
3. **Фирменная поза:** standing with arms crossed, watching someone across a room with a weighing evaluating expression.
4. **Момент:** sitting in a hospital waiting area, posture finally softening, a quiet realization crossing his face.
5. **Деталь:** close-up of a measured expression slowly softening at the edges.

## Хосино Сацуки — мать Кенто (47)
**Внешность:** 47-year-old woman, warm neatly-kept dark hair, kind soft eyes, a gentle well-cared-for face, an easy warm smile, average height.

1. **Лицо анфас:** front-facing, easy warm smile, kind eyes.
2. **Полный рост:** standing in soft elegant casual clothing, a warm approachable posture, hands folded gently in front.
3. **Фирменная поза:** gently nudging a taller man beside her with her elbow, a playful warm gesture, a knowing smile.
4. **Момент:** standing quietly beside her daughter, a supportive warm hand on the shoulder, calm reassuring presence.
5. **Деталь:** close-up of a warm gentle smile with soft kind eyes.

## Танака Мика — жена Танаки (42)
**Внешность:** 42-year-old woman, dark-chestnut hair in a loose practical bun, soft kind tired eyes, a round gentle face, a short soft build, usually in motion, wearing an apron.

1. **Лицо анфас:** front-facing, soft kind tired expression.
2. **Полный рост:** standing mid-step carrying something, simple practical home clothing with an apron.
3. **Фирменная поза:** setting a full plate of food down in front of someone without a word, a warm nurturing gesture, a gentle tired smile.
4. **Момент:** surrounded by several children at a dinner table, calm chaos, warm exhausted happiness on her face.
5. **Деталь:** close-up of soft tired hands setting down a plate of home-cooked food, warm steam rising.

---

# Приложение — локальный Stable Diffusion (если не GPT)

Актуально, если будешь генерить локально (Stability Matrix и т.п.), а не через GPT.

**Чекпойнты (Civitai):**
- 8 ГБ VRAM и больше (лучшее качество): **AnimagineXL 4.0** (SDXL/Illustrious) — чистый современный аниме-стиль, ближе всего к «Куроко/Хайкю». Альтернатива — **Nova Anime XL**.
- 4–6 ГБ VRAM / быстрее: **Counterfeit-V3.0** (SD1.5).

**Настройки (SDXL/Illustrious):** Euler a · 28–32 steps · CFG 5.5–6.5 · Clip Skip 2 · 832×1216 (портрет) / 1024×1024 (крупный план) · Hires ×1.5, denoise 0.35–0.45, 4x-AnimeSharp.
**Настройки (Counterfeit/SD1.5):** DPM++ 2M Karras · 25–30 steps · CFG 7–8 · Clip Skip 2 · 512×768 · Hires до 1024×1536, denoise 0.5.

**Теговый префикс:** `masterpiece, best quality, very aesthetic, absurdres, modern shounen anime style, clean lineart, cel shading, 1boy/1girl, solo, simple background` — дальше внешность персонажа тегами + вид кадра (portrait / full body / dynamic action pose / close-up).
**Консистентность в SD:** для видов 2–5 используй тот же якорь-кадр через **IP-Adapter** или **reference ControlNet** (в GPT это заменяется загрузкой картинки-референса).
**Негатив** — см. в начале файла.
