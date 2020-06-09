Grafana installation for multiple projects

deploy run ./runhelm.sh this will populate all variables. 

grafana will be deployed in namespace grafana

a default dashboards will be created. 

in order to create new dashboards deploy via the grafanadashboards context. 

see https://github.com/integr8ly/grafana-operator/blob/master/documentation/dashboards.md

Default datasource are called Prometheus do not try to use other datasources at the moment. 

