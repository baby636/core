FROM golang:rc-stretch

COPY . /opt/app
WORKDIR /opt/app

ENTRYPOINT ["/bin/bash", "-c"]

CMD ["go test"]
