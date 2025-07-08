# Multi-tenancy

A test project to see how to build proper multi tenancy setups

# Database setup
```shell
poetry run ./manage.py migrate_schemas --shared
poetry run ./manage.py migrate
```
