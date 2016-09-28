# BOSH release of Zabbix agent

The job has 2 parameters
- zabbix.server_ip - Address of Zabbix server
- zabbix.host_metadata - agent host metadata (you may use it for agent auto-registration)

Add the template to your job:
- {name: zabbix_agentd, release: zabbix_agent}
