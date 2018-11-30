# Description

This role configures an [ElasticHQ](https://github.com/ElasticHQ/elasticsearch-HQ) which is a Web UI for [ElasticSearch](https://www.elastic.co/guide/en/elasticsearch/reference/6.3/index.html).
It enables an easier overview of the health of the cluster.

This role goes in tandem with [infra-role-elasticsearch](https://github.com/status-im/infra-role-elasticsearch).

# Configuration

The only settings necessary to set are:
```yaml
# ES Cluster info
es_lb_host: localhost
es_lb_port: 9200
# OAuth for Dashboard
es_hq_domain: 'es.example.com'
es_hq_cookie_secret: 'change-me-please'
es_hq_oauth_client_id: 'some-kind-of-id'
es_hq_oauth_client_secret: 'totally-secret-secret'
```

__WARNING:__ This role assumes the ES container runs on the same host.

# Usage

For more details read:
http://docs.elastichq.org/installation.html
