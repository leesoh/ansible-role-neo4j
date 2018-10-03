Role Name
=========

The Neo4j graph database

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

This role installs Java 8 but does not set it as the default. One way to do this is to add it to your path, like so:

```shell
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/;export PATH=$JAVA_HOME:/bin:$PATH
```

Example Playbook
----------------

- hosts: servers
  roles:
  - leesoh.neo4j

License
-------

BSD-3

Author Information
------------------

Website: https://www.neo4j.com