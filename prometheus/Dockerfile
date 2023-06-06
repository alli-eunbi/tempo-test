FROM  prom/prometheus:latest
WORKDIR /
# COPY  /prometheus.yaml /etc/prometheus.yaml

CMD [ "--config.file=/etc/prometheus.yaml", "--web.enable-remote-write-receiver",  "--enable-feature=exemplar-storage"]
EXPOSE 9090