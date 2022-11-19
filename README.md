ansible-freeswitch-role
=========

Ansible role to install on freeswitch linux machines(Currently on debian 11)

Requirements
------------

Ansible version greater than 2.1 and python3.

Environment Variables
---------------------

Set TOKEN=yoursignalwiretoken using command ```export TOKEN=yoursignalwiretoken```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
- name: Playbook to install freeswitch from ansible-freeswitch-role
  hosts: dev
  gather_facts: yes
  become: no
  vars:
    ansible_python_interpreter: /usr/bin/python3

  roles:
    - role: '/root/.ansible/roles/ansible-freeswitch-role'
```
