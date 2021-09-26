ARG BUILD_ARCH
FROM blakeblackshear/frigate:0.8.4-${BUILD_ARCH}

RUN mkdir -p /tmp/ramcache
RUN sudo mount -t tmpfs -o size=2G ramcache /tmp/ramcache
