FROM ghcr.io/home-assistant/base:latest

# Install ddclient
RUN apk add ddclient && apk add jq

COPY ddclient.conf /etc/ddclient/ddclient.conf

# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
