

## Documentation

Start the Django app by running 

``` Bash
python manage.py runserver 0.0.0.0:8000
```

If you running first time create chatterbot table before starting server

``` Bash
python manage.py migrate --run-syncdb
```

Further documentation on getting set up with Django and ChatterBot can be found in the [ChatterBot documentation](http://chatterbiot.readthedocs.io/en/latest/django.html)

## Make migrations

``` Bash
python manage.py migrate
```
## Train your bot

``` Bash
python manage.py train
```

## Bot Django Settings
You could found Bot settings [here](./example_app/settings.py)
