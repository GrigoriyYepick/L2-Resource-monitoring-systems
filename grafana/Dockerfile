FROM grafana/grafana:latest

USER root

RUN mkdir -p /srv/docker/grafana/data
RUN chown 472:472 /srv/docker/grafana/data  

USER grafana

EXPOSE 3000


