FROM ubuntu:resolute

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
