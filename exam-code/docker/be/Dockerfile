# Dockerfile for Backend Service
FROM python:3.12-slim

WORKDIR /db
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt


COPY src/ ./src/
CMD ["python", "src/main.py"]


EXPOSE 5001