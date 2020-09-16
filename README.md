# rpi_cluster
---
I'm creating a raspberry server that run a lot of services deployed in Docker Swarm.

I will create all Dockerfile from Debian.

All this services have to be accessible by name_svc.hostrpi.com by proxy reversing.

Services planned :
- FTPS
- many wordpress / mariadb
- Python code executors
- influxdb
- Telegraf that measure system metrics of the raspberry.
- Grafana that will display metrics in influxDB
- Nodejs code executors

Services be fun to deploy for tests :
- Pfsense
- Webmail hosting
- Minecraft Serveur
- Teamspeak server
