![version](https://img.shields.io/badge/version-1.0-red.svg?style=flat-square "Version Frontend-kit")
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/sinups/)


## Стартовый проект frontend-kit :fire:
:earth_asia: Cайт : http://codbox.ru

:boy:   Автор : [ A K ](https://www.instagram.com/webtheory/ "Instagram page")

## Browser Support

| <img src="https://clipboardjs.com/assets/images/chrome.png" width="48px" height="48px" alt="Chrome logo"> | <img src="https://clipboardjs.com/assets/images/edge.png" width="48px" height="48px" alt="Edge logo"> | <img src="https://clipboardjs.com/assets/images/firefox.png" width="48px" height="48px" alt="Firefox logo"> | <img src="https://clipboardjs.com/assets/images/ie.png" width="48px" height="48px" alt="Internet Explorer logo"> | <img src="https://clipboardjs.com/assets/images/opera.png" width="48px" height="48px" alt="Opera logo"> | <img src="https://clipboardjs.com/assets/images/safari.png" width="48px" height="48px" alt="Safari logo"> |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Latest ✔ | Latest ✔ | Latest ✔ | No ✕ | Latest ✔ | Latest ✔ |

## Стартовый репозиторий .
Установка: `npm i`.

Запуск: `npm start`.

Сборка - <b>Gulp 4</b>

Запуск конкретной задачи: `npm start имя_задачи` (список задач  в `gulpfile.js`)

Остановка: <kbd>Ctrl + C</kbd>

## Bывод svg sprite

`<svg class="custom-class" width="14px" height="14px"><use xlink:href="img/sprite-svg.svg#img_name"></use></svg>`

Или можете сделать include в верху сайта  ниже тега `Body`

`@@include('img/sprite-svg.svg')`

И выводить на странице таким образом:

`<svg  width="28"  height="28"  class="custom_class"><use  xlink:href="#image_name"></use></svg>`


## Bывод png sprite

Предоставленные миксины предназначены для использования с переменными

`
.icon-imagename {
  @include sprite($image_name);
}`

Пример использования в HTML:

`display: block` sprite:

`<div class="icon-imagename"></div>`

Изменитe `display` ( `display: inline-block;`), мы предлагаем использовать общий css класс:

CSS

`.icon {
  display: inline-block;
}`

HTML

`<i class="icon icon-home"></i>`
