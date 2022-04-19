
## Тестовое задание

### Что делает?
[Описание задачи](./docs/TASK.md) 

### Как запустить?

```shell
# Собираем
cd build
docker-compose build
# Запускаем
docker-compose start    
# Останавливаем
docker-compose stop
```

Запускаются два сервиса:
* **multiplexer** (на порту 8990) - сервис который требовалось разработать по условиям задачи;
* **stub** (на порту 8991) - сервер-заглушка принимающий запросы и отвечающий за рандомное время не больше указанного в запросе лимита;

### Как проверить?
В [директории ./docs/](./docs/) можно найти файлы с примерами запросов
