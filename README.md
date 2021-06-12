# OpenTHC Logging Server

* Accepts logs via Redis Pub/Sub and Syslog.
* Archives Logs
* Display Logs in real-time
* Display Metrics in real-time


## Dependencies

* Grafana
* Prometheus
* Nagios
* Zabbix


## Install

Clone this repo into some place special.

Then install the `edoceo/gwsrps` tool.
Run it, using `./bin/gwsrps.sh` as an example wrapper.


### Grafana

Protected via *Basic* auth using a reverse-proxy.
Could also use [this oAuth](https://github.com/nbayramberdiyev/grafana-generic-oauth) client might work.


### Prometheus

Protected via *Basic* auth, using a reverse-proxy.


### Nagios

Optional


### Zabbix

Optional
