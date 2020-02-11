ARG VERSION=16.04

FROM ubuntu:${VERSION}

RUN apt-get update && apt-get install -y curl && apt-get clean && rm -rf /var/lib/apt/lists/*

RUN mkdir /home/codes

ENV USER ahmed

ENV SHELL /bin/bash

ENV LOGNAME Ahmed-Awad

CMD ["bash"] 