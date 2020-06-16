FROM python:3.8.3

WORKDIR /opt

COPY requirements.txt /opt
RUN python -m pip install --upgrade pip && \
    pip install -r /opt/requirements.txt

