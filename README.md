![Main Kittygram workflow](https://github.com/vastakhova/kittygram_final/actions/workflows/main.yml/badge.svg)

(https://github.com/vastakhova/kittygram_final/actions/workflows/main.yml)

# Описание проекта

Социальная сеть для владельцев котиков


## Инструкция по разворачиванию

- Клонируем репозиторий и переходим в него в командной строке:
    git clone git@github.com:vastakhova/kittygram_final.git
    cd kittygram_final

- Cоздаем и активируем виртуальное окружение:
    python3 -m venv env

- Если у вас Linux/macOS:
    source env/bin/activate
* Если у вас Windows:
    source env/scripts/activate

- Устанавливаем зависимости из файла requirements.txt:
    python3 -m pip install --upgrade pip
    pip install -r requirements.txt

- Запускаем проект:
python3 manage.py runserver
    
## Переменные окружения

Чтобы запустить проект, вам понадобится добавить следующие переменные окружения в файл .env

`SECRET_KEY`
`DEBUG`
`ALLOWED_HOSTS`
`POSTGRES_DB`
`POSTGRES_USER`
`POSTGRES_PASSWORD`
`DB_NAME`
`DB_HOST`
`DB_PORT`

## Автор

- [@vastakhova](https://www.github.com/vastakhova)
