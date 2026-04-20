# E-Commerce Platform MonoShop

## Описание
Монолитное Java-приложение, Spring Boot, PostgreSQL, развёрнуто на 3 VM за nginx load balancer.

## Модули
- Каталог товаров
- Корзина
- Оформление заказа
- Платежи
- Уведомления
- Отчёты
- Админка

## Проблемы
- Деплой всего приложения занимает 2 часа
- Падение одного модуля роняет всё
- Команды блокируют друг друга
- Нельзя масштабировать отдельные модули

## Текущий стек
- Java 17
- Spring Boot 3
- PostgreSQL 15
- Redis для кешей
- RabbitMQ для очередей
- nginx
- Jenkins CI

## Команда
- 4 backend-разработчика
- 2 frontend-разработчика
- 1 DevOps
- 1 QA

## SLA
- 99.9% uptime
- 200ms p95 latency
