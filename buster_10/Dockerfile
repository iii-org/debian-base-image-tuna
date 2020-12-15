FROM debian:buster
LABEL org="iii-org"

RUN apt-get update && apt install -yq --no-install-recommends apt-transport-https ca-certificates
COPY ./MIRROR_APT套件源 /etc/apt/sources.list
