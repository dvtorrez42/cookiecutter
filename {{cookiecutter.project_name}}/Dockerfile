FROM python:3.7-slim

COPY src/ /app
WORKDIR /app

RUN apt-get update \
    && apt-get install -y git \
    && rm -rf /var/lib/apt/lists/*

COPY requirements.txt /tmp/req.txt
RUN pip install -r /tmp/req.txt \
        --disable-pip-version-check \
        --no-cache-dir \
    && rm /tmp/req.txt

CMD [ "python", "/app" ]