![Ansible Lint](https://github.com/johanneskastl/ansible-role-install_microk8s_snap/workflows/Ansible%20Lint/badge.svg)

# install_microk8s_snap

Install microk8s as snap

## Requirements

None.

## Role Variables

There are two optional variables, that influence the role's behaviour:

- `install_microk8s_snap_enable_hostpath_storage_addon` (Boolean): whether the
  hostpath-storage addon should be enabled (default: `true`)
- `install_microk8s_snap_enable_ingress_addon` (Boolean): whether the ingress
  addon should be enabled (default: `true`)

## Dependencies

None

## Example Playbook

```yaml
- hosts: microk8s-server
  roles:
    - role: 'johanneskastl.install_microk8s_snap'
```

## License

BSD-3-Clause

## Author Information

I am Johannes Kastl, reachable via git@johannes-kastl.de
