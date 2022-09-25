# API YaMDb

### Проект YaMDb собирает отзывы пользователей на фильмы, книги, музыкальные произведения.

### Технологии

> * Python 3.9
> * Django 2.2.16
> * Django REST Framework
> * Simple-JWT
> * Postgresql
### Примеры запросов:

Регистрация нового пользователя: POST http://51.250.78.208/api/v1/auth/signup/
```
{
  "email": "string",
  "username": "string"
}
```
Получение списка всех категорий: GET http://51.250.78.208/api/v1/categories/
```
[
  {
    "count": 0,
    "next": "string",
    "previous": "string",
    "results": [
      {
        "name": "string",
        "slug": "string"
      }
    ]
  }
]
```

Ознакомиться с полным функционалом и примерами можно по адресу http://51.250.78.208/redoc

### Автор:

[Алексей Курепин](https://github.com/AlexeyKurepin)

[![Django-app workflow](https://github.com/AlexeyKurepin/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)](https://github.com/AlexeyKurepin/yamdb_final/actions/workflows/yamdb_workflow.yml)
