FROM ubuntu:noble@sha256:73b999393d07f2bf65a40373778a44dc9a6d54ad7718d29247d8ff9413c4d6a8

RUN apt-get update && apt-get install -y --no-install-recommends \
    ca-certificates \
    curl \
    iputils-ping \
    mtr \
    nmap \
    net-tools \
    iproute2 \
    dnsutils \
    jq \
    telnet \
    ftp \
    lftp \
    bc \
    openssh-client \
    && rm -rf /var/lib/apt/lists/*
