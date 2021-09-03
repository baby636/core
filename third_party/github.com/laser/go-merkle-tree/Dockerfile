FROM golang:1.16.7-stretch

COPY . /opt/app
WORKDIR /opt/app

ENTRYPOINT ["/bin/bash", "-c"]

CMD ["go test"]
