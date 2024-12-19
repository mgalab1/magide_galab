FROM mcr.microsoft.com/devcontainers/universal:2-linux

RUN apt-get update && apt-get install -y \
    xz-utils \
    curl \
    python3-pip \
    && apt-get clean


RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash - && \
    apt-get install -y nodejs && \
    npm install -g @vue/cli


RUN pip install flask