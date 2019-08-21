Role Name
=========

Ansible role intended to install and configure a reverse proxy.


Requirements
------------

No requirements.

Role Variables
--------------

| Name  | Description |
| ------------- | ------------- |
| inventory_hostname  | name of the host  |
| reverse_proxy_type  | apache  |
| apache_server_admin  | name of the server admin  |
| apache_server_alias  |   |
| apache_https  |   |
| apache_ssl_certificate_file  |   |
| apache_ssl_certificate_key  |   |
| apache_proxy_pass  |   |
| apache_proxy_pass_reverse  |   |

Dependencies
------------

No dependencies.

Example Playbook
----------------

License
-------

MIT/BSD

Author Information
------------------

This role was created in 2019 by Marce Godoy.
