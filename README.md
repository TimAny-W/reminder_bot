# Reminder Bot
Этот проект помогает сохранить напоминания в
базе данных при помощи телеграмм-бота.
Так же представляет простой REST-API для обращения,извлечения и добавления напоминаний

## Установка

1. Клонирование репозитория:
    ```shell
    git clone https://github.com/TimAny-W/reminder_bot

2. Установка библиотек и модулей:
    ```shell
    pip install -r requirement.txt

3. Создание и активация виртуального окружения (Windows):
    ```shell
   python -m venv venv
   cd venv/Scripts
   activate.bat

4. Настройка /config/config.ini
* **BOT_TOKEN** - Токен бота из @BotFather
* **HOST_URL** - Ссылка на домен
* **ADMIN_ID** - ID администратора бота
* **TIME_DELTA** - Отклонение часового пояса от UTC (в часах)

## Запуск проекта
   ```shell
   uvicorn app.main: app --reload
   ```
## Контакты 
* Telegram: [@timaynk](https://t.me//timaynk)
