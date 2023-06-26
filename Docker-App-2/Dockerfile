FROM alpine:latest

ENTRYPOINT ["/bin/echo", "Hi, your ENTRYPOINT instruction in Exec Form !"]

WORKDIR /app

RUN apk update
RUN apk add git

COPY . /app

ADD http://www.vlsitechnology.org/pharosc_8.4.tar.gz .

CMD ["top"]