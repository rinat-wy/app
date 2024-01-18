FROM alpine

RUN apk update

RUN apk add --no-cache mysql mysql-client && \
    rm -f /var/cache/apk/*

WORKDIR /opt

COPY . .
RUN chmod +x import.sh

CMD [ "sh", "import.sh" ]

