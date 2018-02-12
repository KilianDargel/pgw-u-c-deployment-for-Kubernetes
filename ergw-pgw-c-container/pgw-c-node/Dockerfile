# Dockerfile can be found at https://github.com/travelping/ergw-docker-base
FROM ergw/ergw-docker-base

WORKDIR /
COPY _build/prod/rel/ /opt/

CMD ["/opt/ergw-gtp-u-node/bin/ergw-gtp-c-node", "foreground"]
