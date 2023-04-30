FROM python:3.11-slim

WORKDIR /tmp/work

COPY requirements.txt ${PWD}

RUN python -m pip install --upgrade pip && \
    pip install -r requirements.txt
