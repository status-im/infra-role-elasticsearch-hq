# Description

This role configures an [ElasticHQ](https://github.com/ElasticHQ/elasticsearch-HQ) which is a Web UI for [ElasticSearch](https://www.elastic.co/guide/en/elasticsearch/reference/6.3/index.html).
It enables an easier overview of the health of the cluster.

# Configuration

The only mandatory setting necessary to set is:
```yaml
es_domain: 'es.example.com'
es_hq_cookie_secret: 'change-me-please'
es_hq_oauth_client_id: 'some-kind-of-id'
es_hq_oauth_client_secret: 'totally-secret-secret'
```

# Usage

The UI can be accessed via GitHub OAuth at:
https://es.status.im/

For more details read:
http://docs.elastichq.org/installation.html
