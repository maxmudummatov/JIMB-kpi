
# JIMB KPI — Система оценки сотрудников

## Что включено:
- Регистрация и авторизация
- Роли: админ, начальник, сотрудник
- Задания с дедлайном
- Отправка файлов (начальник и сотрудник)
- Оценки и баллы
- Интерфейс на русском языке
- PostgreSQL

## Запуск

1. Установите зависимости:

```bash
cd server
npm install

cd ../client
npm install
```

2. Создайте файл `.env` в папке `server` и укажите строку подключения к PostgreSQL:

```
DATABASE_URL=postgresql://username:password@host:port/dbname
```

3. Запустите backend:

```bash
cd server
npm start
```

4. Запустите frontend:

```bash
cd client
npm start
```

Готово!
