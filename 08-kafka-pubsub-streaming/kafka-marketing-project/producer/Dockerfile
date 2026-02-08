FROM python:3.14.3-slim

WORKDIR /app

COPY producer.py .

RUN pip install faker confluent_kafka

CMD ["python", "producer.py"]
