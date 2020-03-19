FROM golang:latest

LABEL maintaner="Felipe Macedo <felipe.x.macedo@gmail.com>"

WORKDIR /app

# Copy the source from the current directory to the Working Directory inside the container
COPY . .

# build file with go tool
RUN go build olaMundo.go

# Run the executable
CMD ["./olaMundo"]

