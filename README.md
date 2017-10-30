shared/git
==========

Installs git.

Requirements
------------

No special pre-requisites.

Role Variables
--------------

| Name                 | Default | Description                          |
|----------------------|---------|--------------------------------------|
| apt_cache_valid_time | 21600   | Run apt-get update if cache is older |


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: git
           apt_cache_valid_time: 21600
