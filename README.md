# Todo List — Flask + SQLite in Docker

Простое веб-приложение для управления списком задач.

## Технологии
- Python 3.11
- Flask 3.0
- SQLite (данные хранятся в контейнере)
- Docker

## Запуск

```bash
docker build -t todo-app .
docker run -d --name todo -p 5000:5000 todo-app
