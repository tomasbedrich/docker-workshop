FROM python:latest

RUN pip install Flask

WORKDIR /app

ENV FLASK_APP=hello.py
ENV FLASK_ENV=development
ENV FLASK_RUN_HOST=0.0.0.0
ENV FLASK_RUN_PORT=5000

COPY hello.py hello.py

ENTRYPOINT ["flask", "run"]
