Role Name
=========


Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

Test Role
---------

```bash 
tox -e py37-ansible28 -- molecule test -s default
```

License
-------

{{ cookiecutter.license }}

Author Information
------------------

{{ cookiecutter.author }}
