FROM docker.elastic.co/elasticsearch/elasticsearch:7.3.1

COPY vietnamese.zip /usr/share/elasticsearch

RUN yes y | /usr/share/elasticsearch/bin/elasticsearch-plugin install file:///usr/share/elasticsearch/vietnamese.zip
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install analysis-icu
