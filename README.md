# Ansible-Role: acr-ansible-iptables-forwarding

AIT-CyberRange: Enable ipv4 forwarding and persist settings


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
iptables_out_interfaces: 
    - ens3
iptables_ipversions:
    - v4
    - v6
```

## Example Playbook

```yaml
- hosts: localhost
  roles:
    - acr-ansible-iptables-forwarding
```

## License

GPL-3.0

## Author

- Lenhard Reuter