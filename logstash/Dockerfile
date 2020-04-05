ARG VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${VERSION}
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
RUN rm -f /usr/share/logstash/config/logstash.yml
