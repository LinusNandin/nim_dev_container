FROM nimlang/nim:latest

RUN apt-get update && apt-get install -y \
    git \
    && rm -rf /var/lib/apt/lists/*

RUN nimble install nimble -y

WORKDIR /workspace