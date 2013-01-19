zabbix-rabbitmq
===============

Monitoring script for rabbitmq

zabbix-rabbitmq-template.xml - Template for zabbix 
zabbix-rabbitmq.conf - Zabbix UserParameter for discovery and monitoring

rabbitmq/detect_rabbitmq_nodes.sh - discovery script

return nodes and vhost
```
rabbitmq/detect_rabbitmq_nodes.sh  
```

return nodes and vhosts and queues
```
rabbitmq/detect_rabbitmq_nodes.sh  queue 
```

return nodes and vhosts and exchanges
```
rabbitmq/detect_rabbitmq_nodes.sh  exchange 
```

node - name node
vhost - name vhost
metric - name metric
item - name queue or exchange
```
rabbitmq/rabbitmq-status.sh [node] [vhost] [mertic] [item]
```
