# Repo: REMI

Manage REMI  repository.

# Requirements

For supported systems  see https://rpms.remirepo.net/. If your system is not supported,
the role tasks will be skipped.

For supported system by this role, see the `vars/os-<system>` files.

Feel free to add any new linux distribution and version if missing.

# Role Variables

- `remi_repo_package_state`: the epel package presence  state

# Dependencies

There no external dependencies.

# Example Playbook

To install role, add following line to **ansible-galaxy** requirements file
```
- src: https://github.com/securCom/ansible-role_repo-remi
  version: master
  name: securcom.remi
```

```
- hosts: servers
  roles:
     - securcom.remi
```

# License

BSD

# Author Information


- Peter Hudec (@hudecof)