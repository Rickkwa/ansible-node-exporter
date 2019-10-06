Ansible Role: node_exporter
====

[![Ansible Role](https://img.shields.io/ansible/role/d/43832)](https://galaxy.ansible.com/rickkwa/node_exporter)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/43832)](https://galaxy.ansible.com/rickkwa/node_exporter)

Ansible role for installing the Prometheus node_exporter to be managed by systemd.

Requirements
----

Ansible 2.5+

Configurable Options
----

Configurable options for the role can be viewed in [defaults/main.yml](defaults/main.yml).

Managing the Service
----

After running the role, you can manage `node_exporter` as a service under systemd.

```bash
systemctl [status|start|stop|restart] node_exporter
```

License
----

MIT. See [LICENSE](LICENSE.md) for more information.
