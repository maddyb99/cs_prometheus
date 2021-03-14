#Locally:
```
./prometheus --config.file=prometheus.yml
```

#Docker:
```
sudo docker run     -p 9090:9090     -v /home/kc/Desktop/credit_suisse/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml     prom/prometheus
```
