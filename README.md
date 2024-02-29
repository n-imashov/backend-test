# Django News API

## Обзор

Цель - простое REST API с использованием Django и Django REST framework для сервиса, позволяющего пользователям добавлять посты с фотографиями и описаниями, а также лайкать и комментировать посты других пользователей.

# Запуск проекта Django:

1. Создайте виртуальное окружение (необязательно, но рекомендуется):

    ```bash
    python -m venv venv
    ```

2. Активируйте виртуальное окружение:

    ```bash
    venv\Scripts\activate
    ```

3. Установите зависимости:

    ```bash
    pip install -r requirements.txt
    ```

4. Запустите миграции:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Создайте суперпользователя:

    ```bash
    python manage.py createsuperuser
    ```

6. Запустите сервер разработки Django:

    ```bash
    python manage.py runserver
    ```

## Документация Swagger

  - [Конечные точки API](http://127.0.0.1:8000/api/swagger/)
  - [Список постов](http://127.0.0.1:8000/api/posts/)
  - [Список комментов](http://127.0.0.1:8000/api/comments/)
  - [Список лайков](http://127.0.0.1:8000/api/likes/)


## Создание и запуск с помощью Docker Compose

1. Клонируйте репозиторий:

    ```bash
    git clone https://github.com/your-username/django-crm-api.git

    cd news
    ```

2. Создайте и запустите приложение с помощью Docker Compose:

    ```bash
    docker-compose up --build
    ```

    Эта команда создаст образы Docker и запустит контейнеры. Приложение должно быть доступно по адресу http://localhost:8000/.
