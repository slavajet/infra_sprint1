# Kittygram - Социальная сеть для обмена фотографиями любимых питомцев

Kittygram - это проект, который представляет собой социальную сеть, специализирующуюся на обмене фотографиями и историями о ваших любимых питомцах, основанный на Django и React.

## Возможности

- Регистрация и авторизация пользователей.
- Добавление новых фотографий ваших питомцев или изменение уже существующих записей.
- Просмотр фотографий и историй других пользователей.
- Дружелюбный и интуитивно понятный интерфейс, разработанный с использованием React.

## Требования

Для запуска проекта требуется установить следующие зависимости:

- Django==3.2.3
- djangorestframework==3.12.4
- djoser==2.1.0
- webcolors==1.11.1
- Pillow==9.0.0
- pytest==6.2.4
- pytest-django==4.4.0
- pytest-pythonpath==0.7.3
- gunicorn==21.2.0
- django-cors-headers==4.2.0
- python-dotenv==1.0.0

## Установка

1. Клонируйте репозиторий:

```
git clone https://github.com/yourusername/kittygram.git
cd kittygram
```

2. Установите зависимости. Рекомендуется создать виртуальное окружение перед установкой зависимостей.

```
pip install -r requirements.txt
```

3. Примените миграции для базы данных:

```
python manage.py migrate
```

4. Запустите сервер разработки:

```
python manage.py runserver
```

5. Перейдите в директорию с фронтенд-приложением и установите зависимости:

```
cd frontend
npm install
```

6. Запустите фронтенд-сервер:

```
npm start
```

Теперь вы можете открыть браузер и перейти по адресу [http://localhost:3000/](http://localhost:3000/), чтобы начать использовать Kittygram.

## Вклад

Если вы хотите внести свой вклад в проект, пожалуйста, создайте форк репозитория, внесите необходимые изменения и отправьте пул-реквест. Мы рады принять любую помощь!

## Лицензия

Проект распространяется под лицензией [MIB](LICENSE).

---

Этот README предоставляет обзор функциональности и инструкции для установки и вклада в проект Kittygram. Если у вас возникли вопросы, не стесняйтесь связаться с нами по адресу support@kittygram.com. Спасибо, что выбрали Kittygram! 🐾
