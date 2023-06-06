FROM grafana/grafana:latest

# Create Directory for the Container
WORKDIR /
COPY ./grafana-datasources.yaml ./etc/grafana/provisioning/datasources/datasources.yaml

ENV GF_AUTH_ANONYMOUS_ENABLED=true
ENV GF_AUTH_ANONYMOUS_ORG_ROLE=Admin
ENV GF_AUTH_DISABLE_LOGIN_FORM=true
ENV GF_FEATURE_TOGGLES_ENABLE=traceqlEditor