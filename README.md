# RabbitMQ Basics - Simple Send/Receive Example

Минимальный пример работы с RabbitMQ на C#: отправка и получение сообщений.

## Функционал
- ✅ Простой отправитель (Producer)
- ✅ Простой получатель (Consumer)
- ✅ Базовая конфигурация RabbitMQ
- ✅ Примеры с автоматическим и ручным подтверждением

## Быстрый старт
1. Запустите RabbitMQ: `docker-compose up`
2. Запустите получателя: `dotnet run --project src/Consumer`
3. Запустите отправителя: `dotnet run --project src/Producer`
