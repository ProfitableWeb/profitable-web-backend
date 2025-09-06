# ProfitableWeb Backend

> 🐍 Python FastAPI backend для исследовательского блога по монетизации хобби

## 📋 Обзор

Backend API для платформы ProfitableWeb - исследовательского проекта, документирующего insights о генерации финансового капитала из личных хобби.

## 🛠️ Технологический стек

- **Framework**: FastAPI
- **Language**: Python 3.11+
- **Dependency Management**: Poetry
- **Database**: PostgreSQL + SQLAlchemy
- **Cache**: Redis
- **Code Quality**: black, isort, flake8, mypy
- **Testing**: pytest
- **Deployment**: Docker

## 🚀 Quick Start

**⚠️ Проект в стадии подготовки** - окружение разработки еще не развернуто.

Когда будем готовы к разработке backend:

```bash
# Установка зависимостей
poetry install

# Запуск development сервера
poetry run uvicorn main:app --reload --port 8000

# Запуск тестов
poetry run pytest

# Форматирование и проверки
poetry run black .
poetry run isort .
poetry run flake8
poetry run mypy .
```

## 📚 API Документация

- **Swagger UI**: http://localhost:8000/docs
- **ReDoc**: http://localhost:8000/redoc

## 📁 Структура проекта

```
app/
├── api/          # API endpoints
├── core/         # Конфигурация
├── models/       # SQLAlchemy модели
├── schemas/      # Pydantic схемы
├── services/     # Бизнес логика
└── utils/        # Утилиты
```

## 🔧 Development

- [Development Plan](./docs/development_plan.md) - План разработки
- [Central Documentation](../profitable-web-docs/) - Центральная документация проекта

## 🔗 Links

- **Central Docs**: [profitable-web-docs](../profitable-web-docs/)
- **Frontend**: [profitable-web-frontend](../profitable-web-frontend/)
- **Admin Panel**: [profitable-web-admin](../profitable-web-admin/)

---

*Backend для исследования монетизации хобби* 💰