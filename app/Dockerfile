FROM python:3.13.2-alpine3.21

WORKDIR /app

COPY . /app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

ENV FLASK_ENV=Development

CMD ["python" , "app.py"]


# docker pull shaddass/flask-app:latest