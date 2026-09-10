FROM golang:1.25

RUN apt-get update && apt-get install -y \
    git \
    curl \
    vim

WORKDIR /workspace

RUN go install github.com/githubnemo/CompileDaemon@latest