FROM golang:alpine
MAINTAINER birucloud-golang-demo
#RUN apk add --update curl bash && \
#    rm -rf /var/cache/apk/*
WORKDIR $GOPATH/src/app/
COPY ./outyet $GOPATH/src/app/
EXPOSE 8081
ENTRYPOINT ["./outyet"]
