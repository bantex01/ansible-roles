Role Name
=========

Simple role to install grafana  

Requirements
------------

None  

Role Variables
--------------

grafana_repo_file - The yum repo file to install (there are two, oss and enterprise) - this defaults to oss  
grafana_type - The type of install you want (oss or enterprise) to install (used by yum) - defaults to "grafana" (could be grafana-enterprise)  


Dependencies
------------

None  

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - install_grafana

License
-------

NA  

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
