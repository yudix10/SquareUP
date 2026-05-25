# SquareUp pixel layout

Готовая статическая верстка лендинга SquareUp на Gulp + SCSS.

## Запуск

```bash
npm install
npm run dev
```

## Сборка

```bash
npm run build
```

После сборки готовые файлы находятся в папке `dist/`.

## Что сделано

- восстановлена сборка Gulp;
- исправлены include-пути и битый `dist/index.html`, где часть страницы была закомментирована;
- сверстаны секции: hero, trusted companies, services, why choose, testimonials, FAQ, CTA, footer;
- добавлена адаптация под планшет и мобильный;
- ассеты используются в WebP, чтобы сборка не зависела от нативных WebP/Sharp-бинарников.
