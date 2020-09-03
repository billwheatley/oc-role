oc-role
=========

Ansible Role to install the oc tool (Red Hat OpenShift cli) on a given machine.  This will also install bash completion for `oc` as well.

This was designed to install the official Red Hat certified version which is behind a pay wall at <https://access.redhat.com>.

This was also designed as part of a desktop provisioning playbooks found here <https://github.com/billwheatley/provision-desktop>

Requirements
------------

- A Red Hat like distribution ie: RHEL, Fedora, Centos.
- An official Red Hat oc gz.tar downloaded locally on machine to which is to be installed.

Role Variables
--------------

`oc_archive` : This is the file location to the oc archive to install ex: `/home/myuser/automated-install/archive/oc-4.5.7-linux.tar.gz`

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- name: My Playbook
  hosts: desktop
  roles:
    - role: oc-role
      oc_archive: "/home/myuser/automated-install/archive/oc-4.5.7-linux.tar.gz"
```

License
-------

GPLv2

Author Information
------------------

Contact via [Github](https://github.com/billwheatley/)
