FROM python:3.6.0-alpine

WORKDIR /app
COPY . /app

#RUN apk --no-cache --update add build-base=0.4-r1 && \
#    pip3 install --upgrade pip && \
#    pip3 install -r /app/requirements.txt && \
#    apk del build-base

RUN apk --no-cache --update add gcc musl-dev \
    build-base && \
    pip3 install --upgrade pip && \
    pip3 install -r /app/requirements.txt && \
    apk del build-base

ENV POST_DATABASE_HOST post_db
ENV POST_DATABASE posts

ENTRYPOINT ["python3", "post_app.py"]
