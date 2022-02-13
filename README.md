# [aussielunix.powerdns-admin](#aussielunix.powerdns-admin)

<img src="https://docs.ansible.com/ansible-tower/3.2.4/html_ja/installandreference/_static/images/logo_invert.png" width="10%" height="10%" alt="Ansible logo" align="right"/>
<img src="https://img.shields.io/ansible/role/d/"/> <img src="https://img.shields.io/ansible/quality/"/>
[![CI](https://github.com/aussielunix/ansible-role-aussielunix.powerdns-admin/actions/workflows/ci.yml/badge.svg?event=push)](https://github.com/aussielunix/ansible-role-aussielunix.powerdns-admin/actions)

Install and configure aussielunix.powerdns-admin on your system.

## Example Playbook

```yaml
---
- name: Example
  hosts: all
  become: false
  gather_facts: yes

  roles:
    - role: aussielunix.aussielunix.powerdns-admin
```

## Role Variables

See [defaults/main.yml](defaults/main.yml) for all variables and their defaults.

## Requirements

None.

## Compatibility

This role has been tested on the following Operating Systems:

* Manjaro Stable

## Testing

[Tests](https://github.com/aussielunix/ansible-role-aussielunix.powerdns-admin/actions) are run on every commit, pull request, release and periodically.  
If you find issues, please register them in [GitHub](https://github.com/aussielunix/ansible-role-aussielunix.powerdns-admin/issues)  
Testing is done using [GitHub Actions](https://github.com/features/actions) and Ansible itself.

## License

[MIT](LICENSE)

## Author Information

[Mick Pollard](https://aussielunix.io/)  
[@aussielunix](https://twitter.com/aussielunix)
