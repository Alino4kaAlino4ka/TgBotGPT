# TgBotGPT

# Telegram Knowledge Bot with VseGPT API

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![aiogram](https://img.shields.io/badge/aiogram-3.x-blue)](https://docs.aiogram.dev/)
[![OpenAI](https://img.shields.io/badge/OpenAI-1.6.3-green)](https://openai.com/)

Телеграм-бот с базой знаний по программированию и искусственному интеллекту, интегрированный с VseGPT API для ответов на вопросы.

## 📌 Особенности

- Локальная база знаний с 15+ ответами по темам программирования и ИИ
- Интеграция с VseGPT API для ответов на вопросы вне базы знаний
- Команды `/start` и `/help` для навигации
- Асинхронная реализация с использованием aiogram 3.x
- Готов к работе в Google Colab и на других платформах

## ⚙️ Установка и настройка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/yourusername/telegram-knowledge-bot.git
   cd telegram-knowledge-bot
Установите зависимости:

bash
pip install aiogram openai==1.63.0 nest_asyncio
Настройте переменные окружения:

Создайте файл .env со следующим содержимым:

TELEGRAM_BOT_TOKEN=ваш_токен_бота
VSEGPT_API_KEY=ваш_ключ_vsegpt_api
🚀 Запуск бота
bash
python bot.py
Для работы в Google Colab:

Добавьте токены в секреты Colab (TELEGRAM_BOT_TOKEN и VSEGPT_API_KEY)

Запустите все ячейки ноутбука

🗃️ Структура базы знаний
База знаний содержит ответы по следующим темам:

Создание Telegram ботов

Основы ChatGPT и GPT-4

Работа с API VseGPT

Языки программирования

Машинное и глубокое обучение

Нейронные сети

Блокчейн технологии

Фреймворки для ML

Компьютерное зрение

Рекомендательные системы

Облачные платформы ИИ

Трансформеры в ML

Обработка естественного языка (NLP)

🤖 Примеры вопросов
Как создать Telegram бота?
Что такое ChatGPT?
Как работает API VseGPT?
Какие языки программирования лучше изучать в 2025 году?
В чем разница между машинным обучением и глубоким обучением?
📄 Лицензия
Этот проект распространяется под лицензией MIT. См. файл LICENSE для получения дополнительной информации.

✉️ Контакты
По вопросам сотрудничества или поддержки:

Email: alinasgrib@gmail.com

Telegram: https://t.me/Alino4kaGribavova

