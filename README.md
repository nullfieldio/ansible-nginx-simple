nginx-simple
=========

Adds NGINX repo and then installs.

Role Variables
--------------

* "nginx_conf" config file you want to point nginx at

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
      - role: tobybro-nginx-simple
        nginx_conf: /home/application/nginx/nginx.conf

