FROM gcc:6

RUN set -ex; \
    apt-get update; \
    apt-get install -y --no-install-recommends \
            gdb; \
    rm -rf /var/lib/apt/lists/*