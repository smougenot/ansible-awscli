Ansible Role for AWSCLI
==============================

This is an Ansible role for installing awscli: https://github.com/aws/aws-cli. 
This role installs awscli using pip, sets up awscli's config file, and also enables auto completion for awscli commands.

Requirements
------------

pip (python-pip on Ubuntu/Debian) needs to be installed for this role to work.

Role Variables
--------------

* awscli_user: ubuntu
* awscli_group: ubuntu
* awscli_user_home: /home/ubuntu

Dependencies
------------

None

Example Playbook
----------------

See test/test.yaml 

License
-------

BSD
