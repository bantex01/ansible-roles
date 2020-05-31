Role Name
=========

Role to install grpahite - Note - this is the docker container version as detailed here: https://graphite.readthedocs.io/en/latest/install.html  

Requirements
------------

None  

Role Variables
--------------

None  

Dependencies
------------

install_docker will run before this  

Example Playbook
----------------

    - hosts: servers
      roles:
         - install_graphite 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
