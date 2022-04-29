Role Name
=========

The AWS ec2 instances running Ubuntu need to be kept up-to-date and thus this role

Requirements
------------

The requirements for this are the EC2 collection since it is running in AWS cloud

Role Variables
--------------

There several types of variables and it would be much better to have some 
distinguished grouping done on them.  Having the variables just list out
seems unwieldy and down the line will become unmanageable.  A TODO would 
without a doubt include building these into a more organized structure

Dependencies
------------

There are some system services that are dependencies in that I am just making
this all up as I go along ;)


Example Playbook
----------------

    - hosts: Ubuntu
      roles:
           { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Tim Konick -- https://github.com/tijko of NEDD
