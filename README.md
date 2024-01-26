# Docker Zabbix Grafana PostgreSQL NGINX 

## Components docker-compose:

- Postgresql 14.5
- Zabbix Server 6.2
- Zabbix Frontend NGINX 6.2
- Zabbix Agent 6.2
- Grafana 9.1.4

### Easy guide

1) Clone repo:
```
git clone https://github.com/fabriciogbase/docker_zabbix_grafana.git
cd zabbix-docker
```

2) Change owner grafana directory:

```
chown -R 472:472 grafana
```

3) Run docker-compose:
```
docker-compose up -d
```

### Debug
```
docker-compose logs --tail=1 -f
```
