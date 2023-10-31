
### Сборка и запуск:

git clone git@github.com:gladunvv/django-nested-menu.git
cd django-nested-menu
pip install virtualenv
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cd nested_menu/
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
