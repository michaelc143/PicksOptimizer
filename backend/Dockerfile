FROM python:3.9

WORKDIR /app/backend

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD ["python", "backend.py"]