# OpenTHC Logging Server

* Accepts logs via Redis Pub/Sub and Syslog.
* Archives Logs
* Display Logs in real-time
* Display Metrics in real-time


## Install

Clone this repo into some place special.

Then install the `edoceo/gwsrps` tool.
Run it, using `./bin/gwsrps.sh` as an example wrapper.


### Redis via stunnel

Check out `./etc/stunnel-redis.conf`.
Typically, we make stunnel listen on the same port as local Redis.
