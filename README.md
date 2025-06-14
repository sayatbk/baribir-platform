# BariBir Platform

📌 Платформа для поиска мероприятий и общения по интересам.

## 🧱 Архитектура

- `auth-service` — регистрация, логин, JWT
- `user-service` — профиль, интересы, друзья
- `event-service` — мероприятия, участие, фильтрация
- `chat-service` — личные и групповые чаты (Redis + WebSocket)
- `gateway` — входная точка, маршрутизация запросов

## 🐳 Запуск

```bash
docker-compose up --build
