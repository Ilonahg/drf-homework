# Django DRF Homework Project

## 📚 Описание

Учебный Django-проект с использованием Django REST Framework. Реализованы модели курсов и уроков, кастомный пользователь с авторизацией по email. Настроены CRUD API с помощью ViewSet и Generic Views.

---

## 🧩 Функциональность

- Кастомная модель пользователя (`email`, `phone`, `city`, `avatar`)
- Модель курса: `title`, `description`, `preview`
- Модель урока: `title`, `description`, `video_url`, `preview`, связь с курсом
- CRUD API:
  - Курсы — через `ViewSet`
  - Уроки — через `GenericAPIView`
- Тестирование API через Postman
- Поддержка загрузки изображений
- Подключение DRF

---

## 🚀 Установка и запуск

1. Клонируйте репозиторий:

```bash
git clone https://github.com/ТВОЙ_ЛОГИН/ИМЯ_РЕПОЗИТОРИЯ.git
cd ИМЯ_РЕПОЗИТОРИЯ

создание ссилки на пр