FROM python:3.11

WORKDIR /app

COPY requirements.txt /app
RUN pip install -r requirements.txt

COPY deploy.py /app
COPY dog_cat_handler.py /app

ENV PYTHONUNBUFFERED=1
