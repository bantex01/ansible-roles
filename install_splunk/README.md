Role Name
=========

Install Splunk

Requirements
------------

There are no specific requirements for this role other than internet access on the host you intend to run this on. The host will attempt to use the get_url ansible task to retrieve the splunk installation image.

Role Variables
--------------

The following variables are required and supplied in defaults (as below)

The URL of the wget splunk image page  
splunk_url: https://www.splunk.com/bin/splunk/DownloadActivityServlet?architecture=x86_64&platform=linux&version=8.0.3&product=splunk&filename=splunk-8.0.3-a6754d8441bf-Linux-x86_64.tgz&wget=true

Splunk will be installed to this path + /splunk - so /opt means install to /opt/splunk  
splunk_path: /opt

The splunk admin user  
splunk_user: admin

The splunk admin user password  
splunk_password: changeme

The user splunk should run as  
splunk_run_as_user: splunk

The group the splunk user should belong to  
splunk_run_as_user_group: splunk


Dependencies
------------

There are no dependencies for this role.
