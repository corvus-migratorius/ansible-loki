loki
=========

Installs promtail with systemd service.

Requirements
------------

Role Variables
--------------

(optional)
loki_version: version to install

Dependencies
------------

No

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: loki
           loki_version: 2.7.3

License
-------

MIT

Author Information
------------------

Alexander Gorelyshev and Danilkin Danila (MIPT)

Genlab LLC

corvus-migratorius@proton.me
