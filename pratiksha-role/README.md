Role Name
=========

This Ansible role sets up Docker and Docker Compose on Red Hat-based systems. It adds the Docker repository, installs Docker and Docker Compose, and manages a Docker Compose configuration to deploy services.

Requirements
------------

- Ansible 2.9 or later
- Red Hat-based system (e.g., RHEL, CentOS, Fedora)
- Python 3 and pip (for Docker Compose installation)
- Internet access to download Docker and Docker Compose

Role Variables
--------------

The role does not require any specific variables. However, you can customize the Docker Compose file template as needed by modifying the `docker-compose.yml.j2` Jinja2 template.

Dependencies
------------

None.

Example Playbook
----------------

- hosts: all
  become: yes
  roles:
    - role: docker-compose

License
-------

BSD

Author Information
------------------

Author's name should be Pratiksha Pawar
