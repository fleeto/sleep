FROM alpine
RUN apk add  dnstracer curl wrk vim tcptraceroute --update && \
    curl -s https://pkg.cfssl.org/R1.2/cfssl_linux-amd64 -o /usr/local/bin/cfssl && \
    chmod a+x /usr/local/bin/cfssl

CMD ["sleep", "1d"]
