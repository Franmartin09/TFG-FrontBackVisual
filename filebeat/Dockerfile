# filebeat/Dockerfile
FROM docker.elastic.co/beats/filebeat:7.10.1

COPY filebeat.yml /usr/share/filebeat/filebeat.yml

USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
