//------------------------------------------------------------------------------

Документация шаблона: 
https://template.fls.guru/template-docs 
https://legosite.kz/ts/fls/
Спасибо Жене Андриканичу.

//------------------------------------------------------------------------------

Команды терминала

Если gulp не установлен на новом ПК, то выполнить команду:
npm i gulp-cli -g

//------------------------------------------------------------------------------

Установка:
npm i

Шаблон «Чертоги Фрилансера» может выполнять несколько сценариев:

Дополнительные команды:
1. Режим разработчика. Команда запуска npm run dev
2. Режим продакшена. Команда запуска npm run build
3. Режим продакшена и отправка результата на сервер по FTP. Команда запуска npm run deploy
4. Режим продакшена и создание ZIP-архива с результатом. Команда запуска npm run zip
5. Режим продакшена без создания WEBP изображений и действий связанных с этим форматом. Команда запуска npm run devbuild

Дополнительные команды:
1. Ручное создание SVG спрайта. Команда запуска npm run sprite
2. Конвертация шрифтов с принудительной перезаписью файла стилей. Команда запуска npm run fonts

//------------------------------------------------------------------------------

Основные файлы для работы с шаблоном:
js/app.js
js/files/script.js - для написания своего кода для проекта
scss/style.scss

index.html - разводящая страница (содержание)
home.html - главная страница
файлы *.htm - подключаемые части

//------------------------------------------------------------------------------

Подключение шрифтов:
1. Загрузить файлы шрифтов в папку src/fonts
2. Запустить сревер npm run dev
3. В файле scss/base/fonts настроить: значение 1 (семейство шрифта в один стиль), и значение 3 (числовые значения жирности шрифта)

//------------------------------------------------------------------------------




При возникновении ошибок убедитесь что:
1) У вас установлен Node.js последней версии
2) Терминал открыт с правами администратора
3) В названиях папок на всем пути к проекту нет символа #