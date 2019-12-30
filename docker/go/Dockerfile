FROM golang:latest

WORKDIR /app

RUN go get -u github.com/oxequa/realize && \
    go get -u github.com/gorilla/mux

COPY .realize.yaml /app
COPY main.go /app
