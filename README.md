Role Name
=========

Ansible role intended to install and configure a reverse proxy and redirect the traffic from http to https using apache.


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
| apache_ssl_certificate_file  |   |
| apache_ssl_certificate_key  |   |
| apache_proxy_home_pass  |   |
| apache_proxy_pass  |   |
| apache_proxy_pass_reverse  |   |

License
-------

GPL

Author Information
------------------

This role was created in 2019 by Marce Godoy.
