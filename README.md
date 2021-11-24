## Тестовое задание на PHP
- Реализовать сервис чеклистов с админкой на RestAPI
## Описание
Сервис чеклистов, написанный на Laravel, имеющий админку, 
который работает исключительно на RestAPI.
## Подготовительные действия
- Клонировать проект `git clone https://github.com/hvckxm/mediasoft-checklist-laravel -b develop`
- Создать .env файл в директории проекта и настроить его.
- Установить зависимости, используя команду `composer install`
- Установить ключ проекта командой `php artisan key:generate`
- Запустить миграции командой `php artisan migrate`
- Запустить сидер, командой `php artisan db:seed`
## Доступ в админку
- Чтобы выдать админку, нужно прописать команду `php artisan voyager:admin your@email.com`
## Описание, как запустить проект
Чтобы запустить проект, нужно 
- расположить его в директории 
сайтов локального веб-сервера (OpenServer, LAMP, MAMP). 
- Указать путь к домену `mediasoft-checklist-laravel/public`
- запустить локальный веб сервер
