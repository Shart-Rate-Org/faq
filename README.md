# Shart Rate FAQ

Публичная справка https://faq.shart-rate.com (перенесена с GitBook 06.11.2026).

- Статьи: `docs/*.md` (RU), `docs/kz/*.md` (KZ), картинки `docs/assets/img/`.
- Меню: `nav` в `mkdocs.yml`.
- Локально: `pip install -r requirements.txt && mkdocs serve`.
- Деплой: push в `main` → GitHub Actions → GitHub Pages.
- После правки `docs/stylesheets/brand.css` обновите `?v=` в `extra_css` (`shasum docs/stylesheets/brand.css | cut -c1-8`), иначе браузеры до 4 ч держат старый CSS.
