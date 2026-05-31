# MicroWind CSS

Лёгкая utility-first CSS-библиотека без сборки, зависимостей и лишней магии.

![Версия](https://img.shields.io/badge/version-1.4.0-blue) ![Лицензия](https://img.shields.io/badge/license-MIT-green) ![Формат](https://img.shields.io/badge/zero--build-ready-orange)

## Что внутри

MicroWind — это один файл `microwind.css`, который можно:

- скачать и подключить локально;
- отдать напрямую по HTTPS после деплоя на GitHub Pages;
- использовать как набор атомарных utility-классов для layout, spacing, typography, colors, filters и states.

В версии `1.4` библиотека стала шире по возможностям:

- добавлены более полные `margin` и `padding` утилиты;
- появились `space-x-*` и `space-y-*`, а также новые значения вроде `p-9`, `p-14`, `p-18`, `m-7`, `gap-7`;
- добавлены новые display-режимы: `inline-grid`, `table`, `inline-table`, `table-row`, `table-cell`, `table-caption`, `table-column`, `flow-root`, `list-item`, `contents`;
- добавлены новые sizing helpers: `w-1/5`, `w-2/5`, `w-3/5`, `max-w-prose`, `max-w-screen-*`, `container-*`;
- расширены position utilities: `inset-auto`, `top-auto`, `left-auto`, `sticky`, `z-*` и базовые offset helpers;
- расширены flex/grid helpers: `basis-*`, `order-*`, `place-*`, `justify-items-*`, `grid-flow-*`, `flex-col-reverse`, `flex-wrap-reverse`;
- появились `font-serif`, `font-extrabold`, `text-9xl`, `line-clamp-*`, `antialiased`, `subpixel-antialiased`;
- добавлены surface-утилиты: `rounded-4xl`, `shadow-2xl`, `ring-purple`, `ring-rose`, `outline-*`;
- добавлены filter и backdrop-filter utilities: `blur-*`, `brightness-*`, `contrast-*`, `grayscale`, `sepia`, `saturate-*`, `backdrop-blur-*`;
- появились `transition-colors`, дополнительные hover/focus состояния и soft color backgrounds;
- расширена палитра: `sky`, `fuchsia`, `rose`, `slate`, `zinc`, `stone`;
- добавлены translate и hover-lift utilities для более живых интерфейсных состояний.

## Быстрый старт

Локально:

```html
<link rel="stylesheet" href="./microwind.css">
```

Через GitHub Pages:

```html
<link rel="stylesheet" href="https://stepankislin.github.io/repository/microwind.css">
```

## Примеры классов

```html
<div class="max-w-4xl mx-auto px-6 py-12">
  <div class="grid md:grid-cols-2 gap-6">
    <article class="p-6 rounded-2xl bg-white shadow space-y-4">
      <span class="bg-sky-10 text-sky px-3 py-1 rounded-full">new</span>
      <h2 class="text-3xl font-extrabold font-serif tracking-tight">MicroWind</h2>
      <p class="text-gray-600">Utility-first CSS без build step, с typography и glass-утилитами.</p>
      <button class="border border-sky text-sky px-5 py-3 rounded-xl hover:bg-sky hover:text-white transition-colors">
        Попробовать
      </button>
    </article>
  </div>
</div>
```

## Демо

В репозитории есть landing `index.html` с:

- более сильной презентацией библиотеки;
- отдельной ссылкой на `docs.html`;
- готовыми примерами utility-комбинаций;
- переработанной live playground-зоной;
- интерактивным showcase для motion/state/filter utilities;
- демонстрацией новых display, sizing, surface, typography, color и filter utilities;
- кнопкой скачивания CSS;
- блоком для копирования HTTPS-подключения под GitHub Pages.

Также есть отдельная документация `docs.html` с:

- боковой навигацией по разделам;
- таблицами и reference-блоками;
- отдельными секциями по display, spacing, layout, sizing, position, surfaces, colors, typography, filters, motion, states, composition, utility recipes и responsive;
- живыми интерактивными демо-компонентами.

