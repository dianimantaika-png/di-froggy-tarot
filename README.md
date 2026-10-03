# di.froggy — Tarot reading landing page

🔗 Сайт: https://dianimantaika-png.github.io/di-froggy-tarot/

Одностраничный двуязычный (RU/EN) сайт-визитка таролога. Весь сайт — один файл [`index.html`](index.html): HTML, CSS и JS внутри, без сборки и зависимостей.

## Что редактировать

Всё отмечено комментариями в начале `index.html` и в начале `<script>`:

- **Расписание окон** — `SCHEDULE_CONFIG`
- **Цены** — `PRICING_CONFIG`
- **Ссылка на Instagram** — `INSTAGRAM_URL`
- **Все тексты (RU/EN), отзывы** — объект `I18N`

## Публикация изменений

Сайт раздаётся через GitHub Pages из ветки `main`. Любой пуш в `main` пересобирает сайт автоматически (обычно 1–2 минуты):

```bash
git add index.html
git commit -m "Update content"
git push
```
