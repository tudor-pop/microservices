FROM alpine:latest

RUN apk --no-cache add ca-certificates

RUN mkdir /app
WORKDIR /app
COPY vessel-service .

CMD ["./shippy-service-vessel"]