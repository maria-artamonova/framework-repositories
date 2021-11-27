# Grafana

## Features
The analytics platform for all your metrics
>Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored. Create, explore, and share dashboards with your team and foster a data driven culture.

## Demo
[Live Demo](http://play.grafana.org/)

## Dashboards
[Dashboards](https://grafana.com/grafana/dashboards/)

## Prometheus
[Prometheus Stats](https://grafana.com/grafana/dashboards/2)
- Name: `Prometheus`
- HTTP
    + URL: `http://localhost:9090`

## MySQL
[2MySQL Simple Dashboard](https://grafana.com/grafana/dashboards/7991)
- Name: `MySQL`
- MySQL Connection
    + Host: `localhost:3306`
    + Database
    + User, Password

## InfluxDB
[Telegraf: system dashboard](https://grafana.com/grafana/dashboards/928)
- Name: `InfluxDB`
- Query Language: `Flux`
- HTTP
    + URL: `http://localhost:8086`
- InfluxDB Details
    + Organization
    + Token: http://localhost:8086 -> Load Data -> Tokens
    + Default Bucket

## Redis
[Redis](https://grafana.com/grafana/dashboards/12776) [Configuration](https://redisgrafana.github.io/redis-datasource/configuration/)
- Name: `Redis`
- Redis
    + Type: `Standalone`
    + Address: `redis://localhost:6379`
    + Password

## Cassandra
[Cassandra](https://grafana.com/grafana/dashboards/5408)
- Name: `Apache Cassandra`
- Cassandra Connection
    + Host: `localhost:9042`
    + User, Password

## Loki
[Usage Insights (Cloud)](https://grafana.com/grafana/dashboards/15083)
- Name: `Loki`
- HTTP
    + URL: `http://localhost:3100`

## Runtime Environment
- [Grafana 6.2.5](https://grafana.com/grafana/download)
- [Grafana Documentation](https://grafana.com/docs/)
- [Grafana](https://github.com/grafana/grafana)