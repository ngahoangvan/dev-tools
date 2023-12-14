FROM ghcr.io/mlflow/mlflow:v2.9.1
RUN apt-get update && \
    apt-get install -y \
    libpq-dev \
    python-dev \
    gcc \
    curl

COPY requirements.txt .
RUN pip install psycopg2 boto3
