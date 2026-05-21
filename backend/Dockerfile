FROM golang:1.22-alpine
WORKDIR /app
COPY . .
RUN CGO_ENABLED=0 GOOS=linux go build -o main .
EXPOSE 8080
CMD ["./main"]
