# MicroWind CSS

Лёгкая utility-first CSS-библиотека без сборки, зависимостей и лишней магии.

![Версия](https://img.shields.io/badge/version-1.2.0-blue) ![Лицензия](https://img.shields.io/badge/license-MIT-green) ![Формат](https://img.shields.io/badge/zero--build-ready-orange)

## Что внутри

MicroWind — это один файл `microwind.css`, который можно:

- скачать и подключить локально;
- отдать напрямую по HTTPS после деплоя на GitHub Pages;
- использовать как набор атомарных utility-классов для layout, spacing, typography, colors и states.

В версии `1.2` библиотека стала шире по возможностям:

- добавлены более полные `margin` и `padding` утилиты;
- появились `space-x-*` и `space-y-*`;
- добавлены новые display-режимы: `inline-grid`, `table`, `table-row`, `table-cell`, `flow-root`, `list-item`;
- добавлены фракционные ширины, больше `max-width` и `height` значений;
- расширены flex/grid helpers: `basis-*`, `order-*`, `place-*`, `justify-items-*`, `flex-col-reverse`, `flex-wrap-reverse`;
- появились `transition-colors`, дополнительные hover/focus состояния и soft color backgrounds;
- расширена палитра: `sky`, `fuchsia`, `rose`, `slate`, `zinc`, `stone`;
- добавлены простые gradient utilities и несколько декоративных классов для landing-сценариев.

## Быстрый старт

Локально:

```html
<link rel="stylesheet" href="./microwind.css">
```

Через GitHub Pages:

```html
<link rel="stylesheet" href="https://username.github.io/repository/microwind.css">
```

## Примеры классов

```html
<div class="max-w-4xl mx-auto px-6 py-12">
  <div class="grid md:grid-cols-2 gap-6">
    <article class="p-6 rounded-2xl bg-white shadow space-y-4">
      <span class="bg-sky-10 text-sky px-3 py-1 rounded-full">new</span>
      <h2 class="text-3xl font-black tracking-tight">MicroWind</h2>
      <p class="text-gray-600">Utility-first CSS без build step.</p>
      <button class="border border-sky text-sky px-5 py-3 rounded-xl hover:bg-sky hover:text-white transition-colors">
        Попробовать
      </button>
    </article>
  </div>
</div>
```

## Демо

В репозитории есть landing `index.html` с:

- улучшенной презентацией библиотеки;
- отдельной ссылкой на `docs.html`;
- готовыми примерами utility-комбинаций;
- live playground;
- интерактивным showcase для motion/state utilities;
- демонстрацией новых display и color utilities;
- кнопкой скачивания CSS;
- блоком для копирования HTTPS-подключения под GitHub Pages.

Также есть отдельная документация `docs.html` с:

- боковой навигацией по разделам;
- таблицами и reference-блоками;
- отдельными секциями по display, spacing, layout, colors, motion, states и responsive;
- живыми интерактивными демо-компонентами.

## Лицензия

MIT
