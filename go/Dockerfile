FROM golang:1.8
WORKDIR /go/src/app
COPY . .
RUN go build server.go
CMD ["./server"]
