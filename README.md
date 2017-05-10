Openshift Metrics - Scrape and Visualise
----------------------------------------

Metrics scraper and visualisation tool based on prometheus and grafana for aggregating and visualising metrics from objects in OpenShift cluster

For running grafana pod, it requires some level of escalated privileges than 'default' serviceaccount. Template includes a customized serviceaccount and scc for running grafana. Credentials to login to grafana is **admin/monitor**

Grafana template is inherited from [grafana-dashboard](https://github.com/instrumentisto/grafana-dashboard-kubernetes-prometheus)
