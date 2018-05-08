FROM golang:latest

WORKDIR /go/src/

ADD echo-server/ echo-server/

RUN go install echo-server/

EXPOSE 18888

CMD ["go", "run", "echo-server/main.go"]
