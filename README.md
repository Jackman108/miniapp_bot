# Telegram MiniApp Bot

Это мини-приложение для Telegram, которое использует Telegram Bot API и WebApp для предоставления интерактивного опыта внутри Telegram. Бот позволяет пользователям открывать веб-приложение через интерфейс Telegram и предоставляет простой интерфейс для взаимодействия с ним.

## Основные функции

- Получение и отображение профиля пользователя Telegram.
- Возможность приглашать друзей через ссылку Telegram.
- Поддержка premium пользователей с отображением соответствующей иконки.

## Установка и запуск

### Предварительные требования

- Node.js версии 16.x или выше
- npm (Node Package Manager)
- Telegram Bot Token (можно получить, создав нового бота через BotFather в Telegram)

### Шаги по установке

1. **Клонируйте репозиторий:**

   ```bash
   git clone https://github.com/Jackman108/miniapp_bot.git
   cd miniapp_bot
   ```
2. **Установите зависимости:**

   ```bash
   npm install
   ```
3. **Настройте переменные окружения:**

Создайте файл .env в корневой директории и добавьте следующие переменные:

   ```plaintext
    TELEGRAM_BOT_TOKEN=your_telegram_bot_token
    APP_URL=https://jackman108.github.io/miniapp_tg/
    PORT=3000
    AVATAR_URL=https://i.shgcdn.com/432a91c0-438c-4aea-9581-6015be274fe0/-/format/auto/-/preview/3000x3000/-/quality/lighter/
    BOT_USERNAME=EasyMiniAppBot
   ```
Замените your_telegram_bot_token на ваш токен Telegram бота.

4. **Запустите сервер:**

Создайте файл .env в корневой директории и добавьте следующие переменные:

   ```bash
    npm start
   ```
Сервер будет запущен на порту 3000.

### Использование

1. Запустите бота в Telegram, отправив команду /start.

2. Нажмите кнопку "Открыть miniapp" для доступа к веб-приложению.

3. Вы можете пригласить друзей, нажав кнопку "Пригласить друга".

### Структура проекта

- index.html: Основная HTML-страница для miniapp.
- scripts.js: Скрипт для обработки данных пользователя и управления интерфейсом.
- server.js: Серверное приложение, написанное на Express.js, которое обрабатывает запросы от Telegram и пользователей.

### Зависимости

- dotenv: Для работы с переменными окружения.
- express: Для создания сервера.
- node-telegram-bot-api: Библиотека для работы с Telegram Bot API.
- eslint: Инструмент для анализа кода.
- nodemon: Для автоматического перезапуска сервера при изменениях.

### Лицензия

Этот проект лицензируется под лицензией ISC. Для получения дополнительной информации см. LICENSE.


### Объяснения:

- **Основные функции:** Описывает основные возможности бота.
- **Установка и запуск:** Пошаговая инструкция для запуска проекта, включая установку зависимостей и настройку переменных окружения.
- **Использование:** Объясняет, как взаимодействовать с ботом.
- **Структура проекта:** Краткое описание файлов и их функций.
- **Зависимости:** Список используемых npm-пакетов с кратким описанием.
- **Лицензия:** Указывает на лицензию проекта.

Если у вас есть дополнительные пожелания или изменения, дайте знать!