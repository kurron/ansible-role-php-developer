Role Name
=========

Installation of tools than any self-respecting PHP developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* php_phpstorm_install: true
* php_phpstorm_version: 2016.2.1
* php_phpstorm_build: 162.1889.1

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.php-developer, php_phpstorm_version: 2016.2.1, php_phpstorm_build: 162.1889.1 }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
