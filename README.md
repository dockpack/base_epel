![Build Status](https://api.travis-ci.org/dockpack/base_epel.svg)

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
