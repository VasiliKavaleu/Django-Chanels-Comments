Болванка проекта

1. Склонировать проект
2. Установить виртуальное окружение (например через venv) и активировать
3. Установить зависимости - `pip install -r requirements.txt`
4. Запустить `python manage.py migrate`
5. Запустить `python manage.py loaddata data.json --app=posts`, чтобы предзаполнить БД
6. Запустить `python manage.py loaddata data.json --app=comments`, чтобы предзаполнить БД
