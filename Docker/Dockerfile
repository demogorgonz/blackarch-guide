FROM ubuntu:18.04 as base

MAINTAINER FilipS (filips@vaskir.co)

#Disable interactive tzdata instalaltion
ARG DEBIAN_FRONTEND=noninteractive


RUN apt update && \
    apt install -y make texlive-full latex2html 

ADD . /build/

WORKDIR /build

CMD ["bash"]
