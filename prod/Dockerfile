FROM golang:1.8.1

WORKDIR /gopath


RUN export PATH=$PATH:$(go env GOPATH)/bin
RUN go get github.com/josh-gree/prod

EXPOSE 80

CMD ["prod"]