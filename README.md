# python-test-1

docker run --name postgresContainer1 -e POSTGRES_PASSWORD= -e POSTGRES_USER= -p 5433:5432 -v postgres-volume-django-learning:/var/lib/postgresql/data -d postgres
