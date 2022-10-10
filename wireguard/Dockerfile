# https://www.balena.io/blog/how-to-run-wireguard-vpn-in-balenaos/
FROM balenalib/amd64-debian as builder
WORKDIR /usr/src/app

# Not sure if we need wget yet
# https://docs.docker.com/develop/develop-images/dockerfile_best-practices/
# 

# https://www.balena.io/docs/reference/base-images/base-images/
# install_packages does apt-install and cleanup and more.
# apt-get update && \
# apt-get install -y \
# apt-get install --no-install-recommends -y \
# 
# && apt-get clean \
# && rm -rf /var/lib/apt/lists/*

RUN install_packages \
    awscli \
    bc \
    bison \
    build-essential \
    curl \
    flex \
    git \
    libelf-dev \
    libssl-dev \
    wget \
# Start wireguard dependencies
    python \
    pkg-config \
    kmod
# ENV INTERFACE eth0
# ENV DNSMASQ_LISTENING single
# ENV PIHOLE_DNS_ 1.1.1.1;1.0.0.1
# ENV FONTFACE Terminus
# ENV FONTSIZE 8x14
# ENV WEBPASSWORD balena
# ENV VIRTUAL_HOST balena-devices.com
