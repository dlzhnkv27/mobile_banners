# Ivideon Mobile Banners

Мобильный прототип iOS‑приложения на [Framework7](https://framework7.io/).

## Запуск

Откройте `index.html` в браузере или поднимите локальный сервер:

```bash
cd Ivideon_Mobile_Banners
npx serve .
# или: python3 -m http.server 8080
```

Для вида под iPhone удобно открыть DevTools (F12) → Toggle device toolbar и выбрать устройство iOS.

## Стек

- **Framework7 v8** — UI‑фреймворк (тема iOS, подключение через CDN)
- Один HTML‑файл с инициализацией приложения

## Структура

- `index.html` — разметка и инициализация приложения (view, navbar, toolbar, страница)

Дальше можно добавлять страницы, баннеры и компоненты по [документации Framework7](https://framework7.io/docs/).
