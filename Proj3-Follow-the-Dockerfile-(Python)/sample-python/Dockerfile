FROM python:3.11-slim
WORKDIR /app
COPY server.py ./server.py
COPY requirements.txt ./requirements.txt
RUN pip install -r requirements.txt
CMD ["python", "server.py"]

