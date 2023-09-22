# Тестовое задание на PHP Dev
Спроектировать и реализовать БД и сервис для библиотеки
В бд заложить возможность хранить книги(может быть больше 1 экземпляра), возможность поиска по автору(авторов может быть не 1), возможность выдать книгу читателю, возможность списать книгу(утрата и тд).
Должны быть следующие методы.

- Добавить книгу с указанием авторов
- Получить все книги
- Выдать книгу читателю
- Списать книгу

## Использование
1. Склонировать репозиторий
2. Запустить docker-compose up -d
3. Зайти в контейнер php-fpm `docker exec -it stream_php bash`, зайти в папку проекта `cd mysite.local` и запустить `composer install` . Composer нужен для автозагрузки, других зависимостей нет.
4. Открыть в браузере http://mysite.local

## Наполнение базы данных
Для первичного наполнения БД приложен SQL-дамп в папке sqldump. Он должен импортироваться при первом запуске контейнера, но, если что, то вы знаете, что он тут )
