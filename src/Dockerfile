FROM python:3

ENV PYTHONUNBUFFERED 1

WORKDIR /app

COPY ./src .

RUN pip install -r requirements.txt

EXPOSE 6543

CMD ["python","app.py"]

