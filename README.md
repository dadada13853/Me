## Setup your development environment

```
virtualenv --python=python3 ./env
./env/bin/pip install -r requirements.txt
./env/bin/python manage.py migrate
./env/bin/python manage.py createsuperuser
./env/bin/python manage.py runserver
```

### Verify Django CMS configuration
`./env/bin/python manage.py cms check`

