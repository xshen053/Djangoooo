# Djangoooo

## Structure

```
mysite/
    manage.py
    mysite/
        __init__.py
        settings.py         // configuration like apps, path, time zone
        urls.py             // list routes URLs to views
        asgi.py
    polls/
        __init__.py
        admin.py
        apps.py
        migrations/         // Migrations are how Django stores changes to your models (and thus your database schema)
            __init__.py
            0001_initial.py
            ...
        models.py           // database schema
        tests.py
        urls.py             // map views to a URL
        views.py            // one view is one screen
```
