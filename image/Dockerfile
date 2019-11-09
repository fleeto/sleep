FROM alpine
RUN apk add  dnstracer curl wrk vim tcptraceroute iptables httpie bash tini --update && \
    curl -s https://pkg.cfssl.org/R1.2/cfssl_linux-amd64 -o /usr/local/bin/cfssl && \
    curl -L -s https://github.com/BuoyantIO/slow_cooker/releases/download/1.1.0/slow_cooker_linux_amd64 -o /usr/local/bin/slow_cooker && \
    chmod a+x /usr/local/bin/* 

CMD ["tini", "sleep", "1d"]
