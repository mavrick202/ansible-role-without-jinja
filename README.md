---
  - name: checing the roles
    hosts: web
    roles:
     - ansible-role-without-jinja
