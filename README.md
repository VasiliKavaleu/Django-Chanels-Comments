## Example of using Django Channels for creating comments


Clone project 

Create virtual environment
```bash
python3 -m venv env
```

Activate virtual environment
```bash
source env/bin/activate
```

Install dependencies
```bash
pip install -r requirements.txt
```

Make migrations/migrate
```bash
python manage.py makemigrations
python manage.py migrate
```

Load data into db
```bash
python manage.py loaddata data.json --app=posts
python manage.py loaddata data.json --app=comments
```

Run Redis in container
```bash
docker-compose -f docker-compose.redis.yml up
```

Run server and leave comment under post (login is required)
```bash
python3 manage.py runserver
```
