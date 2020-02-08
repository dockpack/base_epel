[![Galaxy](https://img.shields.io/badge/galaxy-dockpack.base__epel-blue.svg?style=flat)](https://galaxy.ansible.com/dockpack/base_epel)
![Build Status](https://api.travis-ci.com/dockpack/base_epel.svg)

base_epel
=========

base_epel is a role that other base roles depend on.

Requirements
------------

RHEL- like system


Role Variables
--------------
define or undefine the yum proxy

     yum_proxy_url: http://proxy.example.com:3128


Dependencies
------------

base_common is a role that other base roles depend on for RHEL behind a proxy.

Example Usage
----------------

Refer to a complete build server https://github.com/bbaassssiiee/buildserver

License
-------

MIT

Author Information
------------------

Bas Meijer
@bbaassssiiee
