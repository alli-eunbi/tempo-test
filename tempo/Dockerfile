FROM grafana/tempo:latest

# Create Directory for the Container
WORKDIR /
# COPY ./tempo.yaml ./etc/tempo.yaml

CMD [ "-config.file=/etc/tempo.yaml" ]

EXPOSE 14268
EXPOSE 3200
EXPOSE 9095
EXPOSE 4317
EXPOSE 4318
EXPOSE 9411