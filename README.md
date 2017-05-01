=========

base_epel is a role that other base roles depend on.

Requirements
------------

RHEL- like system


Role Variables
--------------
define or undefine the base proxy url, but do it on the block, or don't
     base_proxy_url: http://172.16.1.2:8080

     base_proxy_env:

        http_proxy: "{{ base_proxy_url | default(omit) }}"

        https_proxy: "{{ base_proxy_url | default(omit) }}"

Dependencies
------------

base_common is a role that other base roles depend on.

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
