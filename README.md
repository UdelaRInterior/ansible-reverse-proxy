Role Name
=========

Ansible role intended to install and configure a reverse proxy and redirect the traffic from http to https using apache.


Requirements
------------

Ansible version >= 2.7

Role Variables
--------------

| Name  | Description |
| ------------- | ------------- |
| inventory_hostname   | name of the host  |
| reverse_proxy_type   | apache  |
| apache_server_name   | server domain name |
| apache_server_admin  | server admin email  |
| apache_server_alias  | list of alternate server names  |
| apache_redirect_url  | url for Redirect directive  |
| apache_ssl_certificate_file  | ssl cert file location |
| apache_ssl_certificate_key  | ssl key file location   |
| apache_proxy_home_pass  | incoming requests  |
| apache_proxy_pass  | backend server  |
| apache_proxy_pass_reverse  | backend server  |
| apache_proxy_ssl  | needs true to proxy an https service  |

License
-------

(c) Universidad de la República (UdelaR), Red de Unidades Informáticas de la UdelaR en el Interior. Licenced under GPL-v3.


Author Information
------------------

[@Dkmarce](https://github.com/Dkmarce)  
[@UdelaRInterior](https://github.com/UdelaRInterior)  
https://proyectos.interior.edu.uy/
