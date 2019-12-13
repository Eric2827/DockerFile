FROM python:alpine

COPY . /app
WORKDIR /app

RUN pip install Flask

ENTRYPOINT ["python"]
CMD ["app.py"]
