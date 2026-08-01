FROM python:3.14.2-slim

WORKDIR /app

COPY consumer.py .

RUN pip install confluent_kafka sqlalchemy pandas psycopg2-binary

CMD ["python", "consumer.py"]
