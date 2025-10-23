Conectar a la red InfluxDB/Grafana desde otro contenedor
```
docker network connect my_monitoring_network [CONTAINER_NAME]
```
Acceso a InfluxDB desde el otro contenedor:
```
INFLUX_URL = http://influxdb:8086
```
