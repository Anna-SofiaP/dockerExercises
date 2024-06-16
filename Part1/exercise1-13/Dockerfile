FROM golang:1.16

EXPOSE 8080

WORKDIR /usr/src/app

# Copy the source code
COPY /material-applications/example-backend .

ENV REQUEST_ORIGIN=http://localhost:5000 PORT=8080

# Build the project
RUN go build

# Run tests
#RUN go test ./...

CMD ./server
