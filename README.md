
# 🚀 TgBotGPT - Умный Telegram бот с базой знаний и VseGPT API 

[![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![aiogram Version](https://img.shields.io/badge/aiogram-3.x-blue.svg)](https://docs.aiogram.dev/)
[![OpenAI API](https://img.shields.io/badge/OpenAI-1.6.3-green.svg)](https://openai.com/)



 

Умный Telegram-бот с обширной базой знаний по программированию и искусственному интеллекту, с возможностью подключения к VseGPT API для ответов на сложные вопросы.

## 🔥 Ключевые особенности

- 📚 Локальная база знаний с 15+ готовыми ответами
- 🧠 Интеграция с VseGPT API для сложных вопросов
- ⚡ Быстрый отклик и интуитивное взаимодействие
- 🌐 Поддержка работы в Google Colab и локально
- 🔍 Умный поиск по базе знаний
- 🔄 Асинхронная архитектура на aiogram 3.x

## 🛠 Установка и настройка

### Предварительные требования
- Python 3.8 или новее
- Аккаунт в Telegram
- API ключ VseGPT

### 1. Клонирование репозитория
```bash
git clone https://github.com/yourusername/telegram-knowledge-bot.git
cd telegram-knowledge-bot
```

### 2. Установка зависимостей
```bash
pip install -r requirements.txt
```

### 3. Настройка окружения
Создайте файл `.env` в корне проекта:
```ini
TELEGRAM_BOT_TOKEN=ваш_токен_бота
VSEGPT_API_KEY=ваш_ключ_vsegpt_api
```

## 🏃 Запуск бота

```bash
python bot.py
```

Для работы в Google Colab:
1. Загрузите токены в секреты Colab
2. Запустите все ячейки ноутбука последовательно

## 📊 База знаний

### Основные категории вопросов
| Категория | Примеры вопросов | Количество ответов |
|-----------|------------------|-------------------|
| Telegram API | Как создать бота? Как работать с aiogram? | 3 |
| ИИ технологии | Что такое GPT-4? Как работают трансформеры? | 5 |
| Программирование | Какие языки учить? Как начать с Python? | 4 |
| Машинное обучение | Разница между ML и DL? Как создать нейросеть? | 3 |

## 💬 Примеры взаимодействия

```
Пользователь: Как создать Telegram бота?
Бот: Для создания Telegram бота нужно:
1. Зарегистрировать бота у @BotFather
2. Получить токен
3. Использовать библиотеку aiogram...
```

```
Пользователь: Объясни квантовые вычисления
Бот: (генерирует ответ через VseGPT API) 
Квантовые вычисления используют кубиты...
```



## 🤝 Как внести вклад

1. Форкните репозиторий
2. Создайте ветку для вашей фичи (`git checkout -b feature/AmazingFeature`)
3. Сделайте коммит изменений (`git commit -m 'Add some AmazingFeature'`)
4. Запушьте в ветку (`git push origin feature/AmazingFeature`)
5. Откройте Pull Request

## 📞 Контакты

Алина Грибанова – [@Alino4kaGribavova](https://t.me/Alino4kaGribavova)

📧 Email: [alinasgrib@gmail.com](mailto:alinasgrib@gmail.com)




