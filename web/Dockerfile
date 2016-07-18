FROM golang:1.6.2-alpine

ADD . /go/src/hello
RUN go install hello
ENTRYPOINT /go/bin/hello

EXPOSE 8080
