# [aussielunix.powerdns-admin](#aussielunix.powerdns-admin)

Install and configure [PowerDNS Admin](https://github.com/PowerDNS-Admin/PowerDNS-Admin)

## Example Playbook

```yaml
---
- name: Example
  hosts: dns
  become: true
  gather_facts: yes

  roles:
    - role: geerlingguy.mysql
    - role: powerdns.pdns
    - role: geerlingguy.nodejs
    - role: andrewrothstein.yarn
    - role: aussielunix.powerdns-admin
```

## Role Variables

See [defaults/main.yml](defaults/main.yml) for all variables and their defaults.

## Requirements

One the same node:

* yarn
* nodejs
* python

Access to the following - can be on or off node:

* mysql or postgres
* PowerDNS Authoratative Server

## Compatibility

This role has been tested on the following Operating Systems:

* Ubuntu Focal (20.04)

## Testing

**TODO**
[Tests](https://github.com/aussielunix/ansible-role-powerdns-admin/actions) are run on every commit, pull request, release and periodically.  
If you find issues, please register them in [GitHub](https://github.com/aussielunix/ansible-role-powerdns-admin/issues)  
Testing is done using [GitHub Actions](https://github.com/features/actions) and Ansible itself.

## License

[MIT](LICENSE)

## Author Information

[Mick Pollard](https://aussielunix.io/)  
[@aussielunix](https://twitter.com/aussielunix)

**Original Author:** Natthaphon Phoonsookserm

