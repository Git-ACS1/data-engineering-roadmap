FROM python:3.14.3-slim

WORKDIR /app

COPY consumer.py .

RUN pip install confluent_kafka sqlalchemy pandas psycopg2-binary

CMD ["python", "consumer.py"]
