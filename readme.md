# Задание

## Тестовое задание Laravel

Создадим простой микро-сервис регистрации и авторизации через Google.

### Компоненты:

- Laravel (свежая версия)
- Redis
- PostgreSQL
- PGadmin
- Nginx

### Вводное:

Все тестовое задание должно разворачиваться одной командой `docker-compose up -d` автоматически с прохождением тестов в конце.

### База данных

Также должны развернуться все миграции, сиды. Используйте модель Users, ORM, мягкое удаление и временные метки.

### Стратегии авторизации

Необходимо создать 2 стратегии авторизации:
- По email и паролю (Дефолтная в Laravel)
- По google auth 2.0

### Загрузка на GitHub

- Загрузить на гитхаб в публичный репозиторий
- И прислать нам ссылку на репозиторий.

Желаем Вам удачи!
