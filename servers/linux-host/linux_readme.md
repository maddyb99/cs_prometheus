Node Exporter Setup for Linux:

node_exporter is an official package that should be installed on Linux servers to be monitored.

******Download node exporter**********
Check out the release page( https://prometheus.io/download/ ) to get the latest version

Configure Node Exporter as a service inside systemd

***********************************************************************************************************
Start Node Exporter
metrics can be accessed on http://your_ip:9100/metrics.

Bind this metrics url as target in prometheus.yml
_______________________________________________________________________________

*** Integrating Prometheus to Grafana ***
Go to grafana 
Add data source and select Prometheus and set the URL as Prometheus server’s IP with port 9090.

------------------------------------------------------------------------------------------------------------------------------------
*** Creating dashboard for Linux server ***

Go to grafana.

Click on import and put the dashboard id 1860 and select the Prometheus data source and click on Load.

Add the notification channel for routing the alerts.


