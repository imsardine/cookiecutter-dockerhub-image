FROM buildpack-deps:bionic-curl

WORKDIR /workspace

RUN apt-get update && apt-get install -y --no-install-recommends \
    curl \
    make \
 && rm -rf /var/lib/apt/lists/*
