<p align="center">
<img height="256" src="logo.svg" alt="oteldb svg logo">
</p>

The next generation, [OpenTelemetry-first][otel] aggregation system for metrics, traces and logs.

Compatible with [PromQL][promql], [TraceQL][traceql] and [LogQL][logql].

Based on [ClickHouse][clickhouse], fastest open-source (Apache 2.0) column-oriented database.

[clickhouse]: https://clickhouse.com/
[otel]: https://opentelemetry.io/

> [!WARNING]
> Work in progress. Not ready for production use.

Supported query languages:
- [PromQL][promql] ([Prometheus][prometheus]) for metrics
- [TraceQL][traceql] ([Grafana Tempo][tempo]) for traces
- [LogQL][logql] ([Grafana Loki][loki]) for logs

[traceql]: https://grafana.com/docs/tempo/latest/traceql/
[logql]: https://grafana.com/docs/loki/latest/query/
[promql]: https://prometheus.io/docs/prometheus/latest/querying/basics/

[prometheus]: https://prometheus.io/
[loki]: https://grafana.com/oss/loki/
[tempo]: https://grafana.com/oss/tempo/
