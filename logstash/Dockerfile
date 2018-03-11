# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:6.2.1

RUN logstash-plugin install logstash-filter-ip2location
RUN logstash-plugin install logstash-filter-geoip
RUN logstash-plugin install x-pack

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
