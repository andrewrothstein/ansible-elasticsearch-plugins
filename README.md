elasticsearch-plugins
=====================

Installs a bunch of elasticsearch plugins

Requirements
------------

elasticsearch installed

Role Variables
--------------

elasticsearch_plugins is a list of pairs. The 'plugin' value is the name of the plugin. To be idempotent the 'creates' value is the path in the plugins directory created by the install.

Dependencies
------------

andrewrothstein.elasticsearch

License
-------

MIT

Author Information
------------------

Andrew Rothstein andrew.rothstein@gmail.com
