# Sleep Animal 🐾

Мини-игра: введи, сколько часов ты спал, и узнай, какое ты сегодня животное.
Работает на телефоне (мобильная вёрстка).

## Локальный запуск

```bash
npm install
npm start
```

Открой http://localhost:3000

## Деплой на Railway

1. Запушь этот репозиторий на GitHub.
2. На Railway: **New Project → Deploy from GitHub repo** и выбери этот репозиторий.
3. Railway сам определит Node.js, выполнит `npm install` и `npm start`.
   Порт берётся из `process.env.PORT` — ничего настраивать не нужно.
4. В настройках сервиса нажми **Generate Domain**, чтобы получить публичную ссылку.
