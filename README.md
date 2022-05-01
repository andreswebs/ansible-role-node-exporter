# ansible-role-node-exporter

Ansible role to install the Prometheus node_exporter.

## Install

```sh
ansible-galaxy install andreswebs.node_exporter
```

## Example Playbook

```yaml
---
- hosts: servers
  roles:
    - role: andreswebs.node_exporter
```

## Authors

**Andre Silva** [@andreswebs](https://github.com/andreswebs)

## License

This project is licensed under the [Unlicense](UNLICENSE.md).
