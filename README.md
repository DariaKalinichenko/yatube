
# Yatube
Социальная  сеть для блогеров (выполнен во время обучения в Яндекс.Практикум)
# Стек
Python 3, Django 2.2 LTS, PostgreSQL, gunicorn, nginx, Яндекс.Облако(Ubuntu 18.04), pytest
# Описание
- Можно создать свою страницу.
- После регистрации пользователь получает свой профайл, то есть получает свою страницу.
- Если на нее зайти, то можно посмотреть все записи автора.
- Пользователи могут  заходить на чужие страницы, подписываться на авторов и комментировать их записи.
- Автор может выбрать для своей страницы имя и уникальный адрес.
- Есть возможность модерировать записи и блокировать пользователей, если начнут присылать спам.(реализовано через админ-панель)
- Записи можно отправить в сообщество и посмотреть там записи разных авторов.

# Инструкция по развертыванию проекта
1. Скачать проект или клонировать с помощью git (`git clone https://github.com/DariaKalinichenko/yatube.git`)
2. Перейти в каталог с проектом и создать виртуальное окружение (`python3 -m venv venv`)
3. Запустить виртуальное окружение (`source venv/bin/activate`) на Mac/Linux или (`source venv/Scripts/activate`) на Windows
4. Установить все необходимые пакеты, указанные в файле requirements.txt (`pip install -r requirements.txt`)
5. Запустить миграции (`python manage.py migrate`)
6. Для проверки работы проекта запустить тестовый сервер (`python manage.py runserver`)
7. Перейти по адресу http://127.0.0.1:8000
