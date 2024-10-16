# docker-do-zero
Full Cycle - Colocando múltiplas aplicações no ar

```bash
docker build -t my-app-python .
```

```bash
docker run my-app-python
```

```bash
docker exec -it <CONTAINER ID> bash
```

```bash
pip install pipenv
```

```bash
export PIPENV_VENV_IN_PROJECT=1
```

```bash
mkdir meu-projeto
```

```bash
cd meu-projeto
```

```bash
pipenv shell
```

```bash
pipenv install django
```

```bash
django-admin startproject videos
```

```bash
docker run -v $(pwd):/app my-app-python
```

```bash
cat /etc/passwd
```

```bash
python manage.py runserver
```

```bash
docker run -v $(pwd):/app -p 8000:8000 my-app-python
```

```bash
python manage.py runserver 0.0.0.0:8000
```

```bash
docker run -e POSTGRES_PASSWORD=root -e POSTGRES_DB=django postgres:15.8-alpine3.20
```

```bash
docker compose up
```

```bash
pipenv install psycopg2-binary
```

```bash
python manage.py migrate
```

_admin@user.com_
```bash
python manage.py createsuperuser
```

**Administration**
_/admin_

```bash
docker compose down
```