FROM golang:1.19

RUN apt-get -y update
RUN apt-get -y install less gzip zip unzip
RUN apt-get -y install silversearcher-ag

# install extra golang utiities recommended by the go extension
RUN go install -v github.com/rogpeppe/godef@latest
RUN go install -v golang.org/x/tools/cmd/goimports@latest
RUN go install -v github.com/ramya-rao-a/go-outline@latest
RUN go install -v golang.org/x/tools/gopls@latest