FROM golang:1.20-alpine
WORKDIR /app
COPY . .
RUN go build -o main .
CMD ["./main"]
EXPOSE 8000  # change this based on your app

