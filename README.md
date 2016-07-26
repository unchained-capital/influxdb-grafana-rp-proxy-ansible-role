Role Name
=========

Deploys a daemon running the [InfluxDB-Grafana Retention Policy (RP) Proxy](https://github.com/unchained-capital/influxdb-grafana-rp-proxy)

Requirements
------------

You should already have Grafana and InfluxDB ready; this role does not
set up those services.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
   - role: influxdb_grafana_rp_proxy
```

License
-------

Apache
