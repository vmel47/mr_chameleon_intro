# MR. CHAMELEON — GENERATION DATABASE · FULL RESET

Единая база всех генераций фильма: видеопромпты, стартовые изображения, референсы, location sheets,
персонажи и props. После полного reset ни один старый результат не считается готовым.

**Рабочий файл для вставки сохраняемых запросов по картинкам:**
`prompts/image/IMAGE_PROMPT_INBOX.md`.

Пользователь определяет, какой видеопромпт является последней актуальной версией. Агент не назначает
актуальный видеопромпт по дате файла или собственной оценке: после указания пользователя он заменяет
соответствующую версию и обновляет эту базу.

## Статусы

| Статус | Значение |
|---|---|
| `RESET` | Старый результат существует, но исключён из новой сборки; можно смотреть только как ориентир. |
| `CANDIDATE` | Старый промпт сохранён и может стать основой после проверки/переписывания. |
| `TODO` | Новый промпт или asset ещё не подготовлен. |
| `DRAFT` | Новый промпт подготовлен, но генерация не выбрана. |
| `SELECTED` | Выбран конкретный результат, но он ещё не прошёл continuity/stress test. |
| `LOCKED` | Результат утверждён и является единственным каноном для следующих генераций. |

Правило reset: старые видео, изображения и референсы никогда автоматически не получают `SELECTED` или
`LOCKED`. Каждый новый asset создаётся заново. Старый промпт можно переиспользовать только после явного
решения пользователя.

## A · Что уже имеет старый промпт-кандидат

| Новая сцена | Что | Старый промпт-кандидат | Статус промпта | Новый результат |
|---:|---|---|---|---|
| 01 | Глубокий лес | `prompts/current/01_deep_forest.md` | `CANDIDATE` | `RESET` |
| 02 | Лес → дорога | `prompts/current/02_forest_to_road.md` | `CANDIDATE` | `RESET` |
| 03 | Знак «Припять» | `prompts/current/03_pripyat_sign.md` | `CANDIDATE` | `RESET` |
| 04 | Улица внутри города | `prompts/current/04_city_entrance.md` | `CANDIDATE` | `RESET` |
| 05 | ДК «Энергетик» | `prompts/current/05_dk_energetik.md` | `CANDIDATE` | `RESET` |
| 06 | Парк: автодром | `prompts/current/06_park_bumper_cars.md` | `CANDIDATE` | `RESET` |
| 07 | Парк: колесо | `prompts/current/07_park_ferris_wheel.md` | `CANDIDATE` | `RESET` |
| 08 | Двор и вход в подъезд | `prompts/current/08_home_entry.md` | `CANDIDATE` | `RESET` |
| 09 | Вход в квартиру и обход | `prompts/current/09_apartment.md` | `CANDIDATE` | `RESET` |
| 10 | Панорама Припяти и ЧАЭС | `prompts/current/10_city_panorama.md` | `CANDIDATE` | `RESET` |
| 11, 12, 14, 16 | Камелеон у дома, один 20s source-ролик | `prompts/current/11_12_14_16_chameleon_reveal.md` | `CANDIDATE`, после character lock | `RESET` |
| 13, 15 | Подвал и проявление знаков, один 16s source-ролик | `prompts/current/13_15_basement_marks.md` | `CANDIDATE`, после character lock | `RESET` |
| 17, 18 | Зеркало и крик, один 20s source-ролик | `prompts/current/17_18_mirror_scream.md` | `CANDIDATE`, после character lock | `RESET` |

Слово `current` в старом пути означает только «последняя сохранённая версия до reset». Оно не означает,
что промпт уже утверждён для новой съёмки.

## B · Новые изображения и reference assets — создать заново

### B1 · Стартовые кадры и локации сцен 01–10

