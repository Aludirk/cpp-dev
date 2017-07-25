FROM gcc:7

RUN set -ex; \
    apt-get update; \
    apt-get install -y --no-install-recommends \
            gdb \
            cppcheck \
            libcppunit-dev \
			valgrind; \
    rm -rf /var/lib/apt/lists/*
