FROM golang:1.13.8-buster
ENV GO111MODULE=on
RUn go env -w GOPROXY=https://mirrors.aliyun.com/goproxy/ \
    && go env -w GOSUMDB=off
VOLUME /go
ENTRYPOINT [ "go" ]
