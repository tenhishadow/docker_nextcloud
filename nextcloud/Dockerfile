FROM nextcloud:stable-fpm

RUN apt-get update -q \
    && DEBIAN_FRONTEND=noninteractive apt-get install -yq --no-install-recommends \
        samba-client \
        ffmpeg \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
