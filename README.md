Болванка проекта

1. Склонировать проект - **git clone** (либо **ssh** ссылка, либо **https**)
2. Перейти в директорию **djchannels-rtc**
3. Установить виртуальное окружение (например через venv)

Например: `python3 -m venv myenv`

И активировать: _Windows_ (**myenv\Scripts\activate**), _unix_ (**source myenv/bin/activate**)

4. Установить зависимости - `pip install -r requirements.txt`
5. Запустить `python manage.py migrate`
6. Запустить `python manage.py loaddata data.json --app=posts`, чтобы предзаполнить БД
7. Запустить `python manage.py loaddata data.json --app=comments`, чтобы предзаполнить БД
