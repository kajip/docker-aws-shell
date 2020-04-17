FROM alpine:latest

RUN apk add --update --no-cache python3 \
    && pip3 install aws-shell

VOLUME ["/root/.aws"]

ENTRYPOINT ["/usr/bin/aws-shell"]
