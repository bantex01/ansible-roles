prepare_splunk_app_for_install
=========

A small role to prepare a splunk git artifact in readiness for copying to an ansible managed host. This role is only intended for my own personal use.  

Requirements
------------

None

Role Variables
--------------

No specific variables are set but you should call the role like this:  
  
- { role: prepare_splunk_app_for_install, app: "{{ splunk_app_array }}" }  

where splunk_app_array is:  
    vars:  
    splunk_app_array:  
      - splunk_app1  
      - splunk_app2

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  roles:
    - { role: prepare_splunk_app_for_install, app: "{{ splunk_app_array }}" }


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
