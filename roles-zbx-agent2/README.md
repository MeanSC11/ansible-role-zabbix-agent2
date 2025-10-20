# zabbix-agent2-gpu (Ubuntu 24.04)

Installs Zabbix Agent2

## Usage
```yaml
- hosts: all
  become: true
  vars:
    zbx_server_ip: "xxx.xxx.xx.xx"
  roles:
    - zabbix-agent2-gpu
