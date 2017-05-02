FROM golang:$GO_VERSION
ARG GO_VERSION=1.8
ADD . /src
WORKDIR /src
RUN go build -o hello
CMD ["./hello"]
