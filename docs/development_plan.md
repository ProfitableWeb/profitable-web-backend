# Backend Development Plan

> 📚 **Центральная документация**: [profitable-web-docs](../profitable-web-docs/)
> 📋 **Общий roadmap**: [DEVELOPMENT_ROADMAP.md](../profitable-web-docs/DEVELOPMENT_ROADMAP.md)
> 🏗️ **Архитектура**: [SYSTEM_OVERVIEW.md](../profitable-web-docs/architecture/SYSTEM_OVERVIEW.md)

## 🏗️ Архитектура Backend
- **Framework**: FastAPI
- **Database**: PostgreSQL + SQLAlchemy ORM
- **Package Manager**: Poetry
- **Authentication**: JWT tokens
- **Deployment**: Docker + uvicorn

## 📋 Задачи

### Инициализация проекта
- [ ] Poetry инициализация (pyproject.toml)
- [ ] FastAPI настройка
- [ ] Pre-commit hooks (black, isort, flake8, mypy)
- [ ] Конфигурация базы данных
- [ ] Структура проекта
- [ ] Docker setup

### Модели данных
- [ ] Article (статьи блога)
- [ ] Category (категории)
- [ ] Tag (теги)
- [ ] Analytics (метрики)
- [ ] User (пользователи/авторы)

### API Endpoints
- [ ] `/api/articles` - CRUD операции
- [ ] `/api/categories` - управление категориями
- [ ] `/api/analytics` - метрики и статистика
- [ ] `/api/auth` - авторизация

### Интеграции
- [ ] WordPress migration API
- [ ] Analytics tracking
- [ ] External APIs (social media)

## 🔧 Технические детали

### Database Schema
```sql
-- Базовые таблицы будут созданы через SQLAlchemy migrations
```

### Environment Variables
```env
DATABASE_URL=postgresql://...
JWT_SECRET=...
CORS_ORIGINS=...
```

## 🔗 Полезные ссылки

- [Setup Guide](../profitable-web-docs/development/SETUP_GUIDE.md) - Инструкции по настройке
- [System Overview](../profitable-web-docs/architecture/SYSTEM_OVERVIEW.md) - Обзор архитектуры
- [API Design](../profitable-web-docs/architecture/API_DESIGN.md) - Дизайн API

---
*Обновляется по мере разработки*