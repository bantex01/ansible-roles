Role Name
=========

A simple role to configure collectd. Further updates to follow, currently only useful for my personal use.  

Requirements
------------

None  

Role Variables
--------------

graphite_host: Graphite host name to send metrics to  
graphite_port: Graphite port to send metrics to  


Dependencies
------------

None  

Example Playbook
----------------

    - hosts: servers
      roles:
         - configure_collectd

License
-------

NA  

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
