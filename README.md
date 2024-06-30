- https://umanking.github.io/2021/08/19/prometheus-grafana-example/

```sh
docker run -p 9090:9090 -v ./prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
docker run -d -p 3000:3000 grafana/grafana
```
