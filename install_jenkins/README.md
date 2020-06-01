Role Name
=========

Role to install jenkins - CentOS tested only  

Requirements
------------

None  

Role Variables
--------------

jenkins_repo: https://pkg.jenkins.io/redhat-stable  
jenkins_repo_name: jenkins.repo  
jenkins_key: https://pkg.jenkins.io/redhat-stable/jenkins.io.key  

  
Dependencies
------------

None  

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - install_jenkins  

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
