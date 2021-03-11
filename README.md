RANCHER HOSTS DELETE
====================

This roles delete hosts in rancher

Example Playbook
----------------

Here is a use case :

```yaml
  - hosts: servers
    remote_user: mysuperadmin
    vars:
     - rancher_api_key: "admin"
     - rancher_api_secret: "r@nch3r!"
     - rancher_project_name: "myproject"
     - rancher_project_id: "{{ rancher_pj.rancher_project_id }}"
    roles:
      - ansible-role-rancher-hosts-delete
```

License
-------

MIT
