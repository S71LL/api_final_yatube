# API для сайта с постами

### API позволяет получать из базы данных записи о постах, группах, подписках и комментариях, сделанных пользователями

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:S71LL/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```
```
source env/scripts/activate
```

Установить и обновить менеджер пакетов:

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Перейти в дерикторию с файлом manage.py

```
cd yatube_api
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

Проект доступен локально
## http://127.0.0.1:8000/api/v1/

Документация проекта
## http://127.0.0.1:8000/redoc/