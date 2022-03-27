FROM ubuntu:latest

RUN apt-get update \
    && apt-get install -y curl

COPY my-script.sh .

RUN chmod +x ./my-script.sh

CMD ./my-script.sh
