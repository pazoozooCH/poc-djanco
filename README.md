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

* Start development server: `python manage.py runserver`
    * Will automatically reload Python code on changes