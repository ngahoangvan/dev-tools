FROM lscr.io/linuxserver/code-server:latest
USER root
RUN rm -vf /var/lib/apt/lists/*
RUN apt-get update && apt-get install -y \
    build-essential \
    ca-certificates \
    ccache \
    cmake \
    curl \
    git \
    zsh \
    python3-dev \
    python3-pip \
    && sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" \
    && rm -rf /var/lib/apt/lists/*

#USER "abc"
