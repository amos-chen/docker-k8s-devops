FROM python:2.7-alpine

LABEL maintainer="KeithTt"

RUN pip install flask Flask-Script
COPY . /app/
WORKDIR /app

EXPOSE 5000

ENTRYPOINT [ "python", "manage.py" ]
CMD []
