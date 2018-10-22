
## Стартовый проект frontend-kit :fire:
:earth_asia: Cайт : http://codbox.ru

:boy:   Автор : [ A K ](https://www.instagram.com/webtheory/ "Instagram page")

## Стартовый репозиторий .
Установка: `npm i`.

Запуск: `npm start`.

Сборка - <b>Gulp 4</b>

Запуск конкретной задачи: `npm start имя_задачи` (список задач  в `gulpfile.js`)

Остановка: <kbd>Ctrl + C</kbd>

## Bывод svg 

`<svg class="custom-class" width="14px" height="14px"><use xlink:href="img/sprite-svg.svg#img_name"></use></svg>`

Или можете сделать include в верху сайта  ниже тега `Body`

`@@include('img/sprite-svg.svg')`

И выводить на странице таким образом:

`<svg  width="28"  height="28"  class="custom_class"><use  xlink:href="#calendar"></use></svg>`




