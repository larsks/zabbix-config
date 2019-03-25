# zabbix-config

Repository for zabbix configuration file and deployment tools.

## How to use this role

Clone this role into your `roles/` directory:

    git clone https://github.com/CCI-MOC/zabbix-config roles/zabbix-config

Add this role to a playbook. You will need to set `become: true`:

    - hosts: zabbix-hosts
      become: true
      roles:
        - zabbix-config

## Configuration

- `zabbix_release_url`
- `zabbix_agent_type`
- `zabbix_server`
- `zabbix_tls_psk_identity`
