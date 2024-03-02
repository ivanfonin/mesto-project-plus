# Бэкенд Mesto. API

## Используемые технологии и решения
- Typescript в качестве основного языка проекта
- Mongodb и ODM Mongoose для хранения данных пользователей
- Node.js в качестве среды выполнения

## Инструкции по установке
Для клонирования приложения выполните команду:\
`git clone https://github.com/ivanfonin/mesto-api/`

После клонирования приложения запустите команду `npm run init`, данная команда установит зависимости приложения `npm install` и скопирует файл `.env.example` в `.env`, после чего отредактируйте базовые настройки приложения в `.env`.

Для генерации JWT_SECRET из .env используйте команду в консоли:\
`node -e "console.log(require('crypto').randomBytes(32).toString('hex'));"`