FROM docker.elastic.co/beats/filebeat:7.17.2
COPY --chown=filebeat:filebeat ./filebeat.yml /usr/share/filebeat/
RUN chmod go-w /usr/share/filebeat/filebeat.yml
