FROM python:3.7.2-slim

COPY . /main
WORKDIR /app

RUN pip install --upgrade pip
RUN pip install -r requirements.txt


ENTRYPOINT ["python", "main.py"]

