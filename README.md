# shikaku-site

Сайт игры Shikaku. Отдаётся GitHub Pages.

Сейчас здесь одна страница — политика конфиденциальности, в корне:
`https://anuarars.github.io/shikaku-site/`.

**Здесь её не редактируют.** Исходник живёт в основном репозитории
(`anuarars/shikaku`, `store/privacy/*.md`), страница собирается из него:

```
dart run tool/render_privacy.dart <путь к этому репозиторию>
```

Правка прямо здесь разойдётся с исходником — и разойдётся молча.
