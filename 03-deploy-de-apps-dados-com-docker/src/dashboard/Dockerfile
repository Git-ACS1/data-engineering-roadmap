# dashboard/Dockerfile
FROM python:3.14.2-slim
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
CMD ["streamlit", "run", "app.py"]