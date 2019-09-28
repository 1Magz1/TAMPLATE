# TAMPLATE
## Шаблонизатор для верстки

Для использования данного шаблонизатора необходимо:
1. Установить [Node.js](https://nodejs.org/en/)
2. Установить [Gulp](https://gulpjs.com/)
3. После установки зайти в основную папку
4. Запустить консоль
5. Ввести команду npm i
6. Затем gulp
7. ???
8. PROFIT

Структура папок:
1. pug
- *layout* - Основной шаблон для создания страниц.
- *modules* - Подключаемые модули (Header, Footer и т.д.). Блоки, которые используются на сайте постоянно.
- *pages* - Страницы сайта.
2. static
- *css* - Здесь хранится общий CSS файл. В нем будут храниться стили после сборки проекта.
- *fonts* - Подключаемые шрифты. Шрифты подключатся через fonts.css
- *img* - Там находятся все изображения используемые в проекте.
- *js* - Свои скрипты пишем в main.js
- *libs* - Подключенные библиотеки, такие как Slick Slaider. Подключать JS файлы библиотек в файле gulpfile.js в разделе Работа JS.
- *stylus* - Стили. Используется препроцессор Stylus.


### gulp build - Собрать проект. Файлы проекта будут находится в папке Product
