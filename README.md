# Elasticstack
Filebeat agents shipping logs to a Logstash instance.
Logs are being forwarded to Elasticsearch by Logstash.
Using Kibana to visualise the logs present in Elasticsearch database.

All services run as docker containers, check docker-compose.yml for referance.

Documentaton:
Filebeat: https://www.elastic.co/guide/en/beats/filebeat/7.17/index.html
Logstash: https://www.elastic.co/guide/en/logstash/7.17/index.htmll
Elasticsearch: https://www.elastic.co/guide/en/elasticsearch/reference/7.17/index.html
Set initial passwords for built-in users: https://www.elastic.co/guide/en/elasticsearch/reference/current/built-in-users.html#set-built-in-user-passwords
Configure basic TLS/SSL: https://www.elastic.co/guide/en/elasticsearch/reference/current/security-basic-setup.html
Kibana: https://www.elastic.co/guide/en/kibana/7.17/index.html
