FROM golang:alpine
RUN apk add --no-cache git

# http://moira.readthedocs.org/en/latest/quickstart.html

# Install the libraries we need
ENV GOPATH /moira
RUN go get github.com/moira-alert/cache
RUN go get github.com/moira-alert/notifier/notifier

RUN mkdir /var/log/moira/