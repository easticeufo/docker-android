FROM ubuntu:16.04
RUN apt-get update; \
    DEBIAN_FRONTEND=noninteractive apt-get install -y git-core gnupg flex bison gperf build-essential zip curl zlib1g-dev gcc-multilib g++-multilib libc6-dev-i386 lib32ncurses5-dev x11proto-core-dev libx11-dev lib32z-dev ccache libgl1-mesa-dev libxml2-utils xsltproc unzip libc6-dev tofrodos python-markdown lib32readline6-dev software-properties-common python-software-properties openjdk-8-jdk lib32stdc++6 libxml-simple-perl openssl libssl-dev; \
    rm /bin/sh; \
    ln -s /bin/bash /bin/sh; 
