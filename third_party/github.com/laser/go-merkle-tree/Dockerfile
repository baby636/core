FROM golang:1-stretch

COPY . /opt/app
WORKDIR /opt/app

ENTRYPOINT ["/bin/bash", "-c"]

CMD ["go test"]
