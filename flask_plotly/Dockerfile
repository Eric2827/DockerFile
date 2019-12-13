FROM ubuntu:18.04

COPY . /app
WORKDIR /app

RUN apt-get update && \
    apt-get install -y python3 \
                        python3-pip \
    && apt-get clean \
    && apt-get autoclean \
    && rm -rf /var/lib/apt/lists/*

RUN pip3 install -r requirements.txt

ENTRYPOINT ["python3"]
CMD ["app.py"]

