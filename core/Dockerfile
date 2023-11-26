FROM python:3.9.18-slim-bullseye

ENV PYTHONBUFFERED=1

WORKDIR /apps/django/secure-document-database-django

COPY requirements.txt requirements.txt

RUN pip3 install -r requirements.txt

COPY . .

CMD python3 manage.py runserver 0.0.0.0:8081