| Asset ID | Сцена | Что создать | Формат/назначение | Старый материал | Новый промпт | Новый asset |
|---|---:|---|---|---|---|---|
| `IMG-01-A` | 01 | Глубокий лес, начальная позиция POV | чистый 16:9 starting frame | есть старые forest refs/video | `TODO` | `RESET` |
| `IMG-02-A` | 02 | Тот же лес ближе к дороге | continuity starting frame | есть старые forest refs/video | `TODO` | `RESET` |
| `LOC-FOREST` | 01–02 | Общий forest location sheet, только нужные направления | 3/4 coverage + единый descriptor | старый `@loc_MC_forest` | новый запрос использован | `SELECTED` |
| `IMG-03-A` | 03 | Длинная прямая лесная дорога; знак ещё вне видимого участка | чистый starting frame | новый референс дороги от режиссёра | `prompts/image/IMAGE_PROMPT_INBOX.md`, раздел 03 | `DRAFT` |
| `LOC-SIGN` | 03 | Знак и его точная дорожная география | отдельный location-element для появления в видео | старые sign refs | `prompts/image/IMAGE_PROMPT_INBOX.md`, раздел LOC-SIGN | `DRAFT` |
| `IMG-04-A` | 04 | Заросшая улица внутри Припяти | чистый starting frame | старое city-entrance video | `TODO` | `RESET` |
| `LOC-STREET` | 04 | Панельные дома слева, лес справа, маршрут | location sheet/descriptor | старый `@loc_MC_pripyat_street` | старый кандидат требует обновления | `RESET` |
| `IMG-05-A` | 05 | Площадь и ДК «Энергетик» с нужной позиции | чистый starting frame | фото и старое video | `TODO` | `RESET` |
| `LOC-DK` | 05 | ДК и площадь в необходимых ракурсах | location sheet | старые DK refs | старый кандидат в `ASSET_GENERATION.md` | `RESET` |
| `IMG-06-A` | 06 | Автодром, первая позиция прохода | чистый starting frame | старые park-car refs/video | `TODO` | `RESET` |
| `IMG-07-A` | 07 | Колесо обозрения, первая позиция прохода | чистый starting frame | старые wheel refs/video | `TODO` | `RESET` |
| `LOC-PARK` | 06–07 | Единая география парка: автодром → колесо | location sheet | старый `@loc_MC_park` | старый кандидат в `ASSET_GENERATION.md` | `RESET` |
| `IMG-08-A` | 08 | Двор, фасад и вход в подъезд | чистый starting frame | `Videos/Home area/8.png` и другие тесты | `TODO` | `RESET` |
| `LOC-HOME-EXT` | 08, 11–12 | Дом, двор и подъезд, включая финальный ракурс | location sheet | старые home refs | кандидаты в архиве `TEST_LOC_SLOGAN_BLOCK.md` | `RESET` |
| `IMG-09-A` | 09 | Внутренняя лестничная площадка и дверь | чистый starting frame | старые apartment tests | `TODO` | `RESET` |
| `LOC-HOME-INT` | 09 | Тамбур, прихожая, спальня, зал, кухня | continuity/location sheet | старый план и тестовые комнаты | кандидат в архиве `TEST_07_APARTMENT.md` | `RESET` |
| `PLAN-09` | 09 | Канонический план квартиры с маршрутами и дверями | layout reference, не starting frame | `Videos/Home inside/Refs/Home_plan.png` | описать/пересобрать | `RESET` |
| `IMG-10-A` | 10 | Аэровид Припяти с географически верной ЧАЭС | starting frame либо keyframe | старых утверждённых кадров нет | `TODO` | `RESET` |
| `LOC-CITY` | 10 | Master city/ChNPP geography and atmosphere | aerial location sheet/descriptor | старый `@loc_MC_pripyat_city` | старый кандидат в `ASSET_GENERATION.md` | `RESET` |

### B2 · Персонажи и финал 11–18

| Asset ID | Тег | Что создать заново | Старый промпт | Новый asset |
|---|---|---|---|---|
| `CHAR-01` | `@char_MC_mr_chameleon_face` | нейтральный identity master без маски; в фильме не появляется | есть кандидат в `ASSET_GENERATION.md` | `RESET` |
| `CHAR-02` | `@char_MC_mr_chameleon` | залоченный образ в одежде и неизменной полумаске | есть кандидат | `RESET` |
| `CHAR-03` | `@char_MC_employee` | базовая сотрудница | есть кандидат | `RESET` |
| `CHAR-04` | `@char_MC_employee_civil` | то же лицо, гражданская одежда | есть кандидат | `RESET` |
| `CHAR-05` | `@char_MC_employee_signs` | то же лицо/форма, знаки только на теле | есть кандидат | `RESET` |
| `PROP-01` | `@prop_MC_signs` | библиотека рисунка и поведения знаков | есть кандидат | `RESET` |
| `LOC-BASE-01` | `@loc_MC_basement` | подвал, camera position 1 | есть кандидат | `RESET` |
| `LOC-BASE-02` | `@loc_MC_basement_rev` | тот же подвал, reverse camera position 2 | есть кандидат | `RESET` |
| `IMG-11-A` | сцены 11–12 | финальный внешний keyframe: дом + Камелеон | создать после `CHAR-02` и `LOC-HOME-EXT` | `RESET` |
| `IMG-13-A` | сцены 13–16 | подвал + сотрудница, первый финальный keyframe | создать после `CHAR-03` и `LOC-BASE-01` | `RESET` |
| `IMG-17-A` | сцены 17–18 | зеркало с двумя идентичными лицами | создать после joint stress test `CHAR-03/04` | `RESET` |

### B3 · Не входит в обязательную новую сборку

| Asset | Причина |
|---|---|
| Duga fragment | Опциональный эпизод; не создавать без возвращения сцены в shortlist. |
| School and shop | Удалены из текущего монтажа. Старые промпты оставить в архиве. |

## C · Карточка каждого нового промпта

При подготовке нового изображения или видео добавлять запись:

```text
Asset/Scene ID:
Date and version:
Target model:
Input mode: text-to-image / reference edit / image-to-video / text-to-video
Reference roles:
Prompt file:
What was inherited from an old candidate:
What was rewritten:
Output file/link:
Verdict: reject / iterate / selected / locked
Failure observed:
Next single change:
```

## D · Порядок новой сборки

1. Пересобрать и залочить единый look/weather descriptor.
2. `LOC-FOREST` уже выбран; отдельно подготовить стартовые кадры `IMG-01-A`, `IMG-02-A`, если они понадобятся.
3. Сгенерировать чистый стартовый кадр `IMG-03-A` и отдельный элемент `LOC-SIGN`, затем двигаться последовательно по сценам `03–10`, не перескакивая через незалоченную географию.
4. Параллельно после утверждения look начать character sheets `CHAR-01–05` и stress tests.
5. Только после location/character lock собирать keyframes и видеопромпты `11–18`.

Пользователь может вручную менять статусы и вставлять выбранные промпты/ссылки прямо в этот файл. Агент
обязан считать этот файл базой учёта и синхронизировать итоговые статусы с `PRODUCTION.md`.
