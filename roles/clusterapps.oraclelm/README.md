clusterapps.oraclelm
=========

Install and register client to Oracle Linux Manager

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

olm_master_url| fqdn of master OLM server

olm_activation_key| 1-12345


Dependencies
------------

None. But, clusterapps.rhbase helps.

Example Playbook
----------------

An example of how to use the role.

    - hosts: servers
      roles:
         - clusterapps.oraclelm

License
-------

BSD

Author Information
------------------

Michael Cleary <mcleary@clusterapps.com>