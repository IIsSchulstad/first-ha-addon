ARG BUILD_FROM=ghcr.io/hassio-addons/base/amd64:10.2.2
FROM ${BUILD_FROM}

COPY run.sh /
RUN chmod a+x /run.sh

CMD ["/run.sh"]