oc-role
=========

Ansible Role to install the oc tool (Red Hat OpenShift cli) on a given machine.  This will also install bash completion for `oc` as well.

This was designed to install the official Red Hat certified version.

This was also designed as part of a desktop provisioning playbooks found here <https://github.com/billwheatley/provision-desktop>

Requirements
------------

- A distribution with `dnf` or `yum` or `apt`

Role Variables
--------------

none

Example Playbook
----------------

```yaml
- name: My Playbook
  hosts: desktop
  roles:
    - role: oc-role
```

License
-------

GPLv2

Author Information
------------------

Contact via [Github](https://github.com/billwheatley/)
