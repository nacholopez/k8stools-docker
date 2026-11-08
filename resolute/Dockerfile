FROM ubuntu:resolute@sha256:6a06111c3b0a8600feadb270aec771dc239bf407b25625f93f44ab00e11f4d3c

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
