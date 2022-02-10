# DEPRECATION WARNING

This repository has been deprecated because of [known compatibility issues](https://github.com/status-im/infra-role-elasticsearch/issues/2).

# Description

This role configures an [ElasticHQ](https://github.com/ElasticHQ/elasticsearch-HQ) which is a Web UI for [ElasticSearch](https://www.elastic.co/guide/en/elasticsearch/reference/6.3/index.html).
It enables an easier overview of the health of the cluster.

This role goes in tandem with [infra-role-elasticsearch](https://github.com/status-im/infra-role-elasticsearch).

# Configuration

The only settings necessary to set are:
```yaml
# ES Cluster info
es_hq_lb_host: localhost
es_hq_lb_cont_name: es-lb-container
```

__WARNING:__ This role assumes the ES container runs on the same host and can be linked to.

# Usage

For more details read:
http://docs.elastichq.org/installation.html
