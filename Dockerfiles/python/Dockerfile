FROM python:3.13-slim
WORKDIR /app
COPY . /app

ENV PYTHONUNBUFFERED=1

RUN pip3 install --no-cache-dir -r requirements.txt
CMD ["python3", "-u", "main.py"]