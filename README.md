# Task Tracker REST API

Backend-приложение для управления списком задач на Spring Boot.

## Стек технологий
* Java 27
* Spring Boot 4.1.2
* Spring Web (REST API)
* Spring Data JPA (Hibernate)
* H2 Database
* Maven

## Эндпоинты API
* GET /api/tasks - получить все задачи
* POST /api/tasks - создать задачу
* GET /api/tasks/{id} - получить задачу по ID
* DELETE /api/tasks/{id} - удалить задачу по ID

## Как запустить
1. Открыть проект в IntelliJ IDEA.
2. Запустить класс TaskTrackerApplication.
3. Сервер будет доступен на порту 8080.

## Как тестировать
Отправка запросов через Postman на http://localhost:8080/api/tasks

Пример JSON для создания задачи:
{
"title": "Посмотреть матч Барсы",
"description": "Включить трансляцию в 23:00",
"deadline": "2026-11-20"
}