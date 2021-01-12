# Django POC

## Initialization

* Installation of Django: `python -m pip install Django`
    * Verify: 
    
    ```Python
    import django
    print(django.get_version())
    ```

Base structure created using `django-admin startproject pocdjango` 

## Run

* Run database migrations: `python manage.py migrate`
* Start development server: `python manage.py runserver`
    * Will automatically reload Python code on changes

## Suplementaty Tools

* *SQLiteStudio* to browse SQLite database: `choco install sqlitestudio`

## Development

* Create migration files based on current model (e.g. for polls app): `python manage.py makemigrations polls`
* Display migration skripts: `python manage.py sqlmigrate polls 0001`
* Invoke Django Python shell: `python manage.py shell`

### Django Admin

* Access admin page at <http://127.0.0.1:8000/admin/>
* Manually created admin user: **admin/pw**
