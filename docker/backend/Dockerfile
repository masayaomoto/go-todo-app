FROM golang:alpine
RUN apk update
RUN apk add alpine-sdk
COPY ./backend /app/backend
WORKDIR /app/backend
RUN go build -o server .
