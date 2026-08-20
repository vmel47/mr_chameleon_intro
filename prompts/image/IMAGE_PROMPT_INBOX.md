# IMAGE PROMPT INBOX

**Сюда пользователь вставляет запросы на создание и редактирование картинок, которые нужно сохранить.**

Ничего из этого файла не становится каноном автоматически. После выбора результата статус меняется на
`SELECTED`, а после проверки связности — на `LOCKED`. Общий учёт assets ведётся в
`../../GENERATION_DATABASE.md`.

## Как добавлять

Для каждого нового запроса скопируй блок ниже в конец файла и вставь полный промпт без сокращений.

````markdown
---

## IMAGE PROMPT · [название]

- **Asset ID:** IMG-XX / LOC-XX / CHAR-XX / PROP-XX
- **Scene:** 01–18 или GLOBAL
- **Purpose:** starting frame / location sheet / character sheet / prop / edit / reverse angle
- **Model:** Soul Cinema / Soul 2.0 / AI Cast / Nano Banana Pro / Seedream / GPT Image 2 / другое
- **Input references:** нет или `@Image 1` — его единственная роль
- **Status:** SAVED
- **Selected output:** пока нет
- **Notes:** что именно понравилось или что надо сохранить

### Prompt

```text
ВСТАВИТЬ ПОЛНЫЙ ЗАПРОС СЮДА
```
````

## INBOX

Вставляй новые блоки ниже этой строки. Можно прислать промпт мне в чат — я сам добавлю его сюда,
назначу Asset ID и синхронизирую статус с `GENERATION_DATABASE.md`.

---
