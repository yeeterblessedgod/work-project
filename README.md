# YourProjectName — базовый сайт (ДЭ)

Магазин детских игрушек. Старт с авторизации/регистрации, роли: **Гость → Пользователь → Менеджер → Админ**.

## Запуск

```bash
npm install
npm start
```

Откройте: http://localhost:3000

## Тестовые аккаунты

| Логин   | Пароль      | Роль     |
|---------|-------------|----------|
| user    | user123     | user     |
| manager | manager123  | manager  |
| admin   | admin123    | admin    |

Гость: кнопка **«Войти как гость»** на странице входа.

## Структура

- `server.js` — сервер, API, роли, капча
- `public/login.html` — вход + капча + гость
- `public/reg.html` — регистрация + капча
- `public/catalog.html` — каталог по ролям
- `public/admin.html` — админ-панель (3 вкладки)
- `data/*.json` — данные (на экзамене можно заменить на БД)

## На экзамене

```cmd
git clone https://github.com/yeeterblessedgod/work-project.git
cd work-project
npm install
npm start
```

Замените **YourProjectName** на название из ТЗ.
