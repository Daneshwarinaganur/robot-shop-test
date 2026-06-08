FROM golang:1.22

WORKDIR /go/src/app

COPY *.go .

RUN go mod tidy
RUN go install

CMD dispatch
