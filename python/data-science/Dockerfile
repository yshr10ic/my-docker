FROM python:3.8.3

WORKDIR /opt

COPY requirements.txt /opt
RUN python -m pip install --upgrade pip && \
    pip install -r /opt/requirements.txt

WORKDIR /

CMD ["jupyter", "lab", "--ip=0.0.0.0", "--allow-root", "--LabApp.token=''"]

