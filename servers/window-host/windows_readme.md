Windows Exporter Setup :
******Link for downloading windows exporter**********
https://github.com/martinlindhe/wmi_exporter/releases

On the releases page, download the MSI file corresponding to your CPU architecture.
This .MSI file which would create windows exporter service. 

***********************************************************************************************************
Run that windows exporter service to export metrics on default port 9182.
metrics can be accessed on http://your_ip:9182/metrics.

Bind this metrics url as target in prometheus.yml
________________________________________________________________________________________________

Creating dashboard for windows server :

Go to grafana.

Click on import and paste the contents of windows-node_dashboard.json.

This JSON File contains the necessary configurations for metrics monitoring and alerting.

Add the notification channel for routing the alerts.


