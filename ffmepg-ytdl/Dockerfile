FROM ubuntu:latest
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    ffmpeg \
    python3 \
    python3-pip \
    curl 

WORKDIR /usr/local/bin
RUN curl -OL https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp
RUN chmod a+x yt-dlp

WORKDIR /app
