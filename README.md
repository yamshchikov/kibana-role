Role Name
=========

Downloads and installs Kibana

Role Variables
--------------

There are two vars in the role:

```yaml
kibana_version: "7.12.1" # Choose Kibana version
kibana_home: "/opt/kibana/{{ kibana_version }}" # Dir to unpackage distro and create KIBANA_HOME env
```

Example Playbook
----------------

An example of how to the role:

```yaml
- hosts: all
  roles:
    - kibana-role
```

License
-------

BSD
