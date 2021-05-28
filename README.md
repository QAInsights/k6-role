k6
=========

An Ansible role to install [k6](https://github.com/k6io/k6) in CentOS.

Requirements
------------

- None

Role Variables
--------------

Following are the variables you can set in `defaults\main.yml`:

- Download URL

Dependencies
------------

- None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: k6
      hosts: servers
      become: yes
      roles:
        - qainsights.k6_role

License
-------

MIT

Author Information
------------------

NaveenKumar Namachivayam

- [Blog](https://qainsights.com)
- [Free YouTube Tutorials](https://www.youtube.com/QAInsights)
