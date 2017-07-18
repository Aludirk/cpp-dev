FROM gcc:5

RUN set -ex; \
    apt-get update; \
    apt-get install -y --no-install-recommends \
            gdb \
            cppcheck \
            libcppunit-dev; \
    rm -rf /var/lib/apt/lists/*
