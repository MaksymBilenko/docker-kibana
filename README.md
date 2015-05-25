docker-kibana
===============
Docker [automated build](https://registry.hub.docker.com/u/sath89/kibana/) with Kibana 4.0.2 based on [ubuntu:latest](https://registry.hub.docker.com/u/library/ubuntu/)

**Usage with link to elasticsearch:**

     docker run -it --rm --link elasticsearch:elasticsearch sath89/kibana:latest

**Usage with URL to elasticsearch:**

     docker run -it --rm -e ELASTICSEARCH_URL=http://elasticsearch_ip:9200 sath89/kibana:latest

* Docker-Compose examples here in [logstash](https://github.com/MaksymBilenko/docker-logstash)