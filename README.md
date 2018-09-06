## Description
Openshift Docker image to run cerebro [Elasticsearch 6.x](https://www.elastic.co/products/elasticsearch) web admin tool that replaces [Kopf](https://github.com/lmenezes/elasticsearch-kopf).

Cerebro project: https://github.com/lmenezes/cerebro

This Docker image is built and available in Docker hub [phlbrz/openshift-cerebro:latest](https://hub.docker.com/r/phlbrz/openshift-cerebro/)

### Docker Tags

`phlbrz/openshift-cerebro` tagged images:

* `latest` (default): `0.8.1` - Latest version of Cerebro.

## Usage
`oc create -f https://raw.githubusercontent.com/phlbrz/openshift-cerebro/master/cerebro-template.yaml -n project`

Go to Openshift Console and create the template.

Then you can access the web console in this URL: http(s)://cerebro.domain

