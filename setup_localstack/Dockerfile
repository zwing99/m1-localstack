FROM mesosphere/aws-cli

COPY setup-localstack /
COPY *.json /

RUN apk -v --update --no-cache add jq bash curl

ENTRYPOINT []