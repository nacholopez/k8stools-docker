FROM ubuntu:noble@sha256:fe81560990fae86dc4743202b2cb4d3df98d0bcf949173cecef15ce1127ef852

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
