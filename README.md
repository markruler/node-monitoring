# Node Monitoring with Prometheus and Grafana

## Docker Compose 실행

```sh
sudo docker compose up -d

# 제거 시
# sudo docker compose down -v
```

## Grafana Dashboard

- [localhost:3000](http://localhost:3000)
- Account
  - username: `admin`
  - password: `changeme`
- Data Source
  - Prometheus: `http://prometheus:9090`
- Import Dashboard
  - Dashboard ID: `1860` ([Node Exporter Full](https://grafana.com/grafana/dashboards/1860-node-exporter-full/))
