# ansible-role-prometheus-node-exporter

Ansible role to install the Prometheus node_exporter.

## Install

```sh
ansible-galaxy install andreswebs.prometheus-node-exporter
```

## Example Playbook

```yaml
---
- hosts: servers
  roles:
    - role: andreswebs.prometheus-node-exporter
```

## Authors

**Andre Silva** [@andreswebs](https://github.com/andreswebs)

## License

This project is licensed under the [Unlicense](UNLICENSE.md).
