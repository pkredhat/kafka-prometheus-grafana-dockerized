# A quick container environment for Kafka / Prometheus / Grafana

A very simple "quick-start" [kafka + prometheus + grafana] to run in a docker container

## Prerequisites
> Docker

## Usage

### Clone to a local folder
```
git clone https://github.com/pkredhat/kafka-prometheus-grafana-dockerized
```

### Run Docker Compose
```
docker-compose up -d 
```
> Edit docker-compose.yml to change any default settings

## Test Prometheus
- ```curl http://localhost:9090/api/v1/status/buildinfo```
- In a browser navigate to : http://localhost:9000

## Test Grafana
- In a browser navigate to : http://localhost:3000