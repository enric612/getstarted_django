# getstarted_django

# Description
This project is an implementation of Django's official tutorial with MongoDB support, using Djongo as driver.

# Dependencies

This project depends on Python 3.6, MongoDB 3.6 and  Django and Djongo python projects. For install it with pip type:

```
python -m venv venv

venv\\bin\\activate (linux)

venv\\Scripts\\activate (windows)

pip install -r requirementes.txt
```

# Migrations

```
python manage.py migrate

```

# Test Django version

You can type in a python console:

```Python
import django

print(django.get_version())

```


# Author

Enric Climent

# References

Django Tutorial: https://docs.djangoproject.com/en/2.0/intro/tutorial01/

Djongo get started documentation: https://nesdis.github.io/djongo/get-started/

MongoDB : https://www.mongodb.com/
