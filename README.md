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