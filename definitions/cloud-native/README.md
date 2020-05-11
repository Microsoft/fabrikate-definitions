# fabrikate-cloud-native

An opinionated open platform cloud native Fabrikate stack for operating Kubernetes clusters.

It includes:

### Cluster Maintainance (via [fabrikate-kured](../fabrikate-kured))

- [Kured](https://github.com/weaveworks/kured): Automatic node reboot when OS is patched.

### Metrics Monitoring (via [fabrikate-prometheus-grafana](../fabrikate-prometheus-grafana))

- [Prometheus](https://prometheus.io/) Metrics aggregation
- [Grafana](https://grafana.com/) Visualization with Kubernetes monitoring dashboards preconfigured

### Log Management (via [fabrikate-elasticsearch-fluentd-kibana](../fabrikate-elasticsearch-fluentd-kibana))

- [Fluentd](https://www.fluentd.org/): Collection and forwarding
- [Elasticsearch](https://www.elastic.co/): Aggregation and query execution
- [Kibana](https://www.elastic.co/products/kibana): Full text query UI and visualization

### Service Mesh (via [linkerd](../linkerd))

- [Linkerd](https://linkerd.io/2/overview/): Connect, secure, control, and observe services.

### Distributed Tracing (via [jaeger-operator](../jaeger-operator))

- [Jaeger](https://www.jaegertracing.io/): Distributed transaction, latency, and dependency tracing
