# Кодстайл Mitorun Studio

Стиль написания кода в Mitorun Studio.

## Общее

Использовать редактор кода [VSCode](https://code.visualstudio.com/). В редакторе использовать файл с настройками `settings.json` (включая кастомные настройки цветов редактора), свои студийные добавления в сниппеты Emmet, файл шпаргалки с частоиспользуемыми текстами (все закреплены во вкладках).

Использовать файл настроек [.editorconfig](https://editorconfig.org/).

Во всех файлах использовать отступ в виде таба длиной в 2 пробела.

Для большинства сайтов использовать студийный шаблон с начальными файлами. Он включает конфиг `Eleventy`, файл `styles.css` с начальными стилями, папку с исходниками `SOURCE`...



## HTML

...



## CSS

- Для сайтов студии используется свой начальный код CSS.

- Не использовать селекторы `#id`.

- При использовании нескольких селекторов для одного правила каждое начинается с новой строки.

- Перед `{` ставить пробел в объявлении правила.

- В свойствах после `:` добавлять пробел.

- В конце объявления правила символ `}` переносить на новую строку.

- Между объявлениями правил (и строками-комментариями) добавлять пустую строку.

- Свойства в каждом правиле должны быть расположены в условленном порядке. Сам порядок перечислен в конфиге [`StyleLint`](https://stylelint.io/).

- Все цвета в свойствах должны быть в формате `hsl/hsla`.

- Медиазапросы в новом формате `@media (width >= 576px)`

- Перед стилями новой страницы или важного большого блока (например компонента) ставить такой заголовок комментарием:
```css
/*================================================
=== Страница Блог /blog/: ========================
================================================*/
```

- Классы (и идентификаторы?) для JS лучше не смешивать с CSS, можно использовать префикс `.js-`.



## JS

...



## Дополнительная информация

- [Кодгайд Google](https://google.github.io/styleguide/htmlcssguide.html).
- [Кодстайл HTML Academy](https://codeguide.academy/).
- [Кодгайд CSS от Airbnb](https://github.com/airbnb/css).
- [https://cssguidelin.es/](https://cssguidelin.es/).
- [https://css-live.ru/verstka/do-not-close-tags.html](https://css-live.ru/verstka/do-not-close-tags.html).
- [https://github.com/necolas/idiomatic-css](https://github.com/necolas/idiomatic-css)
- [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)
- [https://codeguide.co/#css](https://codeguide.co/#css)
- [https://piccalil.li/blog/a-modern-css-reset/](https://piccalil.li/blog/a-modern-css-reset/)
