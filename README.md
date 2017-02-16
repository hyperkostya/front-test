Установка всех модулей

npm install

less и jstemplate собираются вызовом grunt

TypeScript собирается вызовом tsc


Если не используется веб-сервер, чтобы работали ajax запросы в хроме:
https://stackoverflow.com/questions/4819060/allow-google-chrome-to-use-xmlhttprequest-to-load-a-url-from-a-local-file


Не надо делать проект с нуля. Клонируем этот репозиторий 

Там уже всё окружение сборки проекта настроено

Вызываем на склонированном репозитории 

npm install


Ставим глобально

npm install -g grunt

npm install -g typescript

После этого вызов grunt - собирает less и mustcahe
Вызов tsc - собирает typescript


Меняем код в 
js/ts/testDrawer.ts
jstemplate/test.tpl
less/main.less
вызываем после этого grunt/tsc, обновляем index.html - видим измененное.

Отмечаем что взялись задание на борде https://trello.com/invite/user11739125/737d5c7c1f8772c6c26bb966314df33f - делаем карточку со своим именем передвигаем в "взяли задание"

По проверке заданий звонить Жене Сташишину, 990-034-071
