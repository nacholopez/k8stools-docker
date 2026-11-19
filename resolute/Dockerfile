FROM ubuntu:resolute@sha256:d66b366dac61b575bee2aef07e9c26e8070096fbe84a3d4d3eb0da069b5d76db

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
