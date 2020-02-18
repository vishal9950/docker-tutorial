FROM golang

WORKDIR /app

COPY hello.go .

RUN go build hello.go

EXPOSE 8000

CMD ["./hello"]